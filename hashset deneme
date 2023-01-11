# OOP
package collections;
import java.util.*;


public class deneme {

	public static void main(String[] args) {
		
//		HASHSET DENEMESİ
		HashSet h=new HashSet();
		h.add(12);
		h.add("12");
		h.add(12.0);
		h.add(12);   //didn't write 12 again 
		h.add(null);
		Iterator itr=h.iterator();
		while(itr.hasNext()) {
			System.out.println(itr.next());
		}
		LinkedHashSet days=new LinkedHashSet();
		days.add("pazartesi");
		days.add("sal");
		days.add("çrş");
		days.add("prş");
		days.add("pazartesi");
		days.add("cm");
		days.add("cm");
		days.add("cmrts");
		days.remove("pazartesi"); //Didn't print the value 12 at all
		Iterator<String> itr1=days.iterator();
		while(itr1.hasNext()) {
			System.out.println(itr1.next());
		}
			//sorting is unimportant in hashset
//		TREESET
		TreeSet tree=new TreeSet();
		tree.add(15);
		tree.add(10); //print 10-15 because it is written sequentially
//		tree.add(null);  exception
		//tree.add("mer");
//		tree.add("m2");
		Iterator iter3=tree.iterator();
		while(iter3.hasNext()) {
			System.out.println(iter3.next());
		}
//		tree.forEach(item->System.out.println(item)); 
//		instead of while
				
}
}
