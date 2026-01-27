  //1.Display Pattern: 
class DisplayPattern { 
    public static void main(String[] args) { 
 
        System.out.println("    J     A     V     V    A"); 
        System.out.println("    J    A A     V   V    A A"); 
        System.out.println("J   J   AAAAA     V V    AAAAA"); 
        System.out.println(" J J   A     A     V    A     A"); 
 
    } 
} 
 
//2.Commandline: 
 
import java.text.DecimalFormat; 
 
class CommandLine { 
    public static void main(String[] args) { 
 
            double width = Double.parseDouble(args[0]); 
            double height = Double.parseDouble(args[1]); 
            double area = width * height; 
    
          DecimalFormat df = new DecimalFormat("0.000"); 
 System.out.println("Area: " + df.format(area)); 
           } 
} 
 
 
//3.Area of Rectangle: 
 
import java.text.DecimalFormat; 
 
class Rectangle { 
    public static void main(String[] args) { 
 
        double width = 4.5; 
        double height = 7.9; 
        double area = width * height; 
 
 DecimalFormat df = new DecimalFormat("0.000"); 
System.out.println("Area: " + df.format(area)); 
} 
}
