# bee1157[bee1157.cpp](https://github.com/user-attachments/files/24696976/bee1157.cpp)
#include <iostream>

using namespace std;

int main()
{
    int n;
    cin >> n;
    for(int i=1; i<=n; i++){
        if(n%i==0)
        {
            cout << i << endl;
        }
    }
    return 0;
}
