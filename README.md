# amina
#include <iostream>
#include <cmath>
using namespace std;
double wow(double a, int n){
double qwert=1;
for(double i=1; i<=n; i++) {
   qwert*=a;
}
 return qwert;
}
int main(){
  double a;
  int n;
  cin >> a >> n;
    cout << wow(a,n)<<endl;
 return 0;
 }
