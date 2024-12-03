- 👋 Hi, I’m @DuxZX2023
- 👀 I’m interested in ... pass the semester
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

#include <iostream>
using namespace std;

int main() {
    float nota;

    cout << "Ingrese la calificación (0-100): ";
    cin >> nota;

    if (nota >= 90 && nota <= 100) {
        cout << "La calificación es: A (4.0)" << endl;
    }
    
    else if (nota >= 80 && nota < 90) {
        cout << "La calificación es: B (3.0)" << endl;
    }
        else if (nota >= 70 && nota < 80) {
            cout << "La calificación es: C (2.0)" << endl;
        }
            else if (nota >= 60 && nota < 70) {
                cout << "La calificación es: D (1.0)" << endl;
            }
                 else if (nota >= 0 && nota < 60) {
                     cout << "La calificación es: F (0.0)" << endl;
                           }
                        else {
                           cout << "Nota inválida. Ingrese un valor entre 0 y 100." << endl;
                              }

    return 0;
}
