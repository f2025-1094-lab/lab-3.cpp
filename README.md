#include <iostream>
#include <iomanip>
using namespace std;
int main() {
    string product1 ,product2;
    float price1, price2;
    int quantity1, quantity2;
     cout << "enter the name of product 1=";
    cin >> product1;
    cout << "enter the price of product 1=";
    cin >> price1;
    cout << "enter the quantity of product 1=";
    cin >> quantity1;
   
    float total = price1*quantity1;
    cout<<"-----------------------------------------"<<endl;
    cout<<left<<setw(15)<<"item"<<right<<setw(15)<<"price"<<setw(15)<<"quantity"<<right<<setw(15)<<"total";
    cout<<endl<<"-----------------------------------------"<<endl;
    cout<<left<<setw(15)<<product1<<right<<setw(15)<<price1<<setw(15)<<quantity1<<right<<setw(15)<<total;
    return 
