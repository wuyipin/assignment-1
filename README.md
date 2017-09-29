# assignment-1
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
