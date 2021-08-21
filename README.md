# Navigus-Project
In the following assignment, we are going to build an adaptive learning platform, leveraging gamification to engage users. There are two types of user roles in this application: ● Teachers ● Students A teacher is supposed to add, remove, edit, and delete courses. For each course, they will be able to create one quiz only, based on a set of questions and their respective answers (Choice-based Questions only). Teachers should also be able to add/edit/delete questions and answers to a quiz for a course
NAVIGUS PROJECT(QUIZ)


#include<iostream>

#include<conio.h>

#include<cstdlib>

#include<windows.h>

using namespace std;

struct student{

	char nam[20],rollno[20];

	int marks,random;

};

student st;

void cppp(){

	int i=0,arr[6];

	st.marks=0;

	char choice;

	while(i<5){

	back:	

	st.random=rand()%6;

	for(int j=0;j<=6;j++){

		if(st.random==arr[j]){

			goto back;

		}

	}

	arr[i]=st.random;

	switch(st.random)

    {

    case 0:

	cout<<i+1<<") What is a correct syntax to output \"Hello World\" in C++?"<<endl;

	cout<<"A. System.out.println(\"Hello world\");"<<endl;

	cout<<"B. Console.WriteLine(\"Hello world\");"<<endl;

	cout<<"C. print(\"Hello world\");"<<endl;

	cout<<"D. cout<<\"Hello world\";"<<endl;

	choice=getch();

	if(choice=='D'||choice=='d'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is d"<<endl<<endl;

	}

	break;

	case 1:

	cout<<i+1<<") Which of the following is called address operator?"<<endl;

	cout<<"a) *"<<endl;

	cout<<"b) &"<<endl;

	cout<<"c) _"<<endl;

	cout<<"d) %"<<endl;

	choice=getch();

	if(choice=='B'||choice=='b'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is b"<<endl<<endl;

	}

	break;

	case 2:

	cout<<i+1<<") Which of the following is used for comments in C++?"<<endl;

	cout<<"a) // comment"<<endl;

	cout<<"b) /* comment */"<<endl;

	cout<<"c) both // comment or /* comment */"<<endl;

	cout<<"d) // comment */"<<endl;

	choice=getch();

	if(choice=='c'||choice=='C'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is c"<<endl<<endl;

	}

	break;

	case 3:

	cout<<i+1<<") Who created C++?"<<endl;

	cout<<"a) Bjarne Stroustrup"<<endl;

	cout<<"b) Dennis Ritchie"<<endl;

	cout<<"c) Ken Thompson"<<endl;

	cout<<"d) Brian Kernighan"<<endl;

	choice=getch();

	if(choice=='A'||choice=='a'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is a"<<endl<<endl;

	}

	break;

	case 4:

	cout<<i+1<<")  A language which has the capability to generate new data types are called"<<endl;

	cout<<"a) Extensible"<<endl;

	cout<<"b) Overloaded"<<endl;

	cout<<"c) Encapsulated"<<endl;

	cout<<"d) Reprehensible"<<endl;

	choice=getch();

	if(choice=='A'||choice=='a'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is a"<<endl<<endl;

	}

	break;

	case 5:

	cout<<i+1<<") Which of the following is called insertion/put to operator?"<<endl;

	cout<<"a) <"<<endl;

	cout<<"b) >"<<endl;

	cout<<"c) <<"<<endl;

	cout<<"d) >>"<<endl;

	choice=getch();

	if(choice=='c'||choice=='C'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl<<endl;

		cout<<"The corrent answer is c"<<endl;

	}

	break;

	case 6:

	cout<<i+1<<") Which of the following is called extraction/get from operator?"<<endl;

	cout<<"a) <"<<endl;

	cout<<"b) >"<<endl;

	cout<<"c) <<"<<endl;

	cout<<"d) >>"<<endl;

	choice=getch();

	if(choice=='d'||choice=='D'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is d"<<endl<<endl;

	}

	break;

    }

    i++;

    

}

	

}

