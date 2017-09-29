# assignment-1
1.1
public static void main(String[] args) {
	    int N=10;
	    int i;
	    int j;
	    for( i=0;i<N+1;i++)
	    {
            	   if(i<N)
            	     {
            	        for(j=0;j<2*(i+1);j++)
            	        {
            	            System.out.print("*");
            	        } System.out.print("\n");
            	      }     
            	      
            	   else 
            	     {
            	        
            	        for(j=0;j<2*N+1;j++)
            	        {
            	            System.out.print("*");
            	        } System.out.print("\n");
            	      }  
	    }
	    for( i=1;i<N+1;i++)
	    {
	        for(j=0;j<22-2*i;j++)
	        {
	            System.out.print("*");
	        }
	        System.out.print("\n");
	    }
		
	}
}
1.2
public class assignment11 {
	public static void main(String args[]) 
	{   
	    //int[] a= new int [14];
	    int[] a= {1,3,11,9,6,12,13,7,4,14,2,15,5,8,10};
	    int n = a.length;   
                  
                    for (int i = 0; i < n - 1; i++) {   
                  
                      for (int j = 0; j < n - 1; j++) {   
                        if (a[j] < a[j + 1]) {   
                  
                          int temp = a[j];   
                  
                          a[j] = a[j + 1];   
                  
                          a[j + 1] = temp;   
                  
                        }   
                  
                      }   
                  
                     }   
	    for(int k=0;k<15;k++)
	    {
	        System.out.println(a[k]);
	        
	    }
        
	 
		
	}
}
 
