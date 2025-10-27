import java.util.ArrayList;

class Account {
private String name ;
private dount balance;
private ArrayList<string>history;

pubilc Account (String name ,double balance){
this.name = name ;
this.balance = balance;
this.history= new ArrayList<>();
}
public void deposit(double amount){
balance += amount;
history.add("Deposited" + amount);
}
public void withdram(double amount){
if (amount > balance){
System.out.println("Insfficient funds!");
}else {
balance -=amount;
history.add("Withdeam" + amount);
}
}
