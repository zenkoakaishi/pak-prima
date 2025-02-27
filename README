Latihan 1: Dasar Array public class LatihanArray1 { public static void main(String[] args) { // Buat program untuk: // 1. Membuat array dengan 10 bilangan bulat // 2. Mengisi array dengan bilangan genap mulai dari 2 // 3. Menampilkan isi array // 4. Menghitung jumlah semua elemen array

    int[] bilanganGenap = new int[10]; : untuk membuat sebuah array bernama bilanganGenap yg menyimpan 10 bilangan,dengan mendeklarasikan terlebih dahulu "int[] bilanganGenap" dan menginisialisasikan array "new int[10]"
    int jumlah = 0; : untuk mengumpulkan serangkaian nilai

    // Mengisi array
    for (int i = 0; i < bilanganGenap.length; i++) { :kegunaan for adalah loop atau perulangan dengan melalui proses menginisialisasikan nilai apabila indeks dimulai dari 0 isi dengan int i = 0, dilanjut dengan batasan yg ingin ditampilkan atau penjelasan dari google seperti kondisi yg menentukan apakah perulangan akan terus berlanjut, agar value dari indeks bertambah kita harus melakukan pengupdatean yaitu i++(untuk menambahkan)/i--(untuk mengurangi)
        bilanganGenap[i] = (i + 1) * 2; :untuk menghitung bilangan yg diinginkan
    }

    // Menampilkan array
    System.out.println("Isi array:"); : menampilkan teks "Isi array:" ke layar
    for (int bilangan : bilanganGenap) { :melakukan perulangan dengan mengambil satu persatu angka dari kotak bilangangenap,mulai dari yang pertama sampai terakhir. Setiap angka yang kita ambil, kita sebut bilangan.
        System.out.print(bilangan + " "); : menampilkan angka bilangan. Jadi, semua angka di kotak bilanganGenapakan muncul di layar
        jumlah += bilangan; :Setiap angka yang kita ambil, langsung kita tambahkan ke wadah jumlah tadi. 
    }

    System.out.println("\\nJumlah semua elemen: " + jumlah); :tampilkan total angka-angka yang ada di wadah jumlah ke layar.
}
}

​Latihan 2: Pencarian dalam Array public class PencarianArray { public static void main(String[] args) { // Program mencari nilai dalam array int[] nilai = {75, 80, 65, 90, 85, 70, 95, 88}; :melakukan deklarasi dan inisialisasi lanngsung yg sudah memanggil variabel bernama nilai bertipe integer dengan inisialisasinya elemen-elemen yg sudah tersedia int cari = 90; :untuk menyimpan angka yg ingin kita cari boolean ketemu = false; : boolean adalah tipe data yang hanya memiliki dua nilai true atau false int indeks = -1; : indeks ini untuk menyimpan nomor urut(indeks) angka yg kita cari dalam variabel "nilai"

    // Mencari nilai
    for (int i = 0; i < nilai.length; i++) {
        if (nilai[i] == cari) { : didalam perulangan ini untuk mengecek apakah angka di variabel nilai no urut i sama dengan angka yg mau kita cari
            ketemu = true; :apabila ketemu maka bisa terproses
            indeks = i; : untuk mencatat nomor urut dari indeksnya
            break; apabila sudah benar perulangan langsung berhenti
        }
    }

    // Menampilkan hasil
    if (ketemu) { :jika ketemu akan langsung terproses 
        System.out.println("Nilai " + cari + " ditemukan pada indeks " + indeks);:dilanjut dengan ini agar mengeluarkan hasil yg sudah ditemukan
    } else { :maka dari sini bila tidak ketemu angka yg dicari maka akan tidak ter proses
        System.out.println("Nilai " + cari + " tidak ditemukan"); : dengan outputan nilai yg dicari tidak ditemukan
    }
}
}

