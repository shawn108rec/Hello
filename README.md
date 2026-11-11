
class Student {
    int id;
    String name;
    double cgpa;

    void display() {
        System.out.println("ID: " + id);
        System.out.println("Name: " + name);
        System.out.println("CGPA: " + cgpa);
    }
}

public class Main {
    public static void main(String[] args) {

        Student s1 = new Student();

        s1.id = 101;
        s1.name = "Shawn";
        s1.cgpa = 3.51;

        s1.display();
    }
}
