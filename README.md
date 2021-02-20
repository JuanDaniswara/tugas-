# tugas-
#nama = Juan Daniswara Putra
#Universitas Kristen Duta Wacana

'''
sumber : https://koding.alza.web.id/latihan-soal-percabangan/

Keterangan Generasi :

1. Generasi Diam, kelahiran 1928 s.d 1945 
2. Baby boomer, kelahiran 1944 s.d 1964
3. Generasi X, kelahiran 1965 s.d 1979
4. Generasi Y (Millenial), kelahiran 1980 s.d 1994
5. Generasi Z, kelahiran 1995 s.d 2010
6. Generasi Alpha kelahiran > 2010 

Buat program dimana user diminta untuk menuliskan nama dan tahun kelahirannya, 
kemudian cetak nama dan generasinya.

'''
print()
print("========== CARI TAU GENERASI ANDA ==========")
print()

pilihan = 'y'

while (pilihan !='n') :

    nama_User = input("Masukkan nama Anda = ")
    tahun_Kelahiran = int(input("Masukkan tahun kelahiran Anda = "))

    if tahun_Kelahiran >= 1928 and tahun_Kelahiran <= 1944 :
        print(nama_User,"generasi anda adalah Generasi Diam.")
    elif tahun_Kelahiran >= 1945 and tahun_Kelahiran <= 1964 :
        print(nama_User,"generasi anda adalah Generasi Baby boomer.")
    elif tahun_Kelahiran >= 1965 and tahun_Kelahiran <= 1979 :
        print(nama_User,"generasi anda adalah Generasi X.")
    elif tahun_Kelahiran >= 1980 and tahun_Kelahiran <= 1994 :
        print(nama_User,"generasi anda adalah Generasi Y (Millenial).")
    elif tahun_Kelahiran >= 1995 and tahun_Kelahiran <= 2010 :
        print(nama_User,"generasi anda adalah Generasi Z.")
    elif tahun_Kelahiran > 2010 and tahun_Kelahiran <= 2021 :
        print(nama_User,"generasi anda adalah Generasi Alpha.")
    else :
        print("Nama/Tahun yang anda masukkan salah.") 
    pilihan = input("Anda ingin mengulanginya lagi (y/n)? ")

