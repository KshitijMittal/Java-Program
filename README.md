# Java-Program

// 1st Program
public class Main {
    public static void main(String[] args) {
        System.out.println("Name Kshitij Mittal");
    }
}

// 2nd Program
public class Main {
    public static void main(String[] args) {
        System.out.println("Adresss: Shahadra, Delhi");
    }
}

//3rd Program
import java.util.* ;
public class Main {
    public static void main(String[] args) {
        
        Scanner sc = new Scanner (System.in);
        System.out.print("Enter the value of a: ");
        float a = sc.nextInt();
        System.out.print("Enter the value of b: ");
        float b = sc.nextInt();
        System.out.println("The addition of a and b is "+ (a+b));
        System.out.println("The subtraction of a and b is "+ (a-b));
        System.out.println("The multiplication of a and b is "+ (a*b));
        System.out.println("The division of a and b is "+ (a/b));
        
    }
}

// 4th Program
public class DataTypesInfo {
    public static void main(String[] args) {

        System.out.println("===== PRIMITIVE DATA TYPES =====");
        System.out.println("byte:");
        System.out.println("Size: " + Byte.BYTES + " bytes");
        System.out.println("Range: " + Byte.MIN_VALUE + " to " + Byte.MAX_VALUE);
        System.out.println();

        System.out.println("short:");
        System.out.println("Size: " + Short.BYTES + " bytes");
        System.out.println("Range: " + Short.MIN_VALUE + " to " + Short.MAX_VALUE);
        System.out.println();

        System.out.println("int:");
        System.out.println("Size: " + Integer.BYTES + " bytes");
        System.out.println("Range: " + Integer.MIN_VALUE + " to " + Integer.MAX_VALUE);
        System.out.println();

        System.out.println("long:");
        System.out.println("Size: " + Long.BYTES + " bytes");
        System.out.println("Range: " + Long.MIN_VALUE + " to " + Long.MAX_VALUE);
        System.out.println();

        System.out.println("float:");
        System.out.println("Size: " + Float.BYTES + " bytes");
        System.out.println("Range: " + Float.MIN_VALUE + " to " + Float.MAX_VALUE);
        System.out.println();

        System.out.println("double:");
        System.out.println("Size: " + Double.BYTES + " bytes");
        System.out.println("Range: " + Double.MIN_VALUE + " to " + Double.MAX_VALUE);
        System.out.println();

        System.out.println("char:");
        System.out.println("Size: " + Character.BYTES + " bytes");
        System.out.println("Range: " + (int) Character.MIN_VALUE + " to " + (int) Character.MAX_VALUE);
        System.out.println();

        System.out.println("boolean:");
        System.out.println("Size: Not precisely defined (typically 1 bit or 1 byte)");
        System.out.println("Range: true or false");
        System.out.println();

        System.out.println("===== NON-PRIMITIVE DATA TYPES =====");
        System.out.println("String: Represents a sequence of characters. Size varies based on content.");
        System.out.println("Array: Container object that holds fixed number of values of a single type.");
        System.out.println("Class: Blueprint for creating objects.");
        System.out.println("Object: Root class of all Java classes.");
    }
}

// 5th Program
import java.util.* ;
public class Main {
    public static void main(String[] args) {
        
        Scanner sc = new Scanner (System.in);
        System.out.print("Enter the value in meters: ");
        float a = sc.nextInt();
        System.out.print("Your value in feet is "+ (a * 3.2808399));
        
    }
}

// 6th Program
import java.util.* ;
public class Main{
    public static void main(String[] args) {
        
        Scanner sc = new Scanner (System.in) ;
        System.out.print("Enter the value of a: ");
        int a = sc.nextInt();
        System.out.print("Enter the value of b: ");
        int b = sc.nextInt();
        System.out.print("Enter the value of c: ");
        int c = sc.nextInt();
        
        System.out.println();
        
        System.out.print("Your quadratic equation is: "+ a + "x^2 + " + b + "x + " + c + " = 0");
        
        System.out.println();
        System.out.println();
        
        double D = ((b*b) - (4*a*c));
        System.out.print("The Discriminent of the equation is: "+ D);
        
        System.out.println();
        System.out.println();
        
        if (D > 0) {
            System.out.println("The two real roots are:");
            double root1 = (-b + Math.sqrt(D)) / (2*a);
            double root2 = (-b - Math.sqrt(D)) / (2*a);
             System.out.println("Root 1: " + root1);
            System.out.println("Root 2: " + root2);
        } else if (D == 0) {
            System.out.println("The single real root is:");
            double root1 = -b / (2*a);
            System.out.println("Root: " + root1);
        } else {
            System.out.println("There are no real solution for this quadratic equation.");
        }
        
    }
}
