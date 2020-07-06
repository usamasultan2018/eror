Find Error in this Program
#include <iostream> 
using namespace std; 
class A{ 
public:
	int a;
};
class B: public A{ 
public:
	int b;
};
class C: public A{ 
public:
	int c;
};  
class D:public B, public C{ 
public:
	int d;
};
int main(){
 D obj;
 obj.b=2;
 obj.c=3;
 obj.d=4;
 obj.a=1;
 cout<<obj.b<<obj.c<<obj.d<<obj.a;
 return 0; }
 
