# Quiz-Game
//C code for a Quiz game

#include <stdio.h>

#include<stdio.h>    
int main()
{
 int i,a,count=0;
 char name[200];
 printf("\t\t\t\t -: ENTER A NUMBER :- \n\n");
 printf("\t\t\t \n 1. START THE QUIZ : \t\t\t \n 0. QUIT THE QUIZ : \t\t\n ");
 scanf(" %d",&i);
 switch (i)
 { 
 
     case 1:
  
   printf(" \n \t\t\t ENTER YOUR NAME   ");
   scanf(" %s",&name);
   printf("\n\t\t\t PLAYER NAME IS %s",name);
   printf("\n\n\t\t\t [ SELECT AND ENTER THE ANSWER NO. ]");
   printf("\n\n\t\t\t [ LEVEL 1 : Easy ]");
   printf("\n\n\t\t Q1.WHAT IS THE CAPITAL OF THE INDIA ?\n");
   printf(" \n\t\t 1. DELHI\n\t\t 2. MUMBAI\n\t\t 3. Punjab\n\t\t 4. Gujrat \n\t\t");
   printf("ENTER THE ANS NO.");
   scanf("\t%d",&a);
   if (a==1)
   {
    printf(" \n\t\t COREECT !!!");
    count+=1;
   }
   else if (a==2)
    printf("\n\t\t WRONG !!!");
   else if (a==3)
    printf("\n\t\t WRONG !!!");
   else if (a==4)
    printf("\n\t\t WRONG !!!");
   else 
    printf("\n\t\t INVALID !!! ");
    
   printf("\n\n\t\t Q2.WHO IS THE PRIME MINISTER OF THE INDIA ?\n");
   printf(" \n\t\t 1. SONIYA GANDHI\n\t\t 2. NARENDRA MODI\n\t\t 3. RAHUL GANDHI\n\t\t 4. AMIT SHAH\n\t\t");
   printf("ENTER THE ANS NO.");
   scanf("\t%d",&a);
   if (a==1)
    printf(" \n\t\t WRONG !!!");
   else if (a==2)
   {
    printf("\n\t\t CORRECT !!!");
    count+=1;
   }
   else if (a==3)
    printf("\n\t\t WRONG !!!");
   else if (a==4)
    printf("\n\t\t WRONG !!!");
   else 
    printf("\n\t\t INVALID !!! ");
    
   printf("\n\n\t\t\t [ LEVEL 2 : MEDIUM ]");
   
   printf("\n\n\t\t Q3.WHO IS THE DEFENCE MINISTER OF THE INDIA ?\n");
   printf(" \n\t\t 1. SONIYA GANDHI\n\t\t 2. NIRMALA SITHARAMAN\n\t\t 3. RAJNATH SINGH\n\t\t 4. AMIT SHAH\n\t\t");
   printf("ENTER THE ANS NO.");
   scanf("\t%d",&a);
   if (a==1)
    printf(" \n\t\t WRONG !!!");
   else if (a==2)
    printf("\n\t\t WRONG !!!");
   else if (a==3)
   {
    printf("\n\t\t CORRECT !!!");
    count+=1;
   }
   else if (a==4)
    printf("\n\t\t WRONG !!!");
   else 
    printf("\n\t\t INVALID !!! ");
    
    printf("\n\n\t\t Q4.WHO IS THE FINANCE MINISTER OF THE INDIA ?\n");
   printf(" \n\t\t 1. SMRITI IRANI\n\t\t 2. NIRMALA SITHARAMAN\n\t\t 3. SONIYA GANDHI\n\t\t 4. S.JAISHANKAR\n\t\t");
   printf("ENTER THE ANS NO.");
   scanf("\t%d",&a);
   if (a==1)
    printf(" \n\t\t WRONG !!!");
   else if (a==2)
   {
    printf("\n\t\t CORRECT !!!");
    count+=1;
   }
   else if (a==3)
    printf("\n\t\t WRONG !!!");
   else if (a==4)
    printf("\n\t\t WRONG !!!");
   else 
    printf("\n\t\t INVALID !!! ");
    
   printf("\n\n\t\t\t [ LEVEL 3 : HARD ]");
   
   printf("\n\n\t\t Q5.WHO WAS THE FIRST INDIAN WOMAN TO WIN THE MISS WORLD TITLE ?\n");
   printf("\n\t\t 1. AISHWARYA RAI\n\t\t 2. SUSHMITA SHEN\n\t\t 3. REITA FARIA\n\t\t 4. DIYA MIRZA\n\t\t");
   printf("ENTER THE ANS NO.");
   scanf("\t%d",&a);
   if (a==1)
    printf(" \n\t\t WRONG !!!");
   else if (a==2)
    printf("\n\t\t WRONG !!!");
   else if (a==3)
   {
    printf("\n\t\t CORRECT !!!");
    count+=1;
   }
   else if (a==4)
    printf("\n\t\t WRONG !!!");
   else 
    printf("\n\t\t INVALID !!! ");
    
   
     case 0:
     break;
     default :
      printf("\n\n\t\t\t invalid input !!!!");
      break;
    }
    //count
    printf("\n\n****** FINAL REPORT *******");
        if (count==0)
    printf(" \n\t\t VERY POOR!!!");
    else if (count==1)
    printf(" \n\t\t POOR!!!");
   else if (count==2)
    printf("\n\t\t BAD !!!");
   else if (count==3)
    printf("\n\t\t GOOD !!!");
   else if (count==4)
    printf("\n\t\t STRONG !!!");
   else 
    printf("\n\t\t VERY STRONG !!! ");
 return 0;    }

