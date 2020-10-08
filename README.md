# Beginnerrr
Can someone please explain me about github? I am beginner I am new to this platform can somebody explain me ??
Where can I ask doubt?
I have a doubt related to programming 
What will be the output of this code and why can somne exlain me plss..
class Main {   
   public static void main(String args[]) {      
         int t;      
         System.out.println(t); 
    }   
}
I also don't know how to ask doubts and all ;) as I am also new user here
coming to your doubt:
Output For the above Code would be 
"Compilation Error" Because t is just a reference, the object referred by t is not allocated any memory. Unlike C++, in Java all non-primitive objects must be explicitly allocated and these objects are allocated on heap. The following is corrected program.
class Test { 
int i; 
} 
class Main { 
public static void main(String args[]) { 
	Test t = new Test(); 
	System.out.println(t.i); 
} 
