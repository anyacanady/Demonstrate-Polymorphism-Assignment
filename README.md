# Demonstrate-Polymorphism-Assignment
This is a Java Assignment
Assignment Instructions
OVERVIEW
Polymorphism enables you to “program in the general” rather than “program in the specific.” In
particular, polymorphism enables you to write programs that process objects that share the same
superclass, either directly or indirectly, as if they were all objects of the superclass; this can
simplify programming.
INSTRUCTIONS
Modify the payroll system of Figs. 10.4–10.9 to include an additional Employee subclass
PieceWorker that represents an employee whose pay is based on the number of pieces of
merchandise produced.
Class PieceWorker should contain private instance variables wage (to store the employee’s wage
per piece) and pieces (to store the number of pieces produced).
Provide a concrete implementation of method earnings in class PieceWorker that calculates the
employee’s earnings by multiplying the number of pieces produced by the wage per piece.
Instantiate a PieceWorker object in PayrollSystemTest.java and add a print statement after the
print statement for basePlusCommissionEmployee for your new PieceWorker object thereby
demonstrating that the new class works.
Modify the array of Employee variables in PayrollSystemTest.java to store references to objects
of each concrete class in the new Employee hierarchy (SalariedEmployee,
CommissionEmployee, HourlyEmployee, BasePlusCommissionEmployee, and now
PieceWorker).
For each Employee, display its String representation and earnings.
