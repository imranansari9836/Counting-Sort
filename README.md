class Solution
{
    //Function to arrange all letters of a string in lexicographical 
    //order using Counting Sort.
    public static String countSort(String arr)
    {
        // code here
        char[]ar=arr.toCharArray();
        Arrays.sort(ar);
        String s=String.valueOf(ar);
        return s;
        }
}
