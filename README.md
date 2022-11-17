# datatypes-in-c-
#include <iostream>
#include <cstdio>
#include <iomanip>
using namespace std;

int main()
 {
    iint a;
    long b ; 
    char c ;
    float d;
    double e;

     cin >> a >> b >> c >> d >> e;
     printf("%d\n%ld\n%c\n%0.3f\n%0.9lf",*&a,*&b,*&c,*&d,*&e);

    return 0;
}
