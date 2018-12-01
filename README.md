# ArrayList

public class ArrayListString {
    
    public static void main(String[] args) {
        
        ArrayList<String> obj = new ArrayList<String>();
        obj.add("Sam");
        obj.add("Ram");
        obj.add("Rahul");
        obj.add("Dipin");
        System.out.println(obj);
        obj.add(1, "Rog");
        System.out.println(obj);
        obj.remove("Rahul");
        System.out.println(obj);
        System.out.println("Size = " + obj.size());
        obj.remove(2);
       System.out.println(obj);
       obj.set(1, "Kris");
       System.out.println(obj);
       int a = obj.indexOf("Dipin");
       System.out.println(a);
       String b = obj.get(1);
       System.out.println(b);
       System.out.println("Size = " + obj.size());
       System.out.println("Element :" + obj.contains("Rog"));
       
       Collections.swap(obj, 0, 1);
       System.out.println("List : " + obj);
       Collections.sort(obj);
        System.out.println("List : " + obj);
        Collections.sort(obj);
        Collections.reverse(obj);
        System.out.println("List : " + obj);
       obj.clear();
       System.out.println("List : " + obj);
    }
    
}
