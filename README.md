# DEAR-JAVA
so in the second semester we are lerning the java language 
java is totally or purily object oriented language

// first is DATA TYPES
. A type identifies a set of values and their representation in memory and a set of operations that transform these values into other values of that set
// Java is Strongly typed language
// there are two type of data type 
// 1st is primitive and second is user defined data type
// in user defined data type have not include keywords

/* e.g boolean
char
byte
short
int
long
float
double
*/

Ox > hexadecimal
O177 > Octal
Ob > Binary

// in java there are three types of comment
// Blocked style comment contain multypule comment /* */
// line  style Comment
// Documentation comment /** */

class Box {
private int length,breadth,height;

public void setDimension(int l, int b, int h){
length=l;
breadth=b;
height=h;
         }
         public void showDimension(){
         System.out.print("L = "+ length);
         System.out.print("B = "+ breadth);
         System.out.print("H = "+ height);
  }
   }
   class Example
   {
   public static void main(String args []){
   
   // make the object
   Box smallBox = new Box();
   // and here is memory is allocate
   smallBox.setDimension(12,10,15);
   smallBox.showDimension();
   
   // and we make same object another time then first will be called garbage box
smallBox = new Box();
smallBOx.showDimension();
// output is 0 0 0
}
}