​Latihan 3: Statistik Array public class StatistikArray { public static void main(String[] args) { // Program menghitung statistik nilai siswa int[] nilai = {75, 80, 65, 90, 85, 70, 95, 88}; :melakukan deklarasi dan inisialisasi langsung yg sudah memanggil variabel bernama nilai bertipe integer dengan inisialisasinya elemen-elemen yg sudah tersedia

    // Mencari nilai tertinggi dan terendah
    int tertinggi = nilai[0]; : agar bisa dipanggil untuk diproses ke perulangan
    int terendah = nilai[0];
    int total = nilai[0];

    for (int i = 1; i < nilai.length; i++) { :i =1 karena inisialisasinya sudah terdapat nilai bisa langsung diisi 1 agar terhitung dengan tepat
        if (nilai[i] > tertinggi) tertinggi = nilai[i]; :memanggil nilai array lalu dilanjut dengan simbol lebih besar agar terproses nilai yg lebih besar
        if (nilai[i] < terendah) terendah = nilai[i]; penjelasan kurang lebih sama dengan lebih besar yg ini menggunakan simbol lebih kecil untuk nilai terkecil
        total += nilai[i]; :untuk memproses penotalan semua nilai pada nilai indeks
    }

    double rataRata = (double) total / nilai.length; : tipe data double ini outputannya biasanya ada komanya dengan mencari nilai rata rata caranya dari proses perulangan nilai pada elemen dijumlahkan semua setelah itu dibagi dengan banyaknya elemen

    System.out.println("Nilai tertinggi: " + tertinggi); :menampilkan nilai tertinggi
    System.out.println("Nilai terendah: " + terendah); :menampilkan nilai terendah
    System.out.println("Rata-rata: " + rataRata); : menampilkan rata rata nilai
}
}

​Latihan 4: Array 2D - Matriks public class OperasiMatriks { :Membuat clas bernama operasimatriks public static void main(String[] args) { :Memulai metode main, merupakan titik awal program eksekusi. // Program operasi matriks int[][] matriksA = { :Mendeklarasikan dan menginisialisasi matriks matriksAdengan dua baris dan tiga kolom. Baris pertama berisi 1, 2, 3 dan baris kedua berisi 4, 5, 6. {1, 2, 3}, {4, 5, 6} };

    int[][] matriksB = { :Mendeklarasikan dan menginisialisasi matriks matriksBdengan dua baris dan tiga kolom. Baris pertama berisi 7, 8, 9 dan baris kedua berisi 10, 11, 12.
        {7, 8, 9},
        {10, 11, 12}
    };

    // Penjumlahan matriks
    int[][] hasil = new int[2][3];Mendeklarasikan dan menginisialisasi matriks hasiluntuk menyimpan hasil penjumlahan, dengan ukuran yang sama dengan matriksAdan matriksB, yaitu dua baris dan tiga kolom.

    for (int i = 0; i < matriksA.length; i++) { :Memulai loop pertama untuk iterasi melalui setiap baris matriks. matriksA.lengthmemberikan jumlah baris dalam matriksA.
        for (int j = 0; j < matriksA[0].length; j++) { :Memulai loop kedua untuk iterasi melalui setiap kolom dalam baris yang sedang diproses. matriksA[0].lengthmemberikan jumlah kolom dalam matriksA.
            hasil[i][j] = matriksA[i][j] + matriksB[i][j]; :Melakukan penjumlahan elemen dari matriksAdan matriksB pada posisi yang sama (indeks [i][j]) dan menyimpan hasilnya di matriks hasil.
        }
    }

    // Menampilkan hasil
    System.out.println("Hasil penjumlahan matriks:"); : mencetak outputan dari hasil penjumlahan matriks
    for (int[] baris : hasil) { :Memulai loop untuk iterasi melalui setiap baris dalam matriks hasil.
        for (int nilai : baris) { :Memulai loop untuk iterasi melalui setiap elemen dalam baris yang sedang diproses.
            System.out.print(nilai + " "); :Mencetak nilai elemen saat ini diikuti dengan spasi.
        }
        System.out.println();
    }
}
}

