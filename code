#include<iostream>
#include<windows.h>
#include<MMsystem.h>
#include<fstream>  
#include<ctime>
#include<dirent.h>
#include<memory>
#include<iomanip>
#include<unistd.h>

using namespace std;
int hours = 0;
int minutes = 0;
int seconds = 0;


void timer(int sec){
	Sleep(sec*1000);
}
int main(){
	int n;
	char choose;
	time_t t1, t2, previous_pause_time=0;
	system("Color 0B");
	cout<<"\t\t\t\t\t\tWelcome to Sangeet\n\n";
	 list:
	   cout<<"Which Singer You Want To Listen?\n";
	   cout<<"1)Armaan Malik  Press'A'\n2)Darshan Raval Press'D'\n3)Shashaa Tirupati Press'S'\n4)Kishore Kumar Press'K'\n5)Mohammad Rafi Press'M'\n6)Close Player Press'E'\n";
	cin>>choose;
	switch(choose)
	{
	case 'A':
    
		
		while(1)
	 {  cout << "Press 1 to Play the Song and Press 3 for Another Singer." << endl;
        cin>>n;
        
    if(n==1)
    {  
       t1=time(0);
       cout<<"Audio file playing...\n\n";
       
	   PlaySound(TEXT("F:\\Wav Files\\Humnawaa(MyMp3Song).wav"),NULL,SND_ASYNC);
       
     }
     else if(n==3)
     {
       mciSendString("close mp3", NULL, 0, NULL);
       goto list;
       cout<<"\n\n";
     }
	 }
	 
	case'D':
	
			while(1)
	 {  cout << "Press 1 to Darshan Raval's List and Press 3 for Menu Again" << endl;
        cin>>n;
        int m,z;
    if(n==1)
    {  
	   string name;
       string a1= "F:\\Wav Files\\Ek Tarfa - Darshan Raval 128 Kbps.wav";
       string a2="F:\\Wav Files\\Rabba Mehar Kari - (amlijatt.in).wav";
       
       cout<<"1)Ek Tarfa Press'1'\n2)Rabba Mehar Kari Press'2'\n";
       cin>>m;
       if(m==1)
       {
       	t1=time(0);
       cout<<"Audio file playing...\n\n";
       cout<<"Want To See Lyrics Press'1'And For Audio Press'2'\n";
       cin>>z;
       if(z==1){
       	
	    PlaySound((a1.c_str()),NULL,SND_ASYNC);
       	timer(25);
       	cout<<"Akhiyon se dariya beh gaya haye\n\n";
       	timer(6);
       	cout<<"Khwaab woh adhoora reh gaya\n\n";
       	timer(6);
       	cout<<"Jag bhi paraya ho gaya haye\n\n";
       	timer(6);
       	cout<<"Juda tera saya ho gaya\n\n";
       	timer(5);
       	cout<<"Teri duniya mujhe ab na ganwara hai\n\n";
       	timer(6);
       	cout<<"Par tu hassdi reh bas yehi sahara hai\n\n";
       	timer(6);
       	cout<<"Mohabbat ho gayi thi donon ko\nEk arsa ho gaya\n\n";
       	timer(6);
       	cout<<"Mera yeh ishq tha do tarfa \nAb ek tarfa ho gaya\n\n";
       	/*timer(36);
       	cout<<"Chand bhi rootha Taare bhi roothe \nAasman bhi mera na rahaaa..\n\n";
       	timer(13);
       	cout<<"Hairan Hoon main dil main tere yun \nMera basera na rahaa...\n\n";*/
	   }
	   else if(z==2){
       PlaySound((a1.c_str()),NULL,SND_ASYNC);	
       }
	   }
	   else if(m==2)
	   {
	   	t1=time(0);
       cout<<"Audio file playing...\n\n";
		PlaySound((a2.c_str()),NULL,SND_ASYNC);
	   }
       	   
     }
     else if(n==3)
     {
       mciSendString("close mp3", NULL, 0, NULL);
       goto list;
       cout<<"\n\n";
     }
	 }
	case'S':	
	   while(1)
	 {  cout << "Press 1 to Play the Song and Press 3 for Another Singer." << endl;
        cin>>n;
    if(n==1)
    {  
       t1=time(0);
       cout<<"Audio file playing...\n\n";
		PlaySound(TEXT("F:\\Wav Files\\Soja Soja(MyMp3Song).wav"),NULL,SND_ASYNC);
		}
     else if(n==3)
     {
       mciSendString("close mp3", NULL, 0, NULL);
       goto list;
       cout<<"\n\n";
     }
	 }
		
	case'K':
		while(1)
	 {  cout << "Press 1 to Play the Song and Press 3 for Another Singer." << endl;
        cin>>n;
    if(n==1)
    {  
       t1=time(0);
       cout<<"Audio file playing...\n\n";
		
		PlaySound(TEXT("F:\\Wav Files\\Ek-Ajnabee-Haseena-Se-(pagalworldsongs.co.in).wav"),NULL,SND_ASYNC);
	}
		else if(n==3)
     {
       mciSendString("close mp3", NULL, 0, NULL);
       goto list;
       cout<<"\n\n";
     }
	 }
		
	case'M':
		while(1)
	 {  cout << "Press 1 to Play the Song and Press 3 for Another Singer." << endl;
        cin>>n;
    if(n==1)
    {  
       t1=time(0);
       cout<<"Audio file playing...\n\n";
		PlaySound(TEXT("F:\\Wav Files\\Ehsan-Tera-Hoga-Mujh-Par-oldisgold.co_.in_.wav"),NULL,SND_ASYNC);
		}else if(n==3)
	
     {
       mciSendString("close mp3", NULL, 0, NULL);
       goto list;
       cout<<"\n\n";
     }
	 }
	 case'E':
		cout<<"Sangeet Closed";
		exit(1);
		break;
	}
}
