# CShape
   abstract class Employee{
        public abstract double Salary();
    }
    
    class HourlyEmployee extends Employee{
        protected int h;
        protected double w;
        public HourlyEmployee(int hour, double hourlyWage){
            h=hour;
            w = hourlyWage;
            
        }
        public double Salary(){
            return w*h;
        }
    }
    
    class MonlyEmployee extends Employee{
        protected double monthlyPay;
        public MonthlyEmployee(double m){
            monthlyPay = m;
        }
        public double Salary(){
            return monthlyPay;
        }
    }
