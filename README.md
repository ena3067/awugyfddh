#include<iostream>
using namespace std;
int main ()
{
/*Proljece=>21.3.-21.6.
Ljeto=>21.6.-23.9.
Jesen=>23.9.-21.12.
Zima=>21.12.-21.3.
*/
cout<<"Unesite broj mjeseca" (1-12)<<endl;
cin>>mjesec;
if (mjesec==3){
cout<<"U ovom mjesecu se desava promjena godisnjih doba, zavrsava jesen a pocinje zima na 21.dan"<<endl;
}
elfe if (mjesec==9){
cout<<"U ovom mjesecu se desava promjena godisnjih doba, zavrsava jesen a pocinje ljeto na 23.dan"<<endl;
}
else if (mjesec==1)&&(mjesec=2){
cout<<"Godisnhe doba kojem mjesec pripada je zima.";
}
else if (mjesec--4)&&(mjesec==5){
cout<<"Godisnje doba kojem mjesec pripada je proljece"'
}
else if (mjesec==7)&&(mjesec==8)){
cout<<"Godisnje doba kojem mjesec pripada je ljeto";
}
else if (mjesec==10)&&(mjesec==11){
cout<<"Godisnje doba kojem mjesec pripada je jesen";
}
return 0;
}
