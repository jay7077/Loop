#include<iostream>
#include<string>
#include<cmath>
#include<cstdio>
#include<ctime>
using namespace std;
int main()
{
    //problem 1
    
     /*for (int i = 10; i > 0; i--)
    {cout << i << " ";}
    cout << endl;*/
    
    
    //problem 2
    /*string str;
    getline(cin,str);
    while (str.length() !=0)
    {cout << "Parrot Says: " << str << endl;
        getline(cin,str);
    }*/
     
    //problem 3
    /*string str;
    for(int i=99; i >0; i--)
    {
        cout << i << "bottles of the beer on the wall " << endl;
        cout << i << "bottled of the beer " << endl;
        cout << "Take one down,Pass it around " << endl;
    }*/
    
    //problem 4
    /*for(int i=0; pow(2,i) < 5000; i++)
    {
        cout << pow(2,i) << endl;
    }*/
    
    //problem 5
    //Print backwards all the positive even integers starting with 100.
    /*for (int i = 100; i >= 2; i-=2)
    {
        if(i%2==0)
        {
            cout << i << " ";
        }
        
        cout << endl;
    }*/
    
    //problem 6
    //Print the numbers 1 through 10 on one line, with a comma after
    //each except the last value, which should have a period after it.
    /*int maxNumber = 10; // Change this number to print a different range of numbers.
        
    for (int i = 1; i <= maxNumber; i++)
     {
        cout << i;
        if (i < maxNumber) {
            cout << ", ";
        } else {
            cout << ".";
            cout << endl;
        }
    }*/
    
    //problem 7
   /*int numbers;
    while(true)
    {
        cout << "Enter the integer between 1 to 10 " << endl;
        cin >> numbers;
        
        if(numbers <= 0 || numbers >= 11)
        {
            cout << "invalid input ";
        }
        else
        {
            break;
        }
    }*/
    
    //problem 8
    // Initialize random seed
       /*srand(time(NULL));

       // Generate a random number between 1 and 100
       int secretNumber = rand() % 100 + 1;

       int guess;
       do {
           // Ask the user to guess the number
           cout << "Guess a number between 1 and 100: ";
           cin >> guess;

           // Check if the guess is too high, too low, or correct
           if (guess > secretNumber) {
               cout << "Too high! Try again." << endl;
           } else if (guess < secretNumber) {
               cout << "Too low! Try again." << endl;
           } else {
               cout << "Congratulations, you guessed the number!" << endl;
           }

       }while (guess != secretNumber);
        */
    
    //problem 9
    
    /*char letter = 'a';
    cout << "Lowercase letters ASCII values:" << endl;
        for (int i = 0; i < 26; i++)
     {
           cout << letter << ": " << static_cast<int>(letter) << endl;
            letter++;
     }*/
    
    
    //problem 10
    
        /*string gifts[] = {"a partridge in a pear tree", "two turtle doves", "three French hens", "four calling birds", "five golden rings", "six geese a-laying", "seven swans a-swimming", "eight maids a-milking", "nine ladies dancing", "ten lords a-leaping", "eleven pipers piping", "twelve drummers drumming"};

        for (int day = 1; day <= 12; day++)
        {
            cout << "On the ";

            switch(day)
            {
                default:
                    cout << day << "th";
                    break;
            }

            cout << " day of Christmas, my true love gave to me: " << endl;

            switch(day) {
                case 12:
                    cout << "Twelve " << gifts[11] << ", " << endl;
                case 11:
                    cout << "Eleven " << gifts[10] << ", " << endl;
                case 10:
                    cout << "Ten " << gifts[9] << ", " << endl;
                case 9:
                    cout << "Nine " << gifts[8] << ", " << endl;
                case 8:
                    cout << "Eight " << gifts[7] << ", " << endl;
                case 7:
                    cout << "Seven " << gifts[6] << ", " << endl;
                case 6:
                    cout << "Six " << gifts[5] << ", " << endl;
                case 5:
                    cout << "Five " << gifts[4] << ", " << endl;
                case 4:
                    cout << "Four " << gifts[3] << ", " << endl;
                case 3:
                    cout << "Three " << gifts[2] << ", " << endl;
                case 2:
                    cout << "Two " << gifts[1] << ", and " << endl;
                case 1:
                    cout << "a " << gifts[0] << ". " << endl;
                    break;
            }

            cout << endl;
        }*/
    
    //problem 11
    /*int low = 1, high = 100;
    int guess, numGuesses = 0;

    cout << "Think of a number between 1 and 100, and I will try to guess it." << endl;

    while (low <= high) {
        guess = (low + high) / 2;
        numGuesses++;

        cout << "Is your number " << guess << "? (Enter 'h' if it's too high, 'l' if it's too low, or 'c' if it's correct)" << endl;
        char response;
        cin >> response;

        if (response == 'c') {
            cout << "I guessed your number in " << numGuesses << " guesses!" << endl;
            break;
        }
        else if (response == 'h') {
            high = guess - 1;
        }
        else if (response == 'l') {
            low = guess + 1;
        }
        else {
            cout << "Invalid response. Please enter 'h', 'l', or 'c'." << endl;
        }
    }*/
    
    


    



    
    return 0;
}
