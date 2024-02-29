Here's a simple POJO (Plain Old Java Object) code snippet without comments:

```java
public class Employee {
    private int id;
    private String name;
    private double salary;

    // Constructors
    public Employee() {
    }

    public Employee(int id, String name, double salary) {
        this.id = id;
        this.name = name;
        this.salary = salary;
    }

    // Getters and setters
    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public double getSalary() {
        return salary;
    }

    public void setSalary(double salary) {
        this.salary = salary;
    }

    // toString method
    @Override
    public String toString() {
        return "Employee{" +
                "id=" + id +
                ", name='" + name + '\'' +
                ", salary=" + salary +
                '}';
    }
}
```

In this code:

- We have a simple `Employee` class with three private fields: `id`, `name`, and `salary`.
- We have provided two constructors: a default constructor and a parameterized constructor to initialize the object.
- Getters and setters methods are provided for accessing and modifying the private fields.
- The `toString()` method is overridden to provide a string representation of the object for easy debugging.
