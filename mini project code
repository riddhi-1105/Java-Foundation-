package com.student.management;

class Person { 

    String name;

    int age;

    Person(String name, int age) {

        this.name = name;

        this.age = age;

    }

    void displayPerson() {

        System.out.println("Name: " + name);

        System.out.println("Age: " + age);

    }

}

class Student extends Person {

    int rollNo;

    double marks;

    Student(String name, int age, int rollNo, double marks) {

        super(name, age);

        this.rollNo = rollNo;

        this.marks = marks;

    }

    void displayStudent() {

        displayPerson();

        System.out.println("Roll Number: " + rollNo);

        System.out.println("Marks: " + marks);

    }

}

class GraduateStudent extends Student {

    String specialization;

    GraduateStudent(String name, int age, int rollNo, double marks, String specialization) {

        super(name, age, rollNo, marks);

        this.specialization = specialization;

    }

    void displayGraduateStudent() {

        displayStudent();

        System.out.println("Specialization: " + specialization);

    }

}

public class StudentManagementSystem {

    public static void main(String[] args) {

        GraduateStudent gs = new GraduateStudent(

                "Riddhi", 19, 66, 85.6, "Computer Science"

        );

        System.out.println("----- Student Details -----");

        gs.displayGraduateStudent();

    }

}
