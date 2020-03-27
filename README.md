# cgpa-grade

#include <iostream>

#include <iomanip>

#include <conio.h>

 

using namespace std;

 

int main()

{

    float cgpa;

    cout<<"Enter cgpa of the student"<<endl;

    cin>>cgpa;

    if(cgpa==5.0)

    {

        cout<<" O grade"<<endl;

    }

    else if(cgpa>=4.5&&cgpa<5.0)

    {

        cout<<" A grade"<<endl;

    }

    else if(cgpa>=4.0&&cgpa<4.5)

    {

        cout<<" B grade"<<endl;

    }

    else if(cgpa>=3.0&&cgpa<4.0)

    {

        cout<<"C grade"<<endl;

    }

    else if(cgpa>=2.0&&cgpa<3.0)

    {

        cout<<" D grade"<<endl;

    }

    else if(cgpa>=1.0&&cgpa<2.0)

    {

        cout<<" E grade"<<endl;

    }

    else if(cgpa>=0.0&&cgpa<1.0)

    {

        cout<<" F grade"<<endl;

    }

    else

    {

        cout<<"Student is Absent"<<endl;

    }

    getch();

    return 0;

}

 


 

