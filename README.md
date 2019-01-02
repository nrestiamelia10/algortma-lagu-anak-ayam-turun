#include <iostream>

using namespace std;

int main()
{
    int x,jmlh_anak;
    cout<< " Masukkan jumlah anak ayam yang akan turun :";
    cin>>jmlh_anak;
    cout<< " Mari kita nyanyikan lagu anak ayam turun"<<jmlh_anak<<endl;
    cout<< " Mulai !"<<endl;
    for (x=jmlh_anak;x>0;x--)
    {
        if (x>1)
            cout<< "Anak ayam turun  : "<<x<< "  Mati satu tinggal  : "<<x-1<<endl;
        else if (x=1)
            cout<< "Anak ayam turun 1 Mati satu tinggal induknya"<<endl;
    }
}
