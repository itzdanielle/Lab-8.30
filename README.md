# Lab-8.30
#include <iostream>
#include <string>
using namespace std;

int main() {

string secret = "open";
int password;
cout << "What is the secret password?\n";
cin >> secret;

if ( secret == "open")
{
  cout << "Congrats you got it right!\n";
}

else 
{
  cout << "Try again." << endl;
  cout << "Hint: what is the opposite of the word 'close'? " << endl;

}


}
