# write-a-java-program-for-a-simple-bank-account-solved
**TO GET THIS SOLUTION VISIT:** [Write a Java program for a simple bank account Solved](https://www.ankitcodinghub.com/product/write-a-java-program-for-a-simple-bank-account-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;5548&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Write a Java program for a simple bank account Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<p class="ui header product-top-header" title="Write a Java program for a simple bank account Solution">You&nbsp;shall&nbsp;define a&nbsp;Customer&nbsp;class. A customer has a first name, last name, and social security number.&nbsp;The social security number is a String variable and must comply with this format: xxx-xx-xxxx where ‘x’ is a digit between 0-9. If a customer is supplied an invalid ssn, a message must be printed that the SSN of the customer is invalid; however, it will create the bank account regardless.

You&nbsp;shall&nbsp;define a&nbsp;BankAccount&nbsp;class. A BankAccount&nbsp;has a customer, account number, and a balance.&nbsp;A bank account can be opened with any amount of initial deposit.&nbsp;For each bank account, a 10 digit random account number must be created.&nbsp;Bank account&nbsp;shall&nbsp;define&nbsp;the following methods:&nbsp;deposit,&nbsp;withdraw.&nbsp;applyInterest,&nbsp;and&nbsp;checkBalance.

Every time there is a deposit or withdrawal, the amount and current balance should be displayed. One cannot withdraw more than the funds available in the account.

You&nbsp;shall&nbsp;define two types&nbsp;of bank accounts:&nbsp;Checking Account&nbsp;and&nbsp;Saving Account.&nbsp;Each account accrues interest.&nbsp;A saving account accrues 5% fixed interest and a checking account accrues 2% for any amount in excess of $10000 (For example, if there is $11000 in the checking account, the interest is only applied to $1000).

You&nbsp;shall&nbsp;define the&nbsp;BankMain&nbsp;class that defines the main method.&nbsp;You can use the “main” method shown below to test your application. The expected output is also provided.

public class BankMain {

public static void main(String[] args) {

CheckingAccount acct1 = new CheckingAccount(“Alin”, “Parker”, “123-45-6789”, 1000.0f);

CheckingAccount acct2 = new CheckingAccount(“Mary”, “Jones”, “987-65-4321”, 500.0f);

SavingAccount acct3 = new SavingAccount(“John”, “Smith”, “1233-45-6789”, 200.0f);

acct1.deposit(22000.00f);

acct2.deposit(12000.00f);

acct1.withdraw(2000.00f);

acct2.withdraw(1000.00f);

acct1.applyInterest();

acct2.applyInterest();

acct1.checkBalance();

acct2.checkBalance();

acct1.withdraw(30000.00f);

}

}

=================== This is the expected output =======================

Successfully created account for Alin Parker Account Number 3364673506

Alin Parker, Balance $1000.0

Successfully created account for Mary Jones Account Number 6221275878

Mary Jones, Balance $500.0

Successfully created account for John Smith. Inavlid SSN!

Successfully created account for John Smith Account Number 7091028094

John Smith, Balance $200.0

Alin Parker deposited $22000.0. Current balance 23000.0

Mary Jones deposited $12000.0. Current balance 12500.0

Alin Parker withdrew $2000.0. Current balance 21000.0

Mary Jones withdrew $1000.0. Current balance 11500.0

Alin Parker, Balance $21220.0

Mary Jones, Balance $11530.0

Unable to withdraw 30000.0 for Alin Parker due to insufficient funds

<div class="ui divider"></div>
<div class="ui nopad middle aligned grid product-share"></div>
