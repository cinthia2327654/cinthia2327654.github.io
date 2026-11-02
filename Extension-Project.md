# Brainstorm
1.Smart Fitness Tracker
2.Concert Ticket Scalping & Fee Estimator
3.Smart Plant Watering Advisor

* Smart Fitness tracker is a personal health utility that tracks weekly physical activity against a set target.
* People tracking gym time, running miles, or yoga sessions who want quick validation of their weekly progress.
* Information the user will enter is: 1. The users name. 2. Their weekly target. 3. Their actual completed activity.
* Calculates exactly how many extra minutes were completed and prints a celebratory message.
* The type of varible amd data types I will be using is string and Int.


* Begging:
  1.Welcome user: "System.out.println("=== Fitness Tracker & Goal Checker ==="); "
 2. Give instructions: "System.out.println("Please enter your name (Text): "); System.out.println("Please enter your weekly exercise goal (Whole Number in minutes): ");
  Take user input to set up program: "
  Logged prompt: System.out.println("Please enter the actual exercise time you completed this week (Whole Number in minutes): ");
  *Main program
  1.Decision to be made/game structure: • valuate the logged minutes against the target goal inside checkGoalStatus().
	• Decision 1 (Surplus): If actualMinutesLogged > weeklyGoalMinutes, calculate the positive difference.
	• Decision 2 (Exact match): If actualMinutesLogged == weeklyGoalMinutes, trigger the success milestone flag.
	• Decision 3 (Deficit): If neither is true, calculate the remaining minutes needed to reach the target.
  2.Class instance variables/methods: • Store the collected data inside a FitnessTracker object.
	• private String userName
	• private int weeklyGoalMinutes
	• private int actualMinutesLogged
  3.Output/end
  Print recommendation/show update/end game: • Display the tailored motivational feedback based on the decision loop.
	• Output 1: "Great job, [Name]! You crushed your goal by  minutes."
	• Output 2: "Spot on, [Name]! You hit your-minute goal exactly."
	• Output 3: "Keep it up, [Name]! You were  minutes away from your goal." •
  4.End game: Free up system resources.
	• Action: Safely invoke input.close(); on the input stream to cleanly terminate the program run.
 * Plan each part, example:
  1.Welcome user: • print "Welcome to the Personal Fitness Tracker! Here, you will be able to evaluate your weekly exercise habits against your fitness goals."
  2. Give instructions:
	• print "Please enter your name (Data Type: Text):"
	• print "Please enter your weekly goal (Data Type: Whole Number in minutes):"
	• print "Please enter your actual minutes completed (Data Type: Whole Number in minutes):"
  3. Decision to be made:
	• "If actual minutes completed is greater than the weekly goal, calculate the surplus and print a congratulatory success message praising their extra effort."

  



  

  
  



