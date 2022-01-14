#include <iostream> //This is my first interaction with this platform I will attach below my first code that I created by myself

using namespace std;

float adunare (float, float, float, float);
float scadere (float, float, float, float);
float inmultire (float, float, float, float);
float impartire (float, float, float, float);

int main()
{
    float a;
    cout << "a = ";
    cin >> a;
    float b;
    cout << "b = ";
    cin >> b;
    float c;
    cout << "c = ";
    cin >> c;
    float d;
    cout << "d = ";
    cin >> d;
    float ad;
    float sc;
    float in;
    float im;
    ad = adunare(a, b, c, d);
    sc = scadere(a, b, c, d);
    in = inmultire(a, b, c, d);
    im = impartire(a, b, c, d);
    cout << "Suma numerelor este: "<< ad << endl;
    cout << "Diferenta numerelor este: "<<sc << endl;
    cout << "Inmultirea numerelor este: "<< in << endl;
    cout << "Impartirea numerelor este: "<< im << endl;
}
float adunare (float p, float q, float r, float t){
    float adFunctie;
    adFunctie = (p + q + r + t);
    return adFunctie;
}
float scadere (float p, float q, float r, float t){
    float scFunctie;
    scFunctie = (p - q - r - t);
    return scFunctie;
}
float inmultire (float p, float q, float r, float t){
    float inFunctie;
    inFunctie = (p * q * r * t);
    return inFunctie;
}
float impartire (float p, float q, float r, float t){
    float imFunctie;
    imFunctie = (p / q / r / t);
    return imFunctie;
}
