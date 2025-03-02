#include<iostream>
using namespace std;

void start_game();
void end_game(int score);
int main(){

    string user_input;

    cout<<" ,,,,,,,,Welcome,,,,,"<<endl;
    cout<<",,,,, If you want to play game then enter'play' to start: ";
    cin>>user_input;
    if (user_input=="play")
    {
        start_game();

    }
    else{
         end_game(0);
    }
    
}

void start_game()
{
    char answer;
    int score=0;
    //question 1. start here
   cout<<"how much ic 70-1"<<endl;
   cout<<"a) 4"<<endl;
   cout<<"b) 69"<<endl;
   cout<<"c) 3"<<endl;
   cout<<"d) 0"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
      cin>>answer;
    
   if (answer=='b')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }
  //question ends here

  //question.2 start here
    cout<<"who is the CEO of Google "<<endl;
   cout<<"a) Bill Gates"<<endl;
   cout<<"b) Jeff Bezos"<<endl;
   cout<<"c) Srk"<<endl;
   cout<<"d) Sundar pichai"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='d')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }
   //question ends here


   //question.3  start here
   cout<<"which state is famous for hollywood "<<endl;
   cout<<"a) California "<<endl;
   cout<<"b) New York"<<endl;
   cout<<"c) Paris"<<endl;
   cout<<"d) Sydney"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='a')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }


   //question.4  start here
   cout<<"Chemical formula for water is "<<endl;
   cout<<"a)NaAlO2 "<<endl;
   cout<<"b) H2O"<<endl;
   cout<<"c) Al2O3"<<endl;
   cout<<"d) CaSiO3"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='b')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }




   //question.5  start here
   cout<<"The gas usually filled in the electric bulb is "<<endl;
   cout<<"a) Nitrogen"<<endl;
   cout<<"b)Hydrogen "<<endl;
   cout<<"c) Carbon Dioxide"<<endl;
   cout<<"d) Oxygen"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='a')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }



   //question.6  start here
   cout<<" What is the full meaning of AI?"<<endl;
   cout<<"a)Artificial internet "<<endl;
   cout<<"b) Artificial information"<<endl;
   cout<<"c) Artificial interface"<<endl;
   cout<<"d)Artificial intelligence "<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='d')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }



   //question.7  start here
   cout<<" Which robot has been granted citizenship"<<endl;
   cout<<"a) Reco"<<endl;
   cout<<"b) Seba"<<endl;
   cout<<"c)Reco "<<endl;
   cout<<"d) Sophia"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='d')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }



   //question.8  start here
   cout<<"Find the sum of 111 + 222 + 333 "<<endl;
   cout<<"a)100 "<<endl;
   cout<<"b) 412"<<endl;
   cout<<"c) 666"<<endl;
   cout<<"d) 120"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='c')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }


   //question.9  start here
   cout<<" Who is hosting the 2026 World Cup "<<endl;
   cout<<"a) Canada"<<endl;
   cout<<"b)  Mexico"<<endl;
   cout<<"c)United States "<<endl;
   cout<<"d) All of the Above"<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='d')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }


   //question.10  start here
   cout<<"Who is the king of Bollywood? "<<endl;
   cout<<"a)Shah Rukh Khan "<<endl;
   cout<<"b)Salman Khan "<<endl;
   cout<<"c)Aamir Khan "<<endl;
   cout<<"d)Akshay Kumar "<<endl;

   cout<<"please entered 'a' 'b' 'c''d' and press enter: ";
   cin>>answer;
   if (answer=='a')
   {
    cout<<"congrats you enrerd right answer "<<endl;
     score++;
   }
   else
   {
    cout<<"sorry , your answer wrong "<<endl;
   }



   end_game( score);
}


void end_game(int score){
  cout<<"thanks for playing"<<endl;
  cout<<"yor score is: "<<score<<endl;

}
