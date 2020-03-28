public class SavingsAccount {
  
  int balance;
  
  public String toString(){
    System.out.println("This is a savings account!");
    return "This is a savings account";
    
  }
  public SavingsAccount(int initialBalance){
    balance = initialBalance;
  }
  public void checkBalance(){
    System.out.println("Hello!");
    System.out.println("Your balance is "+balance);
  }
  public void deposit(int amountToDeposit){
    int updatedBalance=balance+amountToDeposit;
    balance=updatedBalance;
    System.out.println("You just deposited "+amountToDeposit);
  }
  public int withdraw(int amountToWithdraw){
    int updatedBalance=balance-amountToWithdraw;
    balance=updatedBalance;
    System.out.println("You just withdrew "+amountToWithdraw);
     return amountToWithdraw;
  }
  public static void main(String[] args){
    SavingsAccount savings = new SavingsAccount(2000);
    
    //Check balance:
    savings.checkBalance();
    
    //Withdrawing:
    savings.withdraw(300);
    
    //Check balance:
  savings.checkBalance();
    
    //Deposit:
savings.deposit(600);
    
    //Check balance:
savings.checkBalance();
    
    //Deposit:
savings.deposit(600);
    
    //Check balance:
    savings.checkBalance();
    
savings.toString();
