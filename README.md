//how-to-check-if-you-are-eligible-to-vote
//this program takes user input as age and checks if the user is eligible to vote or not.
#include<iostream>
#include<conio.h>
using namespace std;
int main()
{    
    int age;
    cout<<"Hello,The right to vote is the fundamental right of every citizen.\nTo be able to cast a vote is a precious power and should not be wasted.\nYou will be able to check if you are eligible to vote or not.\nEnter your present age (in years):";
    cin>>age;
    if(age>=18){
        cout<<"You are eligible to vote.\nVote rightly!!!!\n";
    }
    else{
        cout<<"You are not eligible to vote.\nPlease wait for some more time i.e."<<18-age<<"year(s)\n";
    }

    
    cout<<"Thank You\n";
    getch();
    return 0;
    
}
