## MONDAY, February 3rd

Dear Diary,

today was the first day of the course. Apart from formal and organizations aspects, there was a bunch of installing
and setting up to do (GitHub, GitHub Classroom, Git Kraken, Visual Studio Code).

Then, individually, we did a video tutorial for IntelliJ. It went... interesting for most of us.

KNOWLEDGE GAINED:
* IntelliJ may auomatically insert comments that can be mistaken for code. 
* When I am uncertain and I delete the element in question AND the whole code still works - then it's a comment.

IMPROVEMENT/INSIGHT NEEDED:
* I need to devote some time to how classes, methods, constructors and their interaction works.
* Also, I might understand the concept of GIT and/or the sync better if I was provided a more complex example.
* This example should demonstrate a collaboration of several people.
* The example video from GIT does not provide that level of detail.


Also, dear diary, I am confident that - in time - I can abandon this style of writing and stop resembling an overly eager
nine-year-old who does everything by the book in fear of irrational parental retaliation.

_Toodles!_


## WEDNESDAY, February 5th

__KNOWLEDGE GAINED:__
* I think I finally understood how loops work
* following I share some code that examplifies what I worked on
* I had a first glimpse into working with program flowcharts; they seem useful, yet a bit clunky to draw


''''
   public static void main(String[] args) {
        //TODO 4 killsteaks, Baal at the end,
        // minions: easy, medium, difficult
        // TODO: create a number of loops that display the waves of enemies in a video game

        int easySlain, medSlain, diffSlain, totalSlain;
        easySlain = 0;
        medSlain = 0;
        diffSlain = 0;
        totalSlain = 0;

        for (int baal = 1; baal <=1; baal++) {
            for (int diff = 1; diff <=2; diff++) {
                for (int med = 1; med <=3; med++) {
                    for (int easy = 1; easy <=5; easy++) {
                        System.out.println("easy enemies lay slain: "+easy);
                        easySlain++;
                    }
                    System.out.println("medium enemies lay slain: "+med);
                    medSlain++;
                }
                System.out.println("difficult enemies lay slain: "+diff);
                diffSlain++;
            }
            System.out.println("Baal is muh biatch!");
            System.out.println(easySlain);
            System.out.println(medSlain);
            System.out.println(diffSlain);
            totalSlain = easySlain + medSlain + diffSlain;
            System.out.println("total minions slain: "+totalSlain);
        }
''''


__IMPROVEMENT/INSIGHT NEEDED:__
* I am still a bit uncertain how to differentiate with certainty between the increments, the current value of the variable
* and what happens within the loop
