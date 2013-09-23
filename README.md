p95-1
=====
#include <iostream>
using namespace std;
void main()
{
	double c,f;
  int a;
	cout<<"华氏转化成摄氏请输入0，摄氏转化成华氏请输入1。"<<endl;
	cin>>a;
	if (a)
		{ 
      cout<<"请输入摄氏温度:"<<endl;
			cin>>c;
			f= (9.0/5.0)*c + 32;
			cout<<"对应的华氏温度为:"<<f<<endl;
			
	   }
		else 
		{
			cout<<"请输入华氏温度:"<<endl;
			cin>>f;
			c = (5.0/9.0)*(f-32);
			cout<<"对应的摄氏温度为:"<<c<<endl;
			
    }
	}

