# Lab 1

## Q1: 
> Write a Java program with a method named 'totalSum' that takes in an argument of two integers and return its sum. Call this method from main( ) and print the results.

public class totalSum {

	public static void main(String[] args) {
		int a = 50;
		int b = 30;
		System.out.println(a + b);
	}

}


## Q2:
> Write a Java program with a method named 'getGrades' that will display grades according to the marks entered into the method call as below:
```
Marks        Grade
91-100         A+
81-90          A-
71-80          B+
61-70          B-
51-60          C+
41-50          D-
<=40          Fail
```


public class getGrades {

	public static void main(String[] args) {
		int marks = 85;
		
		if(marks >= 91) {
			System.out.println("Grade A+");
		} else if(marks >= 81 && marks <= 90) {
			System.out.println("Grade A-");
		} else if(marks >= 71 && marks <= 80) {
			System.out.println("Grade B+");
		} else if(marks >= 61 && marks <= 70) {
			System.out.println("Grade B-");
		} else if(marks >= 51 && marks <= 60) {
			System.out.println("Grade C+");
		} else if(marks >= 41 && marks <= 50) {
			System.out.println("Grade D-");
		} else {
			System.out.println("Fail");
		}
			
	}

}



## Q3:
> Write a program to print the factorial of a number by defining a method named 'factorial'. Factorial of any number n is represented by n! and is equal to 1*2*3*....
``` 
4! = 1*2*3*4 = 24
3! = 3*2*1 = 6
2! = 2*1 = 2
Also,
1! = 1
0! = 0
```



public class factorial {

	public static void main(String[] args) {
		int i,fact = 1;
		int n = 4;
		
		for(i = 1; i <= n; i++) {
			fact = fact*i;
		}
		System.out.println("Factorial of "+n+" is: " + fact);
	}

}




## Q4
> Write a Java method to create the area of a pentagon.


public class pentagon {

	public static void main(String[] args) {
		int s = 20;
		int a = 7;
		
		float areaOfPentagon = (float)(5.0/2.0)*s*a;
		System.out.println("Area of pentagon : " + areaOfPentagon);

	}

}





