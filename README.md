public class Main{
    public static void main(String args[]){
        int arr[]={2,4,5,6,7,8,3,9};
        int k=5;
        {
            for(int i=0;i<arr.length;i++)
            {
                for(int j=i+1;j<arr.length;j++)
                {
                    if(arr[i]<arr[j]){
                        int temp=arr[i];
                        arr[i]=arr[j];
                        arr[j]=temp;
                    }
                }
                if(i==k-1){
                    System.out.println(arr[i]);
                }
            }
        }
    }
}
