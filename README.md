#include <iostream>

using namespace std;

int main()
{
    int rows, i,j,k=0;
    cout << "masukkan jumlah baris:";
    cin >> rows;
    for (i=1;i<=rows;i++)
    {
        for (j=1;j<=i;++j)
          cout <<k+j<<"";
        ++k;

    cout <<endl;
    }
    return 0;
}
