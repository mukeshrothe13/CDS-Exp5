
## Aim
To understand and implement `if` statements and `switch` statements in C++.

## Software Used
- VS Code

## Problem Statements

1. **Grade Evaluator**
   - Write a C++ program to evaluate and display grades based on user input.

2. **Leap Year Checker**
   - Write a C++ program to determine if a given year is a leap year.

3. **Password Validator**
   - Write a C++ program to validate a user’s password based on specified criteria.

4. **Simple Calculator**
   - Write a C++ program to create a basic calculator that performs arithmetic operations.
   - 
5. **Days of the Week**
   - Write a C++ program to print the days of the week based on user input.

## Theory

- **`if` Statement**: Used to execute a block of code if a specified condition is true.
- **`else` Statement**: Executes a block of code if the condition in the `if` statement is false.
- **`else if` Statement**: Tests a new condition if the previous `if` condition is false.
- **`switch` Statement**: Allows the execution of different blocks of code based on the value of an expression. It can have multiple `case` labels for different values and only supports `int` or `char` types for the expression.

# Program Codes

```javascript
//Mukesh Rothe  //23070123089  //EXP5
#include <iostream>
using namespace std;
int main()
{
  int s;
  cout<< "Enter your score";
  cin>>s;
  if(s>=90)
  {
    cout<<"Your grade is A"<<endl;
    cout<< "You are passed"<<endl;
  }
  else if(s>=80)
  {
    cout<<"Your grade is B"<<endl;
    cout<< "You are passed"<<endl;
  }
  else if(s>=70)
  {
    cout<<"Your grade is C"<<endl;
    cout<< "You are passed"<<endl;
  }
  else if(s>=60)
  {
    cout<<"Your grade is D"<<endl;
    cout<< "You are passed"<<endl;
  }
  else if( s>=50)
  {
    cout<<"Your grade is E"<<endl;
    cout<< "You are passed"<<endl;
  }
  else
  { cout<< "Failed";
  }
  return 0;
}

//Mukesh Rothe  //23070123089  //EXP5
#include<iostream>
using namespace std;
int main()
{
    int year;
    cout<<"Enter a year"<<endl;
    cin>>year;
    if(cin.fail())
    {
        cout<<"Invalid input";
    }
    else 
    {
        if((year%4==0 && year%100!=0) || (year%400==0))
        {
        cout<<year<<" is a leap year";
        }
        else 
        {
        cout<<year<<" is not a leap year";
        }
    }
    return 0;
}

//Mukesh Rothe  //23070123089  //EXP5
#include<iostream>
using namespace std;
int main()
{
   string password;
   cout << "Enter the password: ";
   cin >> password;
   if (password == "secret")
   {
    cout << "Access Granted ";
   }
   else
   { 
    cout<< "Access Denied";
   }
   return 0;
}

//Mukesh Rothe  //23070123089  //EXP5
#include<iostream>
using namespace std;
int main()
{
    float a,b,c ;

    int choice;
    cout << "Calculator"<<endl;
    cout << "1: Addition"<<endl;
    cout << "2: Subtraction"<<endl;
    cout << "3: Multiplication"<<endl;
    cout << "4: Division"<<endl;
    cout<<"Enter operation choice: ";
    cin>>choice;
switch(choice)
{
    case 1 :
    { float c;
    cout<<"Enter numbers: ";
    cin>>a>>b;
    c=a+b;
    cout<<"Sum is = "<<c;
    } 
    break;
    case 2 :
    {
        float c;
    cout<<"Enter numbers: ";
    cin>>a>>b;
    c=a-b;
    cout<<"Difference is = "<<c;
    }
    break;
case 3 :
{ float c;
    cout<<"Enter numbers: ";
    cin>>a>>b;
    c=a*b;
    cout<<"Product is = "<<c;
}
break;
case 4 :

{ float c;
   cout<<"Enter numbers: ";
    cin>>a>>b;
    c=a/b;
    cout<<"Quotient is = "<<c;
    }
    break ;
}
return 0;
}

//Mukesh Rothe  //23070123089  //EXP5
#include<iostream>
using namespace std;
int main()
{
    int a,b,c, choice ;
    cout << "DAY"<<endl;
    cout << "1: Monday"<<endl;
    cout << "2: Tuesday"<<endl;
    cout << "3: Wednesday"<<endl;
    cout << "4: Thursday"<<endl;
    cout << "5: Friday"<<endl;
    cout << "6: Saturday"<<endl;
    cout << "7: Sunday"<<endl;
    cout<<"Enter of day: ";
    cin>>choice;
switch(choice)
{
{ case 1 :
cout<< "Day is Monday";
}
break ;
{ case 2 :
cout<< "Day is Tuesday";
}
break ;
{ case 3 :
cout<< "Day is Wednesday";
}
break ;{ case 4 :
cout<< "Day is Thursday";
}
break ;
{ case 5 :
cout<< "Day is Friday";
}
break ;
{
 case 6 :
cout<< "Day is Saturday";
}
break ;
{ case 7 :
cout<< "Day is Sunday";
}
}
}

```

# Output:
Grades-

![Screenshot 2024-08-22 213301](https://github.com/user-attachments/assets/0da7ab7a-f754-4a90-9bcc-aa5ffa774d77)

Leap Year-

![Screenshot 2024-08-22 213626](https://github.com/user-attachments/assets/d392d15a-3169-4ff5-83c4-be262cfd21f2)

Password-

![Screenshot 2024-08-22 213631](https://github.com/user-attachments/assets/ebb67137-6d64-406f-96f2-9e7c20e4ef74)

Calculator-

![Screenshot 2024-08-22 213831](https://github.com/user-attachments/assets/b53ef4b8-bc2a-4dd0-88a6-9ad7394e4a32)

Week- 

![Screenshot 2024-08-22 214009](https://github.com/user-attachments/assets/3aa90a21-bc97-4c63-b063-158613d786cb)


## Conclusion

- We learned to use `if` statements and `switch` statements effectively in C++.
