package Demo2;
class Car
{
	String Carname = "Thar" ;
	String Carcolor = "Black" ;
	Short Carno = 2007 ;
	Short Carspeed = 200 ;
}
	class Bike
{
	String Bikename = "Readon" ;
	String Bikecolor = "Red" ;
	Short Bikeno = 4488 ;
	Short Bikespeed = 120 ;
}
class Bicycle
{
	String Bicyclename = "Ranger" ;
	String Bicyclecolor = "Green" ;
	Short Bicyclegear = 7 ;
}
public class Vehicles 
{
	public static void main(String[] args)
	{
		Car c1 = new Car();
		Bike b1 = new Bike();
		Bicycle b2 = new Bicycle();
		
	  System.out.println("Car name is " + c1.Carname);
		System.out.println("Car color is " + c1.Carcolor);
		System.out.println("Car no is " + c1.Carno);
		System.out.println("Car speed is " + c1.Carspeed);
		System.out.println("Bike name is " + b1.Bikename);
		System.out.println("Bike color is " + b1.Bikecolor);
		System.out.println("Bike no is " + b1.Bikeno);
		System.out.println("Bike speed is " + b1.Bikespeed);
		System.out.println("Bicycle name is " + b2.Bicyclename);
		System.out.println("Bicycle color is " + b2.Bicyclecolor);
		System.out.println("Bicycle gear is " + b2.Bicyclegear);
	}
	}
