# UAS_Algoritma1A
Hilal Fakhri Dzakwan
NPM:1214018
D4TI 1A

public class Bee extends Actor
{
public void act()
    {
         checkKey();
         
    }
    
    public void checkKey(){
       if (Greenfoot.isKeyDown("W"))
       {
         setLocation(getX(), getY()-2);
          
       }
       if (Greenfoot.isKeyDown("S"))
       {
           setLocation(getX(), getY()+2);
        
       }  
       if (Greenfoot.isKeyDown("A")){
           setLocation(getX()-2, getY());
       }
       if (Greenfoot.isKeyDown("D")){
           setLocation(getX()+2, getY());
       }
    }
}    
    
penjelasan:
public class Bee extends Actor adalah Class Bee yang berada di Superclass Actor
public void act adalah prosedur yang bisa dilakukan di dalam class Bee,contoh nya adalah checkKey
checkKey adalah prosedur yang bisa dilakukan oleh Bee yang dimana saat kita menekan keyboard W maka Bee akan bergerak ke atas hal itu karena
  if (Greenfoot.isKeyDown("W"))
       {
         setLocation(getX(), getY()-2);
       }
 disana terletak setLocation(getY()-2); yang dimana disaat kita menekan tombol W maka objek Bee akan bergerak -2 ke atas
 dan berlaku sama untuk tombol S, A, D.
 if (Greenfoot.isKeyDown("S"))
       {
           setLocation(getX(), getY()+2);
        
       }  
 jika kita menekan tombol S maka objek Bee akan bergerak +2 ke bawah.
 if (Greenfoot.isKeyDown("A")){
           setLocation(getX()-2, getY());
       }
 disana juga terletak setLocation(getX()-2 yang dimana saat kita menekan tombol A maka objek Bee akan bergerak -2 ke arah kiri.
 if (Greenfoot.isKeyDown("D")){
           setLocation(getX()+2, getY());
       }
 jika kita menekan tombol D maka objek Bee akan bergerak +2 ke kanan
