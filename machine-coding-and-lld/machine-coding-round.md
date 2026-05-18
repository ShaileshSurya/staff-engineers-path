### Machine coding round

Why take machine coding round?
> Machine coding round exists to prove you can actually build systems, not just talk about them. 

DSA is to test your problem solving skills, LLD is to check your design skills where as machine coding round is to check whether you can turn what you say in clean working code. 

Understand -> Can you do what you speak. 

You can say, hey lets use this awesome-design pattern. The machine coding interviewer asks okay implement it. 

This is basically to check how you write your code. Skills that will be assesed here. 

1. Problem understanding and & Requirement gathering
What to asses:- Do you clarify things before jumping into code. 

Template
	1. Restate the problem :- This step is to speak out your version of the problem and how you understand it. 

	It can go soemthing like this
		"So from my understanding we want to build a parking lot system, where vehicle can be parked, unparked and we track available slots" 

	2. Identify core functionalities
		- parking?
		- unparking()
		- availableSlots()
	3. clarify boundaries

	4. Identify entities

	5. Clarify edge cases & constraints if any | You can define/clarify your boundaries here

	6. Understand the actors in the system. You can focus on the primary actor but say explicitely that the admin/second actor is preconfigured
	  Now understand that the parking slot there will be an admin's case as well. Where some task has to be done by admin. You can explicitely say that the admin things are preconfigured.
	"For example the parking slots are preconfigured, in case interviewer asks for that you can extend your system"


	7. Make sure that when you define your functional usecase, it tells a complete story. There are two guys in the story, the primary actor and the system. 	For eg. 
		Parking System
			customer Comes to parking area -> customer parks vehicle system reseves the parking slot -> system generate ticket ->  customer unparks the vehicle using ticket -> system calculates fare -> system opens the slot  
