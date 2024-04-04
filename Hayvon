#include <iostream>
#include <string>
using namespace std;

class HayvonSifat {
private:
    string tur;
    string rang;
    float ogirligi;
    int yoshi;

public:
    void show() {
        static int k = 0;
        cout << ++k << " - Hayvon sifati:" << endl << endl;
        cout << "Turi: " << tur << endl;
        cout << "Rangi: " << rang << endl;
        cout << "Og'irligi: " << ogirligi << " kg" << endl;
        cout << "Yoshi: " << yoshi << " yosh" << endl << endl;
    }

    void input() {
        static int k = 0;
        cout << ++k << " - Hayvon sifatini kiriting:" << endl << endl;
        cout << "Turi: "; cin >> tur;
        cout << "Rangi: "; cin >> rang;
        cout << "Og'irligi: "; cin >> ogirligi;
        cout << "Yoshi: "; cin >> yoshi;
        cout << endl;
    }

    void qidir() {
        int k;
        cout << "Izlash turini kiriting: " << endl;
        cout << "Turi: 1" << endl;
        cout << "Rangi: 2" << endl;
        cout << "Og'irligi: 3" << endl;
        cout << "Yoshi: 4" << endl;
        cin >> k;

        if(k==1) {
            string s;
            cout << "Qidirilayotgan tur: "; cin >> s;
            if(tur.compare(s) == 0) {
                cout << "Bunday turdagi hayvon mavjud:" << endl;
                show();
            }
        }

        if(k==2) {
            string s;
            cout << "Qidirilayotgan rang: "; cin >> s;
            if(rang.compare(s) == 0) {
                cout << "Bunday rangdagi hayvon mavjud:" << endl;
                show();
            }
        }

        if(k==3) {
            float s;
            cout << "Qidirilayotgan og'irligi: "; cin >> s;
            if(ogirligi == s) {
                cout << "Bunday og'irligidagi hayvon mavjud:" << endl;
                show();
            }
        }

        if(k==4) {
            int s;
            cout << "Qidirilayotgan yoshi: "; cin >> s;
            if(yoshi == s) {
                cout << "Bunday yoshdagi hayvon mavjud:" << endl;
                show();
            }
        }
    }
};

int main() {
    HayvonSifat h[100];
    int N;
    cout << "Hayvonlar sonini kiriting: "; cin >> N;
    for(int i = 0; i < N; i++) {
        h[i].input();
    }

    for(int i = 0; i < N; i++) {
        h[i].qidir();
    }
}