void java(){

int i=0,arr[6];

	st.marks=0;

	char choice;

	while(i<5){

	back:	

	st.random=rand()%6;

	for(int j=0;j<=6;j++){

		if(st.random==arr[j]){

			goto back;

		}

	}

	arr[i]=st.random;

	switch(st.random)

    {

    case 0:

	cout<<i+1<<") What is polymorphism?"<<endl;

	cout<<"A. Polymorphism is a technique to define different objects of same type."<<endl;

	cout<<"B. Polymorphism is the ability of an object to take on many forms."<<endl;

	cout<<"C. Polymorphism is a technique to define different methods of same type."<<endl;

	cout<<"D. None of the above."<<endl;

	choice=getch();

	if(choice=='B'||choice=='b'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is b"<<endl<<endl;

	}

	break;

	case 1:

	cout<<i+1<<") Which is a reserved word in the Java programming language?"<<endl;

	cout<<"a) method"<<endl;

	cout<<"b) naive"<<endl;

	cout<<"c) subclasses"<<endl;

	cout<<"d) reference"<<endl;

	choice=getch();

	if(choice=='B'||choice=='b'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is b"<<endl<<endl;

	}

	break;

	case 2:

	cout<<i+1<<") Which is a valid keyword in java?"<<endl;

	cout<<"a) interface"<<endl;

	cout<<"b) string"<<endl;

	cout<<"c) Float"<<endl;

	cout<<"d) unsigned"<<endl;

	choice=getch();

	if(choice=='a'||choice=='A'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is a"<<endl<<endl;

	}

	break;

	case 3:

	cout<<i+1<<") You want subclasses in any package to have access to members of a superclass. Which is the most restrictive access that accomplishes this objective?"<<endl;

	cout<<"a) public"<<endl;

	cout<<"b) private"<<endl;

	cout<<"c) protected"<<endl;

	cout<<"d) transient"<<endl;

	choice=getch();

	if(choice=='C'||choice=='c'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is c"<<endl<<endl;

	}

	break;

	case 4:

	cout<<i+1<<") Which of the following class level (nonlocal) variable declarations will not compile?"<<endl;

	cout<<"a) protected int a;"<<endl;

	cout<<"b) transient int b = 3;"<<endl;

	cout<<"c) volatile int d ;"<<endl;

	cout<<"d) private synchronized int e;"<<endl;

	choice=getch();

	if(choice=='D'||choice=='d'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is d"<<endl<<endl;

	}

	break;

	case 5:

	cout<<i+1<<") Which of the following would compile without error?"<<endl;

	cout<<"a) int a = Math.abs(-5);"<<endl;

	cout<<"b) int b = Math.abs(5.0);"<<endl;

	cout<<"c) int c = Math.abs(5.5F);"<<endl;

	cout<<"d) int d = Math.abs(5L);"<<endl;

	choice=getch();

	if(choice=='a'||choice=='A'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl<<endl;

		cout<<"The corrent answer is a"<<endl;

	}

	break;

	case 6:

	cout<<i+1<<") Which interface does java.util.Hashtable implement?"<<endl;

	cout<<"a) Java.util.Map"<<endl;

	cout<<"b) Java.util.List"<<endl;

	cout<<"c) Java.util.HashTable"<<endl;

	cout<<"d) Java.util.Collection"<<endl;

	choice=getch();

	if(choice=='a'||choice=='A'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		

cout<<"The corrent answer is a"<<endl<<endl;

	}

	break;

    }

    i++;

    

}
	
}

