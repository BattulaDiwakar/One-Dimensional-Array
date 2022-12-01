import java.util.*;
public class Search
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int  n = sc.nextInt();
        int arr[] = new int[1000];
        int count=0;
        for(int i = 1;i<=n;i++)
        {
            arr[i] = sc.nextInt();
        }
        int see = sc.nextInt();
        for(int i = 1;i<=n;i++)
        {
            if(arr[i]!=see)
            {
                count = count+1;
            }
        }
        for(int i = 1;i<=n;i++)
        {
            if(arr[i] == see)
            {
                System.out.println(arr[i]+" is present in the array");
            }
            
        }
        
            if(count == n)
            {
                System.out.println(see+" is not present in the array");
            }
        
    }
}
