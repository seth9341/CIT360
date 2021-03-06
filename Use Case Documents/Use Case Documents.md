# Use Case Documents


<!-- ## Template

| 	| 	|
| --	| --	|
| Name:	| Use case name	|
| Summary:	| A high level description of use case	|
| Version:	| 1.1 (Current revision number)	|
| Preconditions:	| 1. Defines all the conditions that must be true (i.e., describes the state of the system) for the trigger to be active.	|
| Triggers:	| Describes the event that causes the use case to be initiated	|
| Main Success Scenario:	| 1. Outline of steps for normal scenario (System displays “”, User enters “”, etc.) <br> 2. … <br> 3. …	|
| Alternative Success Scenarios:	| 1. Outline steps for alternative scenario 1 <br> 1.1.… <br> <br> 1.2.… <br> 2. Outline steps for alternative scenario 2 <br> 2.1.… <br> 2.2.…
| Postconditions:	| 1. Describes what the change in state of the system will be after the use case completes	|
| Business Rules:	| 1. List items to be validated and other business rules that need to be enforced <br> 2. … <br> 3. …	|
| Notes:	| 1. Additional items that needed to clarified or special considerations	|
| Author:	| Authors Name|
| Date:	| Current Date 	| -->

***


| 	| 	|
| --	| --	|
| Name:	| Addition use case	|
| Summary:	| a use case to test the addition function of the calculator app	|
| Version:	| 1.0	|
| Preconditions:	| (a) Two positive integers. <br> (b) addition "+" operand 	|
| Triggers:	| Run the application and input a positive integer followed by the addition "+" operand and a second positive integer	|
| Main Success Scenario:	| 1. System displays "What's the first number you'd like to calculate? " <br> 2. User inputs first positive integer <br> 3. System displays "How would you like to calculate it? (+, -, /, or *): " <br> 4. User inputs addition "+" operand <br> 5. System displays "What's your second number?" <br> 6. User inputs second positive integer <br> 7. System displays first value e.g. 13 + second value e.g. 3 = answer e.g. 16	|
| Alternative Success Scenarios:	| 1. User chooses different values <br> 2. User completes math problem as above <br> 3. User receives correct answer.	|
| Postconditions:	| 1. No change is system state. <br> 2. System is unaffected by successful application operation. <br> 3. No data is written to system	|
| Business Rules:	| 1. No negative numbers <br> 2. No decimals or fractions, integers only. <br> 3. Must use "+" from keyboard and not "➕" symbol	|
| Notes:	| Be aware the results of division will be rounded to nearest integer	|
| Author:	| Seth Huntley|
| Date:	| 2019.03.26 	|

