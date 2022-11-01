
```js
abstract class Shape
{
        public abstract double getArea(); 
}

class Rectangle implements Shape
{
        public abstract double length();
        public abstract double width();
        public HourlyEmployee(double length, double width)
        {
            h=hour;
            w = hourlyWage;
        }
        public double getArea(){
        }
        public double toString(){
        }   
}

class Triangle implements Shape
{
        public abstract double base();
        public abstract double height();
        public double Salary(){
        }
        
}
```

---
## CShape.java 
```js
abstract class CShape{

    protected String color;
    public void setColor(String str){
        color = str;
    }
 
    public abstract void show();
}
```
## CTriangle.java
```js
class CTriangle extends CShape{
    double ca, cb, cc;
    public CTriangle(double a, double b, double c){
        ca=a;
        cb=b;
        cc=c;
    } 
    public void show() {
        System.out.print("color="+color+"  ");
        System.out.print("area="+0.5*ca*cb);
    } 
}
```

## app11.java
```js
public class app11 {
   public static void main(String[] args) {
    CTriangle ct = new CTriangle(3, 4, 5);
    ct.setColor("red");
    ct.show();
    }
}
```













