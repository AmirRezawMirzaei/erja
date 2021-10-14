#include <iostream>
#include <conio.h>
#include <math.h>

using namespace std;

void maximum();

int main()
{
    cout<< "Enter three numbers = ";
    maximum();
    getch();
}
void maximum()
{
    int a , b , c ,max , min ;
    cin>>a>>b>>c;
    max = a;
    if(max<b)
       max=b;
    else if(max<c)
       max=c;
    min = a;
    if(min>b)
        min = b;
    if(min>c)
        min = c;
    cout<< "Max is = "<<max<<endl;
    cout<< "Min is = "<<min;
}

