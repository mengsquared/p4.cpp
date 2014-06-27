p4.cpp
======

int factorial(int num, int ans) {
    if (num == 1 || num == 0) {
          return ans;
    }
    
    ans = ans*num;
    factorial(num-1, ans);
}

int main() {
    int num;
    cout << "Find factorial of: " << endl;
    cin >> num;
    int result = factorial(num, 1);
    cout << "Factorial is " << result;
    return(0);
    
    //FIND OUT IF THIS WORKS
    
}
