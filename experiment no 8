# include<iostream>
using namespace std;

class college
{
    public:

    int age;
    string name;
    int contact;

    void display()
    {
        cout<<"AGE OF THE STUDENT IS:"<<age<<endl;
        cout<<"NAME OF THE STUDENT IS :"<<name<<endl;
        cout<<"CONTACT OF THE STUDENT IS:"<<contact<<endl;
    }
};

class student:public college
{
    public:
         int rollno;
         string branch;

         void show()
         {
            cout<<"ROLLNO OF THE STUDENT IS:"<<rollno<<endl;
            cout<<"BRANCH OF THE STUDENT IS:"<<branch<<endl;


         }

};

int main()
{
    student S1;
    student S2;
   

    cout<<"INFORMATION OF THE STUDENT"<<endl;

    S1.age=15;
    S1.name="harsh";
    S1.contact=1458784;
    S1.rollno=145;
    S1.branch="AIML";

    S1.display();
    S1.show();

    cout<<"              "<<endl;

    S2.age=27;
    S2.name="VIRAT";
    S2.contact=8695879;
    S2.rollno=23;
    S2.branch="AIDS";

    S2.display();
    S2.show();

    return 0;
}
