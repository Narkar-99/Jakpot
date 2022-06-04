# Jakpot
//HELLO! There I am just a student who is seeking for knowledge, nothing else 😗
#include<stdio.h>

int main()

{ int pin,n;

// put your own balance

float balance=100000.00,draw;

    printf("\t\tWelcome to ATM");

 

 { A :printf("\n\npress 1:Cash widrwal\npress 2:check balance\npress 0:Exit\t"); 

   scanf("%d",&n);

   printf("Enter your pin:");

scanf("%d",&pin);

// change pin by changing value of pin below

if(pin==9211)

{ if(n==1)

  {printf("\nEnter amount to withdraw:");

B: scanf("%f",&draw);

balance-=draw;

if(balance<=0) { balance=100000.00;

printf("\nNot enough balance!!");

printf("\nEnter less amount:"); goto B;}

else 

  printf("\nNew balance is %.2f ", balance);}

else if(n==2)

{ printf("\nYour balance is 100000.00", balance);

}

 else if(n==0)

goto C;

}

 

else printf("\nIncoreect password!");

goto A;

C: printf("\nThank you for visiting!");}

    return 0;

}
