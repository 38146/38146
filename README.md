#include <iostream>
using namespace std;
int main() {
    int n;
    cout << "n=? ";
    cin >> n ;
  
    for (int f = 1 ; f<=n ; f++){
	
	 for (int e = n-1 ; e>=f ; e--){
	      cout << " ";
	 }
         for (int j = 1; j <= f ; j++) {
	      cout << "#";
         }
    
	 cout << " " ;

         for (int i = 1 ; i<=f ;i++){
	      cout << "#";
	 }
	 cout << "\n" ;
	}
}
<!---
38146/38146 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
