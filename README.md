# sike 

a
this code for find the value ASCII  (American Standard Code For Information Interchange) . it can convert  a word to ascii value






#include <iostream>
#include <string>


int main()
{

char letter[50];//[1,2,3,4]
int n,i;//        [0,1,2,3,]

std::cout<<"   ";

std::cout<<"   ";

std::cout<<"   ";

std::string name;
std::cout<<"         PLEASE DON'T LEAVE SPACE              "<<"\n";


std::cout<<"\t"<<"Enter you name i will give how many6 letter in it :-"<<"\t";

//std::cin>>name;
std::getline(std::cin,name);
std::cout<<"\t"<<"Number of leteer in the give word is:-"<<"\t"<<name.length()<<"\n";


std::cout<<"\t"<<"ENTER NUMER OF LETTER YOU WANT TO ENCRYPTED:-";
std::cin>>n;



for(i=0; i<n; i++){



std::cout<<"\t"<<"Enter value : "<<"\t"<<i+1<<"\t";

std::cin>>letter[i];

std::cout<<"   ";


//std::cout<<int(letter[i])<<"\n";
//std::cout<<"   ";


}

for(i=0; i<n; i++){



std::cout<<"\t"<<int(letter[i])<<"\n";
std::cout<<"   ";


}




return 0;

}

