import java.util.ArrayList;
import java.util.List;


public class prefixstr {

	public static void main(String[] args) {
		
	ArrayList<String> a=new ArrayList<String>();
	 a.add("a");
	 a.add("abcdef");
	 String str="";
	 if(a.size()==0)
	 {
	     System.out.println("");
	 }
	 if(a.size()==1)
	 {
	     System.out.println(a.get(0));
	 }
	  
	 int result=a.get(0).length();
	 int n=a.size();
	  
	 for(int i=0;i<result ;i++)
	 {
	     int j;
	     for(j=1;j<n;j++)
	     {
	         if(a.get(0).charAt(i)==a.get(j).charAt(i))
	         {
	             if(j==n-1)
	             {
	                 str+=a.get(0).charAt(i);
	            	 
	             }
	         }
	         else
	         {
	             i=result;
	             break;
	              
	             
	         }
	          
	          if(result>a.get(j).length())
	     {
	         result=a.get(j).length();
	     } 
	          
	     }
	     
	 }
	 System.out.println(str);
	
	     	
	}
}
