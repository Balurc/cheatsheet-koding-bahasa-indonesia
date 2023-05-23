## Python
- Python adalah bahasa pemrograman tingkat tinggi yang didesain untuk menjadi mudah dibaca dan ditulis.
- Python juga merupakan bahasa berorientasi objek, berorientasi modul, dan bahasa skrip.
- Dalam Python, segala sesuatu dianggap sebagai objek.
- Sebuah file Python memiliki ekstensi .py.
- Python menggunakan indentasi untuk memisahkan blok kode, bukan menggunakan kurung kurawal ({}) seperti bahasa pemrograman lainnya.
- Anda dapat menjalankan file Python dengan menggunakan perintah berikut di cmd (Windows) atau shell (Mac/Linux):
`python <namafile.py>` atau `python3 <namafile.py>`


## Cara membuat dan mengeksekusi program
1. Buka terminal/cmd
2. Buat programnya: nano/cat > nama_program.py
3. Tulis programnya dan simpan
4. Jalankan program dengan perintah: python nama_program.py


## Sintaks dasar
- Komentar menggunakan tanda `#` : `# Ini adalah komentar`
- Indentasi menggunakan spasi atau tab.
- Mengakhiri pernyataan tidak memerlukan tanda titik koma (`;`).
- Deklarasi variabel : `nama_variabel = nilai`.


## Tipe data dasar

| Tipe Data |            Keterangan            |
|:---------:|:--------------------------------:|
| int       | Nilai integer : 0, 1, -2, 3       |
| float     | Nilai decimal : 0.1, 4.03, -5.123 |
| char      | Karakter : a, b, @, !, `          |
| str       | String : abc, AbC, A@B, sd!, `asa |
| bool      | Nilai boolean : True, False       |
| complex   | Bilangan complex : 2+3j, 4-1j     |


## Kata Kunci

| **Kata Kunci** |                                        **Keterangan**                                       |       **Kategori**       |
|:--------------:|:-------------------------------------------------------------------------------------------:|:------------------------:|
|      True      |                               Nilai boolean untuk True atau 1                               |     Kata kunci Value     |
|      False     |                               Nilai boolean untuk False atau 0                              |     Kata kunci Value     |
|      None      |                                       Tidak ada nilai                                       |     Kata kunci Value     |
|       and      |     Mengembalikan nilai true jika kedua (operand) bernilai true (dalam sintaks lain: &&)    |    Kata kunci Operator   |
|       or       | Mengembalikan nilai true jika salah satu dari operand bernilai true (dalam bahasa lain: \|) |                          |
|       in       |                   Mengembalikan nilai true jika kata ada didalam iterator                   |    Kata kunci Operator   |
|       is       |                        Mengembalikan nilai true jika id variabel sama                       |    Kata kunci Operator   |
|       not      |                        Mengembalikan nilai boolean yang berkebalikan                        |    Kata kunci Operator   |
|       if       |                    Masuk ke blok percabangan jika ekspresi bernilai true                    |        Percabangan       |
|      elif      |                         Digunakan untuk lebih dari 1 pemeriksaan if                         |        Percabangan       |
|      else      |                     Blok ini akan dieksekusi jika kondisi bernilai false                    |        Percabangan       |
|       for      |                                  Digunakan untuk perulangan                                 |        Perulangan        |
|      while     |                                  Digunakan untuk perulangan                                 |        Perulangan        |
|      break     |                                    Keluar dari perulangan                                   |        Perulangan        |
|    continue    |                                Lewati untuk kondisi tertentu                                |        Perulangan        |
|       def      |                           Membuat fungsi yang ditentukan pengguna                           |         Struktur         |
|      class     |                            Membuat kelas yang ditentukan pengguna                           |         Struktur         |
|     lambda     |                                  Membuat fungsi tanpa nama                                  |         Struktur         |
|      with      |                    Menjalankan kode dalam ruang lingkup pengelola konteks                   |         Struktur         |
|       as       |                                Memberikan alias untuk sesuatu                               |         Struktur         |
|      pass      |                     Digunakan untuk membuat struktur kosong (deklarasi)                     |         Struktur         |
|     return     |                      Mendapatkan nilai dari fungsi, keluar dari fungsi                      |     Kata kunci Return    |
|      yield     |            Menghasilkan nilai-nilai sebagai pengganti return (disebut generator)            |     Kata kunci Return    |
|     import     |                               Impor libraries/modules/packages                              |          Import          |
|      from      |                       Import fungsi/kelas tertentu dari modul/package                       |          Import          |
|       try      |                            Blok ini akan dicoba untuk dieksekusi                            |    Exception handling    |
|     except     |                   Akan dieksekusi jika ada eksepsi/kesalahan yang terjadi                   |    Exception handling    |
|     finally    |              Akan dieksekusi tanpa memperhatikan apakah ada eksepsi atau tidak              |    Exception handling    |
|      raise     |                            Menampilkan eksepsi/kesalahan tertentu                           |    Exception handling    |
|     assert     |                    Menampilkan AssertionError jika kondisi bernilai false                   |    Exception handling    |
|      async     |             Digunakan untuk mendefinisikan fungsi/fungsi co-routine asynchronous            | Asynchronous programming |
|      await     |              Digunakan untuk menunjukkan titik di mana kendali diambil kembali              | Asynchronous programming |
|       del      |                    Menghapus/menghilangkan data yang ditentukan pengguna                    |         Variable         |
|     global     |             Digunakan untuk mengakses variabel yang didefinisikan di luar fungsi            |         Variable         |
|    nonlocal    |                         Mengubah variabel dari cakupan yang berbeda                         |         Variable         |


