# project
import java.util.*;  


public class Employee {
    private String Name ;
    private int ID ; 
    private String PhoneNumber ; 
    private String Xp ; 
    private int Salary ; 
    public static int NumberOfEmployees = 0 ; 
    private String Password ;
      
    Employee(){
        
    }
    
     public Employee(String name ,int id , String phone , String xp ,int salary, String  password   ){
 Name = name ;
      ID = id ; 
      PhoneNumber = phone ; 
      Xp = xp; 
      Salary = salary; 
      Password = password ;
     NumberOfEmployees ++ ; 

         
     }

    public String getName() {
        return Name;
    }

    public void setName(String Name) {
        this.Name = Name;
    }

    public int getID() {
        return ID;
    }

    public void setID(int ID) {
        this.ID = ID;
    }

    public String getPhoneNumber() {
        return PhoneNumber;
    }

    public void setPhoneNumber(String PhoneNumber) {
        this.PhoneNumber = PhoneNumber;
    }

    public String getXp() {
        return Xp;
    }

    public void setXp(String Xp) {
        this.Xp = Xp;
    }

    public int getSalary() {
        return Salary;
    }

    public void setSalary(int Salary) {
        this.Salary = Salary;
    }

    public static int getNumberOfEmployees() {
        return NumberOfEmployees;
    }

    public static void setNumberOfEmployees(int NumberOfEmployees) {
        Employee.NumberOfEmployees = NumberOfEmployees;
    }

    public String getPassword() {
        return Password;
    }

    public void setPassword(String Password) {
        this.Password = Password;
    }

    @Override
    public String toString() {
        return "Employee{" + "Name = " + Name + ", ID = "+ ID + ", PhoneNumber = " + PhoneNumber + ", Xp = " + Xp + ", Salary = " + Salary + ", Password = " + Password + '}';
    }
    
   
 }
