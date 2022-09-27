// Lecture 3 - Objects, Classes and Methods

public class Date {  // creating a class named Date
     private int day, month, year;  // declaring INSTANCE VARIABLES (specify internal state of object), always private (Encapsulation, hidden inside object)

    public Date(int day, int month, int year){   // CONSTRUCTOR declaration ( method that creates the object)
        this.day = day;                          // Constructors name is always the same as the class name
        this.month = month;                      // this.day = day, sets the instance variable "day" to parameter in constructor
        this.year = year;
    }
        void incrementYear(){      // Method
            //day = 1;
            //month = 1;
            year++;
        }
        void incrementMonth(){
            if (month < 12) {
                month++;
            } else {
                incrementYear();
                month = 1;
            }
        }
        void incrementDay(){}



    public int getDay(){  // accessor method
        return day;
    }

    public static void main(String[] args)
    {
        Date d = new Date(26, 9, 2022);  // Constructs new object "d"
        System.out.println(d);
        d.incrementMonth();
        d.incrementYear();
        System.out.println(d);
        Date d2 = new Date(22, 3, 2022);
        System.out.println(d2);
        System.out.println("Hello world!");
    }

    public String toString(){
        return day + "/" + month + "/" + year;
    }

}
