#include <iostream>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <conio.h>
#include <time.h>
using namespace std;
int main()
{
    awalnemen:
    string siap, ulangi, pil, lagi;
    cout << "==========================================" << endl;
    cout << "        Japar sodik: ";
    cin >> siap;
    cout << "==========================================" << endl;
    cout << "             Apakah Kamu Siap" << endl;
    cout << "   Untuk Bermain Batu Kertas Gunting ? " << endl;
    cout << "==========================================" << endl;
    cout << "                 [ya/tidak] ? " ;
    cin >> siap;
    if(siap=="y"){
        pertama:
        srand(time(NULL));
        int com = rand() % 10;
		system("cls");
        cout << "==========================================" << endl;
        cout << "             Selamat Datang " << endl;
        cout << "      Di Game Batu, Kertas, Gunting " << endl;
        cout << "==========================================" << endl;
        cout << " Pilihlah angka dari keempat pilihan ini : " << endl;
        cout << endl;
        cout << "    1. Batu\n    2. Kertas\n    3. Gunting\n\n    4. Keluar" << endl;
        cout << "  Tulis Pilihanmu : "; cin >> pil; cout << endl;

        if (pil=="2")
        {
            cout << "==========================================" << endl;
            cout << "  Kamu pilih = KERTAS  " << endl;

            if(com<=3 && com>=2){
                cout << "  Lawan pilih = KERTAS  " << endl;
                cout << "==========================================" << endl;
                cout << "   ==> SERI ! <==   " << endl;
            }
            else if(com<=6 && com>=4){
                cout << "  Lawan pilih = GUNTING  " << endl;
                cout << "==========================================" << endl;
                cout << " ==> KAMU KALAH ! <==" << endl;
            }
            else{
                cout << "  Lawan pilih = BATU  " << endl;
                cout << "==========================================" << endl;
                cout << "  ==> KAMU MENANG ! <==  " << endl;
            }
        }
        else if(pil=="1")
        {
            cout << "==========================================" << endl;
            cout << "  Kamu pilih = BATU  " << endl;

            if(com<=3 && com>=2){
                cout << "  Lawan pilih = BATU  " << endl;
                cout << "==========================================" << endl;
                cout << "    ==> SERI ! <==   " << endl;
            }
            else if(com<=6 && com>=4){
                cout << "  Lawan pilih = KERTAS  " << endl;
                cout << "==========================================" << endl;
                cout << " ==> KAMU KALAH ! <==  " << endl;
            }
            else{
                cout << "  Lawam pilih = GUNTING  " << endl;
                cout << "==========================================" << endl;
                cout << " ==> KAMU MENANG ! <== " << endl;
            }
        }
        else if(pil=="1")
        {
            cout << "==========================================" << endl;
            cout << "  Kamu pilih = BATU  " << endl;

            if(com<=1 && com>=1){
                cout << "  Lawan pilih = BATU  " << endl;
                cout << "==========================================" << endl;
                cout << "    ==> SERI ! <==   " << endl;
            }
            else if(com<=6 && com>=4){
                cout << "  Lawan pilih = KERTAS  " << endl;
                cout << "==========================================" << endl;
                cout << " ==> KAMU KALAH ! <==  " << endl;
            }
            else{
                cout << "  Lawan pilih = GUNTING  " << endl;
                cout << "==========================================" << endl;
                cout << " ==> KAMU MENANG ! <== " << endl;
            }
        }
        else if(pil=="4")
        {
            exit:
            system("cls");
            cout << "\n Terimakasih, Sudah Bermain :) " << endl;
            cout << "      Bermain Lagi Yah        " << endl;
            getch();
            return 0;
        }
        else
        {
            cout << "==========================================" << endl << endl;
            cout << " Inputan Salah ! Silahkan Ulangi Kembali " << endl;
            cout << "        ==> Tekan ENTER <==" << endl;
            getch();
            system("cls");
            goto pertama;
        }
        cout << "==========================================" << endl << endl;
        cout << " Tekan ENTER ";
        getch();
        system("cls");

        cout << "==========================================" << endl;
        cout << "==========================================" << endl;
        cout << "           Main Lagi [y/t] ? ";
        cin >> lagi;
        if (lagi=="y"){
            system("cls");
            goto pertama;
        }
        else if (lagi=="t"){
            system("cls");
            goto exit;
            getch();
        }
    }
    else if(siap=="t"){
        keluar:
        system("cls");
        cout << "\n\n\n\n" << endl;
        cout << "============================================================================" << endl;
        cout << "                  Kamu Telah Keluar Dari Permainan" << endl;
        cout << "============================================================================" << endl;
        cout << "                             Tekan ENTER ";
        getch();
        return 0;
    }
    else {
        cout << "============================================================================" << endl;
        cout << "                      **** Inputan Salah ! ****" << endl;
        cout << "                              Ulangi ?" << endl;
        cout << "============================================================================" << endl;
        cout << "                                 y ? ";
        cin >> ulangi;
        if(ulangi=="y"){
            system("cls");
            goto awalnemen;
        }
        else {
            goto keluar;
        }
    }
}