Studi Kasus Studi Kasus 1: Sistem Manajemen Nilai Siswa public class SistemNilai { : membuat class dengan nama sistem niali public static void main(String[] args) { :Memulai metode main, merupakan titik awal program eksekusi. // Data siswa String[] namaSiswa = {"Ani", "Budi", "Cici", "Dodi", "Edi"}; :Mendeklarasikan dan menginisialisasi array namaSiswa yang berisi nama-nama siswa. int[][] nilai = { :Mendeklarasikan dan menginisialisasi array 2D nilai yang berisi nilai-nilai siswa untuk setiap mata pelajaran. {80, 85, 90}, // Nilai Ani {75, 70, 85}, // Nilai Budi {85, 80, 88}, // Nilai Cici {90, 85, 95}, // Nilai Dodi {70, 75, 80} // Nilai Edi }; String[] mapel = {"Matematika", "Bahasa Inggris", "IPA"}; :Mendeklarasikan dan menginisialisasi array mapel yang berisi nama-nama mata pelajaran.

    // Menghitung rata-rata per siswa
    System.out.println("Rata-rata nilai per siswa:");: menampilkan output rata rata nilai persiswa
    for (int i = 0; i < nilai.length; i++) { Memulai perulangan untuk setiap siswa.
        double total = 0; :Mendeklarasikan variabel total untuk menyimpan jumlah nilai dari semua mata pelajaran untuk setiap siswa.
        for (int n : nilai[i]) {
            total += n;
        } :Melakukan perulangan untuk menjumlahkan semua nilai dari setiap mata pelajaran untuk siswa saat ini.
        double rataSiswa = total / nilai[i].length; :Menghitung rata-rata nilai untuk siswa saat ini dengan membagi total nilai dengan jumlah mata pelajaran.
        System.out.printf("%s: %.2f\\n", namaSiswa[i], rataSiswa); :Menampilkan nama siswa dan rata-rata nilainya ke konsol dengan format dua angka di belakang koma.
    }

    // Menghitung rata-rata per mata pelajaran
    System.out.println("\\nRata-rata nilai per mata pelajaran:");
    for (int j = 0; j < nilai[0].length; j++) { :Memulai perulangan untuk setiap mata pelajaran.
        double total = 0; :Mendeklarasikan variabel total untuk menyimpan jumlah nilai dari semua siswa untuk setiap mata pelajaran.
        for (int i = 0; i < nilai.length; i++) {
            total += nilai[i][j];
        } :Melakukan perulangan untuk menjumlahkan semua nilai dari setiap siswa untuk mata pelajaran saat ini.
        double rataMapel = total / nilai.length; :Menghitung rata-rata nilai untuk mata pelajaran saat ini dengan membagi total nilai dengan jumlah siswa.
        System.out.printf("%s: %.2f\\n", mapel[j], rataMapel); :Menampilkan nama mata pelajaran dan rata-rata nilainya ke konsol dengan format dua angka di belakang koma.
    }
}
}

Studi Kasus 2: Permainan Tic-Tac-Toe public class TicTacToe { :membuat Class bernama tictactoe public static void main(String[] args) { :Memulai metode main, merupakan titik awal program eksekusi. char[][] papan = new char[3][3]; :Mendeklarasikan array 2D papan dengan ukuran 3x3 untuk merepresentasikan papan permainan Tic Tac Toe.

    // Inisialisasi papan kosong
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            papan[i][j] = '-';Mengisi seluruh elemen papan dengan karakter '-' untuk menunjukkan bahwa papan awalnya kosong.
        }
    }

    // Simulasi beberapa langkah
    papan[0][0] = 'X'; :Kotak baris pertama kolom pertama kita isi 'X'
    papan[1][1] = 'O'; :Kotak baris kedua kolom kedua kita isi 'O'.
    papan[2][2] = 'X'; :Kotak baris ketiga kolom ketiga kita isi 'X'.

    // Tampilkan papan
    System.out.println("Status Papan:"); :menunjukkan bahwa program akan menampilkan status papan.
    tampilkanPapan(papan); :memanggil metode tampilkanPapan untuk menampilkan papan
}

public static void tampilkanPapan(char[][] papan) { :Mendefinisikan metode tampilkanPapan yang menerima papan sebagai parameter dan menampilkannya ke konsol.
    for (int i = 0; i < 3; i++) { : pakai perulangan penempatannya lagi buat ngatur baris dan kolomnya
        for (int j = 0; j < 3; j++) {
            System.out.print(papan[i][j] + " ");:di dalam perulangan, menampilkan isi kotak papanbaris i kolom j ke layar.
Setiap selesai satu baris, kami pindah baris } System.out.println(); } } }