## Operator

| **Operator** |                                 **Keterangan**                                 |
|:------------:|:------------------------------------------------------------------------------:|
| ( )          | tanda kurung untuk pengelompokan, pemanggilan fungsi, deklarasi tuple, dll     |
| [ ]          | indeks array, juga untuk deklarasi list, dll                                   |
| !            | negasi relasional, komplement, ! menghasilkan true atau false                  |
| ~            | negasi bitwise, komplement satu, ~a                                            |
| -            | minus unary, -a                                                                |
| +            | plus unary, +a                                                                 |
| *            | perkalian, a * b                                                               |
| /            | pembagian, a / b                                                               |
| %            | modulo, a % b                                                                  |
| +            | penjumlahan, a + b                                                             |
| -            | pengurangan, a - b                                                             |
| <<           | geser kiri, operand kiri digeser ke kiri sebanyak bit operand kanan (kali 2)   |
| >>           | geser kanan, operand kiri digeser ke kanan sebanyak bit operand kanan (bagi 2) |
| <            | kurang dari, hasilnya true atau false, a < b                                   |
| <=           | kurang dari atau sama dengan, hasilnya true atau false, a <= b                 |
| >            | lebih dari, hasilnya true atau false, a > b                                    |
| >=           | lebih dari atau sama dengan, hasilnya true atau false, a >= b                  |
| ==           | sama dengan, hasilnya true atau false, a == b                                  |
| !=           | tidak sama dengan, hasilnya true atau false, a != b                            |
| &            | bitwise dan, a & b                                                             |
| ^            | bitwise XOR (eksklusif atau), a ^ b                                            |
| \|           | bitwise or, a \| b                                                             |
| &&, and      | relasional and, hasilnya true atau false, a < b && c >= d                      |
| \|\|, or     | relasional or, hasilnya true atau false, a < b \|\| c >= d                     |
| =            | simpan atau penugasan                                                          |
| +=           | tambah dan simpan                                                              |
| -=           | kurangi dan simpan                                                             |
| *=           | kali dan simpan                                                                |
| /=           | bagi dan simpan                                                                |
| %=           | modulo dan simpan                                                              |
| <<=          | geser kiri dan simpan                                                          |
| >>=          | geser kanan dan simpan                                                         |
| &=           | bitwise and dan simpan                                                         |
| ^=           | bitwise eksklusif or dan store                                                 |
| \|=          | bitwise or dan store                                                           |
| ,            | pemisah seperti dalam (y = x, z = ++x)                                         |


## Struktur data dasar

### List
- Digunakan untuk menyimpan kumpulan elemen yang terurut. 
- Merupakan salah satu struktur data yang paling sering digunakan dalam Python karena fleksibilitas dan kemampuannya untuk mengelola kumpulan data.
- List dapat dibuat dengan menggunakan tanda kurung siku `[ ]` dan dapat menyimpah tipe data berbeda.

  Contoh : `my_list = [1, 2, 3, "empat", True]`.
- Anda dapat mengakses elemen dalam list dengan menggunakan indeksnya. Indeks dimulai dari 0 untuk elemen pertama, 1 untuk elemen kedua, dan seterusnya.

  Contoh : `print(my_list[0])   # Output: 1` & `print(my_list[3])   # Output: "empat"`.
- List juga dapat dibuat dengan konstruktor `list()`.

  Contoh : `buah = list(("apel", "pisang", "mangga"))  # gunakan braket kurung dobel`.
