class Solution
{
    //Function to merge the arrays.
    public static void merge(long arr1[], long arr2[], int n, int m) 
    {
        // code here\
        int len1=arr1.length-1,len2=0;
        while(len1>=0&&len2<m){
            if(arr1[len1]>arr2[len2]){
                long temp=arr1[len1];
                arr1[len1]=arr2[len2];
                arr2[len2]=temp;
                len1--;
                len2++;
            }else{
                break;
            }
        }
        Arrays.sort(arr1);
        Arrays.sort(arr2);
    }
}
