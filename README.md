#include <iostream>
#include <math.h>
using namespace std;

int main() {
const int pi=3.1415;
float a, b, u, c,s, h;
cin >>a>>b>>u;
c=(b-a)/2;
h=c*tan(u*pi/180);
s=(a+b)/2*h;


cout <<"s= "<<s<<endl;

    return 0;
}