void dbms(){

	int i=0,arr[6];

	st.marks=0;

	char choice;

	while(i<5){

	back:	

	st.random=rand()%6;

	for(int j=0;j<=6;j++){

		if(st.random==arr[j]){

			goto back;

		}

	}

	arr[i]=st.random;

	switch(st.random)

    {

    case 0:

	cout<<i+1<<") Which of the following is generally used for performing tasks like creating the structure of the relations, deleting relation?"<<endl;

	cout<<"A. DML(Data Manipulation Language)"<<endl;

	cout<<"B. Query"<<endl;

	cout<<"C. Relational Schema"<<endl;

	cout<<"D. DDL(Data Definition Language)"<<endl;


	choice=getch();

	if(choice=='D'||choice=='d'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is d"<<endl<<endl;

	}

	break;

	case 1:

	cout<<i+1<<") Which one of the following given statements possibly contains the error?"<<endl;

	cout<<"a) select * from emp where empid = 10003;"<<endl;

	cout<<"b) select empid from emp where empid = 10006;"<<endl;

	cout<<"c) select empid from emp;"<<endl;

	cout<<"d) select empid where empid = 1009 and Lastname = 'GELLER';"<<endl;

	choice=getch();

	if(choice=='D'||choice=='d'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is d"<<endl<<endl;

	}

	break;

	case 2:

	cout<<i+1<<") What do you mean by one to many relationships?"<<endl;

	cout<<"a) One class may have many teachers"<<endl;



	cout<<"b) One teacher can have many classes"<<endl;

	cout<<"c) Many classes may have many teachers"<<endl;

	cout<<"d) Many teachers may have many classes"<<endl;

	choice=getch();

	if(choice=='b'||choice=='B'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is b"<<endl<<endl;

	}

	break;

	case 3:

	cout<<i+1<<") A Database Management System is a type of _________software."<<endl;

	cout<<"a) It is a type of system software"<<endl;

	cout<<"b) It is a kind of application software"<<endl;

	cout<<"c) It is a kind of general software"<<endl;

	cout<<"d) Both A and C"<<endl;

	choice=getch();

	if(choice=='A'||choice=='a'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is a"<<endl<<endl;

	}

	break;

	
case 4:

	cout<<i+1<<")  Which of the following can be used to extract or filter the data & information from the data warehouse?"<<endl;

	cout<<"a) Data redundancy"<<endl;

	cout<<"b) Data recovery tool"<<endl;

	cout<<"c) Data mining"<<endl;

	cout<<"d) Both B and C"<<endl;

	choice=getch();

	if(choice=='c'||choice=='A'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is c"<<endl<<endl;

	}

	break;

	case 5:

	cout<<i+1<<") In general, a file is basically a collection of all related______."<<endl;

	cout<<"a) Rows & Columns"<<endl;

	cout<<"b) Fields"<<endl;

	cout<<"c) Database"<<endl;

	cout<<"d) Records"<<endl;

	choice=getch();

	if(choice=='d'||choice=='D'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl<<endl;

		
cout<<"The corrent answer is d"<<endl;

	}

	break;

	case 6:

	cout<<i+1<<") Which one of the following is a type of Data Manipulation Command?"<<endl;

	cout<<"a) Create"<<endl;

	cout<<"b) Alter"<<endl;

	cout<<"c) Delete"<<endl;

	cout<<"d) All of these"<<endl;

	choice=getch();

	if(choice=='c'||choice=='C'){

		cout<<choice<<" is correct Answer"<<endl<<endl;

		st.marks++;

	}

	else{

		cout<<choice<<" is incorrect Answer"<<endl;

		cout<<"The corrent answer is c"<<endl<<endl;

	}

	break;

    }

    i++;

    

}
 

}

void result(){

	

	float percentage=0;

	cout<<"Student Name: "<<st.nam<<endl;

	cout<<"Roll no: "<<st.rollno<<endl;

	

cout<<"Marks: "<<st.marks<<" out of 6"<<endl;

	percentage=100*st.marks/6;

	cout<<"Percentage: "<<percentage<<"%"<<endl;

	if(percentage>=50){

		cout<<"Status: Pass"<<endl;

	}

	else {

	cout<<"Status: Fail"<<endl;

    }

}



main(){

	char press,select;

	do

	{

	cout<<"\n\n\t\t***********"<<endl;

	cout<<"\t\t  QUIZ "<<endl;

	cout<<"\t\t***********"<<endl;

	cout<<"\t\tEnter name: ";

	gets(st.nam);

	cout<<"\t\tEnter rollno: ";

	gets(st.rollno);

	system("CLS");

	cout<<"\t\tMarks less than 50% will be fail"<<endl;

	cout<<"\n\nSelect option which subject's quiz you want to perform"<<endl;

	cout<<"1) C++"<<endl;

	cout<<"2) Java"<<endl;

	cout<<"3) Dbms"<<endl;

	select=getch();

	system("CLS");

	

switch(select)
{

		case '1':

			cout<<"\t\tC++ Quiz"<<endl;

			cppp();

			system("CLS");

			cout<<"\t\tC++ Quiz Result"<<endl;

			result();

			break;

		case '2':

			cout<<"\t\tJava Quiz"<<endl;

		    java();

		    system("CLS");

		    cout<<"\t\tJava Quiz Result"<<endl;

		    result();

		    break;

		case '3':

			cout<<"\t\tDbms Quiz"<<endl;

			dbms();

			system("CLS");

			cout<<"\t\tDbms Quiz Result"<<endl;

			result();

			break;

		default:

			cout<<"Invalid input"<<endl;

			break;

	}

	cout<<"Press y if you want to continue or any key to terminate"<<endl;

	press=getch();

	system("CLS");

   }

while(press=='y'||press=='Y');

}












