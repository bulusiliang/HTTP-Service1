
public class BackSet {
	public static String backSet(String str){
		String[] stringArray=str.split(",");
		int len=stringArray.length;
		int[] array=new int[len];
		for(int i=0;i<len;i++){
			array[i]=Integer.parseInt(stringArray[i]);
		}
		int number=1,i=0,j=0;
		int[] backArray=new int[len];
		
		for(i=0;i<len;i++){
			for(j=0;j<len;j++){
				if(j!=i){
					number=number*array[j];
				}
			}
			backArray[i]=number;
			number=1;
		}
		String s ="";
		for(i=0;i<len;i++){
			s=s+backArray[i]+",";
		}
		return s.substring(0,s.length()-1);
	}
	public static void main(String[] args) {
		System.out.println(backSet("1,7,3,4"));
		
		
	}
}
