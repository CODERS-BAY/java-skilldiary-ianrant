## WEDNESDAY, February 12th

__KNOWLEDGE GAINED:__
* I had the assistent trainer give me further mini-assignments
* following I share some code that examplifies what I worked on
* these nested loops generate up to 9 (well-formatted) printed rows
* said rows contain 9 characters each, the first row containing 8 dots and 1 numeral "1"
* each row then contains one fewer dot and one more numeral in ascending order (1,22,333,....)

''''
   public static void main(String[] args) {
        int maxRows = 9;

        for (int k=1; k<=maxRows; k++) {
            for (int m= maxRows-k; m>= 1;m--) {
                System.out.print(".");
            }
            for (int o = 1; o <= k; o++) {
                System.out.print(k);
            }
            System.out.println();

        }
    }
''''
* the same thing in reverse

    public static void main(String[] args) {
        int maxRows = 9;
        int current = 0;
        //9 rows, from 111111111 to ........9

        for (int k=1; k<=maxRows; k++) {
            for (int o = maxRows; o >= k; o--) {
                System.out.print(k);
                current = k-1;
            }
            for (int m=0; m < current; m++) {
                System.out.print(".");
            }
            System.out.println();
        }
    }
''''


* FizzBuzz was easy and fun, however, I had to ask the trainer regarding one thing:
* I knew that I (technically) had to fool-proof the comparative operations
* just in case I someone would jumble them; therefor, there may be too many (syntactically)
* but logically, everthing is considered
''''
public static void main(String[] args) {

        String buzz = "Buzz!";
        String fizz = "Fizz!";
        String fizzBuzz = "FizzBuzz!";
        String number;

        for (int i = 1; i <= 100; i++) {
            if (i % 5 == 0 && i % 3 != 0) {
                System.out.println(buzz);
            } else if (i % 3 == 0 && i % 5 != 0) {
                System.out.println(fizz);
            } else if (i % 5 == 0 && i % 3 == 0) {
                System.out.println(fizzBuzz);
            } else {
                number = String.format("%3d", i);
                System.out.println(number);
            }
        }
    }
''''

     


* following I share some code that examplifies what I worked on
* these nested loops generate up to 9 (well-formatted) printed rows
* said rows contain 9 characters each, the first row containing 8 dots and 1 numeral "1"
* each row then contains one fewer dot and one more numeral in ascending order (1,22,333,....)



__IMPROVEMENT/INSIGHT NEEDED:__
* LOOPS: I am still a bit uncertain how to handle increments and handing over values withing nested loops

