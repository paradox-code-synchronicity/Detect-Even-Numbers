# Detect-Even-Numbers

//
//  main.cpp
//  Quiz_Even_numbers
//
//  Created by Brandon Tseng on 9/23/21.
//

#include <iostream>
using namespace std;

int main() {
  int startValue = 0;
  int endValue;
    cout << "Enter an integer for endValue: ";
    cin >> endValue;
// your solution starts here
    for(startValue=1; startValue <= endValue; startValue++){ // use for loop from zero to the number inputted by user input. 
        if(startValue % 2 == 0){ // detects even numbers and filters out odd numbers
        cout << "Even numbers: " << startValue << endl;
}
    }
// your solution ends here

return 0;
}

