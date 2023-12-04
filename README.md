# lab-works
#include <iostream>
#include <cmath>
using namespace std;
int main()
{
    float H,h,W,BMI;
    cout<<" Enter your weight in Kg: ";
    cin>>W;
    cout<<" Enter your height in meter: ";
    cin>>h;
    H= pow(h,2);
    BMI=W/H;
    cout<<" your body mass index is: "<<BMI;
    return 0;
}