- Mengubah elemen berdasarkan indeks : `my_list[indeks] = nilai_baru`.
- Menambahkan elemen di akhir list : `my_list.append(elemen_baru)`.
- Menambahkan elemen pada indeks tertentu : `my_list.insert(indeks, elemen_baru)`.
- Menghapus elemen berdasarkan indeks : `del my_list[indeks]`.
- Menghapus elemen dengan nilai tertentu : `my_list.remove(elemen)`.
- Menghapus dan mengembalikan elemen terakhir : `elemen_terakhir = my_list.pop()`.
- Menghapus dan mengembalikan elemen pada indeks tertentu : `elemen = my_list.pop(indeks)`.
- Menggabungkan dua list : `list_gabungan = list1 + list2`.
- Mengulang elemen list : `list_ulang = my_list * jumlah_ulang`.
- Menghitung panjang list : `panjang_list = len(my_list)`.
- Mengurutkan list : `my_list.sort()`.
- Mencari indeks elemen : `indeks = my_list.index(elemen)`.
- Menghitung jumlah kemunculan elemen : `jumlah_kemunculan = my_list.count(elemen)`.


### Dictionary
- Dictionary adalah struktur data yang digunakan untuk menyimpan pasangan kunci-nilai (key-value pairs). 
- Dalam dictionary, kunci (key) harus unik dan digunakan untuk mengakses nilai-nilai yang terkait.
- Cara membuat dictionary adalah dengan menggunakan `{}`. Contoh : `my_dict = {} # dictionary kosong`. Cara lain adalah menggunakan konstruktor `dict()`.
- Membuat dictionary dengan pasangan kunci-nilai : `my_dict = {kunci1: nilai1, kunci2: nilai2, kunci3: nilai3}`.
- Cara mengakses nilai berdasarkan kunci : `nilai = my_dict[kunci1] # output nilai1`.
- Mengubah nilai berdasarkan kunci : `my_dict[kunci] = nilai_baru`.
- Menambahkan pasangan kunci-nilai baru : `my_dict[kunci_baru] = nilai_baru`.
- Menghapus pasangan kunci-nilai berdasarkan kunci : `del my_dict[kunci]`.
- Menghapus semua pasangan kunci-nilai dalam dictionary : `my_dict.clear()`.
- Menghitung panjang dictionary (jumlah pasangan kunci-nilai) : `panjang_dict = len(my_dict)`.
- Mendapatkan daftar semua kunci dalam dictionary : `daftar_kunci = list(my_dict.keys())`.
- Mendapatkan daftar semua nilai dalam dictionary : `daftar_nilai = list(my_dict.values())`.
- Mengembalikan daftar tuple pasangan kunci-nilai dalam dictionary : `daftar_pasangan = list(my_dict.items())`.


### Tuple
- Tuple adalah tipe data yang mirip dengan list, namun dengan perbedaan utama yaitu tuple bersifat tidak dapat diubah atau immutable.
- Setelah sebuah tuple dibuat, elemen-elemennya tidak dapat ditambahkan, diubah, atau dihapus.
- Tuple biasanya digunakan dalam situasi ketika kita ingin menyimpan kumpulan elemen yang tetap dan tidak berubah sepanjang waktu. 
- Tuple dideklarasikan dengan menggunakan tanda kurung `()` atau tanpa tanda kurung. Contohnya:
  
  `my_tuple = (elemen1, elemen2, elemen3)`
  
  `my_tuple = elemen1, elemen2, elemen3  # Tanpa tanda kurung`
 - Elemen-elemen tuple dapat berupa objek dengan tipe data yang berbeda, seperti angka, string, tuple lain, atau objek lainnya.
 - Satu-satunya operasi yang dapat dilakukan pada tuple adalah mengakses elemennya. Elemen di tuple dapat diakses menggunakan indeks, mirip dengan list. Indeks dimulai dari 0. Contohnya:

    `my_tuple = ('a', 'b', 'c')`
  
    `print(my_tuple[0])  # Output: 'a'`
    

### Set
- Set adalah koleksi tidak berurutan dari elemen-elemen unik. 
- Di dalam set, tidak ada elemen duplikat.
- Set adalah tipe data yang mutable, artinya Anda dapat menambahkan atau menghapus elemen dari set setelah set tersebut dibuat.
- Set mendukung operasi matematika seperti gabungan, irisan, perbedaan, dan lainnya. Anda dapat melakukan operasi ini pada dua set atau lebih.
- Cara membuat set adalah dengan menggunakan `{}`. Contoh : `my_set = {} # set kosong`. Cara lain adalah menggunakan konstruktor `set()`. Contoh lainnya:

  `my_set = {1, 2, 3, 4, 5}`
- Cara menambahkan elemen ke set : `my_set.add(6)`.
- Cara menghapus elemen dari set : `my_set.remove(3)`.
- Operasi gabungan set : 

  `set1 = {1, 2, 3}`
  
  `set2 = {3, 4, 5}`
  
  `union_set = set1 | set2 # output: {1,2,3,4,5}`
- Operasi irisan set : `intersection_set = set1 & set2 # output {3}`.
- Operasi perbedaan set : `difference_set = set1 - set2 # output {1,2}`.

## Manipulasi String

## Conditional (Percabangan)

## Loop (Perulangan)

## Try-except (Penanganan eksepsi)

## Function








  
  











