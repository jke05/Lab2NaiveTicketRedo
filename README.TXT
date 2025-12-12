Part II: naive-ticket-machine project

2. 0

3. You can't put more than 10000000000
   Theres no refund
   The ticket still prints when you click printTicket
   
5. The only thing changed is the price payed

6. public class Student  and  public class LabClass

7. The class becomes red

8. you cannot

10. fields: price, balance, total
    constructors: TicketMachine
    methods: getPrice, getBalance, insertMoney, printTicket
    
11. The constructor has no return type and is called upon creation

12. int, Student, Server

13. alive, tutor, game

14. Student, Server, Person, Game

15. the order matters, there will always be an error and the class will turn red when closing
the editor if the order of the three words in the field declaration changes

16. it is important to add a semi colon at the end of a field declaration or else it will ask
you to put it

17. private int status;

18. it belongs to the Student class

19. 2 paremeters, String and double

20. some fields in a Book class could be: title, chapters, pages, etc

21. public Pet(String petsName){
    this.petsName = petsName;
}

22. public Date(String month, int day, int year){
    
}

23. getBalance has a return type and getPrice has no return type

24. "How much money do I have?"

25. No the return statement does not need to be changed. The code could have whatever name
even if the meaning is completely different from what the code does.

27. public int getTotal(){
        return total;
    }
    
28. getPrice has a return type and returns the price (int)
    printTicket does not have a return type and prints out lines
    
29. no they do not, because the methods are of type void and they perform actions, not return a 
value

31. public void increaseScore(int points){
    score = score + points;
}

32. Yes addCredits is a mutator. If I wanted to use it with a Student object name student, it 
would be like this:
student.addCredits(5); // credits could be whatever int value you'd like

33. public void discount(int amount){
        price = price - amount;
    }
    
34. public void setAge(int age){
        this.age = age;
    }
    
35. public void isAlive(boolean alive){
        this.alive = alive;
    }
    
36. price = 0

37. "My cat has green eyes."

38. public void prompt(){
        System.out.println("Please insert the correct amount of money");
    }
    
39. "# price cents."

40. same thing as 39

41. public void showPrice(){
        System.out.println("The price of a ticket is " + price + " cents."); 
    }
    
42. they don't show the same output because the value of price is
different in both objects

43. It prints the same thing as the println statement and I have no clue why

44. If I take out the parameter of the constructor and set the price at 1000 cents,
the price of a ticket will be 1000 tickets for any object that will
be created from the TicketMachine class.

45. public TicketMachine(int cost)
    {
        price = cost;
        balance = 0;
        total = 0;
    }
    
    public TicketMachine(){
        price = 1000;
        balance = 0;
        total = 0;
    }
    
46. public void empty(){
        total = 0;
    }
    mutator