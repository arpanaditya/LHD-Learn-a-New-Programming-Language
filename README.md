<h1 align="center">LHD Challenge: Learn a New Programming Language</h1>
<img src="https://uploads-ssl.webflow.com/611141321924300710121a2c/612f90cfea72f6ee37f5472c_Learn-wallpaper-Main.jpg">
<p>This is a part of challenges by <a href="https://localhackday.mlh.io/">Local Hack Day</a> organized by <a href="https://mlh.io/">MLH </a></p>
  
<h2>What we have learnt:</h2>
<h4> JAVA </h4>
<p>We learnt about a new programming language which is JAVA. We have planned and choose a programming language which was new to all of us. We have tried and gone through the basics of that programming language. </p>

<h2>Below there are some basics programs which we have written in java language:</h2>

 - Calculate the Factorial of a Number By <a href="https://github.com/sheetal22sharma">Sheetal Sharma </a>
  ```
  Sheetal's code goes here
  ```
  
  - Print Fibonacci sequence upto n terms By <a href="https://github.com/arpanaditya">Aditya Arpan </a>
  ```
  public class lhd {

	static int fib(int x) {
		if (x == 0) {
			return 0;
		} else if (x == 1) {
			return 1;
		} else {
			return fib(x - 1) + fib(x - 2);
		}
	}
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.print("Enter The number of terms: ");
		int n = sc.nextInt();
		for (int i = 0; i <= n; i++) {
			System.out.print(fib(i) + " ");
		}
	}
}
  ```
  
  - Program to calculate BMI of a person By <a href="https://github.com/Rishita-Nayak">Rishita Nayak </a>
  ```
  public class lhd {
   public static void main(String args[]) {
      Scanner sc = new Scanner(System.in);
      System.out.print("Input weight in kilogram: ");
      double weight = sc.nextDouble();
      System.out.print("\nInput height in meters: ");
      double height = sc.nextDouble();
      double BMI = weight / (height * height);
      System.out.print("\nThe Body Mass Index (BMI) is " + BMI + " kg/m2");
  		 }
	}
  ```
  
  - Print Fibonacci sequence upto n terms By <a href="https://github.com/mrunankpawar">Mrunank Pawar </a>
  ```
  Mrunank's code goes here
  ```
