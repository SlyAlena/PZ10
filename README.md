# PZ10
![Alt text](URL_to_image "Optional title")
<img width="1276" height="384" alt="Снимок экрана (25)" src="https://github.com/user-attachments/assets/6799e38b-4b10-4a2e-9bc2-5b54579c8ff0" />


Задание 1

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    for(int i = 1; i <= N; i++) {
        cout << i << " ";
    }


    return 0;
    }

Задание 2

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    for(int i = N; i > 0; --i) {
        cout << i << " ";
    }


    return 0;
    }

Задание 3

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    int sum = 0;
    for(int i = 1; i <= N; ++i) {
        sum += i;
       
    }
    cout << sum;
    


    return 0;
    }

Задание 4

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    for(int i = 1; i <= N; ++i) {
        if(i % 2 == 0) {
            cout << i << ' ';
        }
    }


    return 0;
    }

Задание 5

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    int counter = 0;
    for(int i = 1; i <= N; ++i) {
        if(i % 2 == 0) {
            counter += 1;
         
        }
        
    }
    cout << counter;


    return 0;
    }

Задание 6

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    int factorial = 1;
    for(int i = 1; i <= N; ++i) {
        factorial *= i;
        
    }
    cout << factorial;
  


    return 0;
    }

Задание 7

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
    for(int i = 1; i <= 10; i++) {
        int n = i * N;
        cout << N << ' ' << '*' << ' ' << i << ' ' << '=' << ' ' << n << endl;
    }


    return 0;
    }

Задание 8

    #include <iostream>
    using namespace std;

    int main() {
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    // Ваш код:
     for( int i = 0; i < N; ++i) {
        for(int j = 0; j < N; ++j) {
            cout << "*";
            
        }
        cout << endl;
    }
 
    


    return 0;
    }
