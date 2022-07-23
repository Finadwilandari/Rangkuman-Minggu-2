# finadwi
Javascript adalah bahasa pemrograman yang dirancang untuk berjalan di jendela browser.

Alat-alat yang digunakan untuk belajar javascript yaitu:
    web browser; google chrome, firefox dll
    teks editor; Vs Code

Untuk melihat hasil run dari javascript, kita dapat menggunakan console.
    didalam console, kita bisa menulis fungsi atau kode-kode javascript dan hasilnya langsung ditampilkan.
contohnya:
    console.log("Hello World");
    Hello world
    <undefined

    alert("kami disini");
    <undefined

Jika menggunakan Nodejs, maka cara untuk mengakses console adalah dengan mengetik perintah "node" pada terminal.
contohnya:
  Node
  console.log("Hello world")
  Hello world
  <undefined

  var nama = "fina dwi";
  <undefined

  console.log("Nama saya" + nama);
  Nama saya fina dwi 
  <undefined

Artinya, console bisa digunakan untuk menguji coba fungsi atau kode javascript dan untuk melihat pesan error saat debugging program.

Ada beberapa cara menulis kode javascript didalam HTML:
>Embed yaitu kode javascript ditempel langsung pada HTML
>Inline yaitu kode javascript ditulis pada atribut HTML
>Eksternal yaitu kode javascript ditulis terpisah dengan file HTML


Variabel adalah nama yang mewakili sebuah nilai seperti "string" yaitu teks, "number" yaitu angka, array, object dll.
    membuat variabel yang umum digunakan di javascript yaitu menggunakan kata kunci "var" lalu diikuti dengan nama variabel serta nilainya
contohnya:
    var title = "mari belajar javascript";
contoh di atas artinya kita membuat variabel bernama "title" dengan nilai berupa teks "string" yaitu "mari belajar javascript"

    selain "var", kita juga bisa menggunakan kata kunci "let"
contohnya:
// membuat variabel dengan kata kunci let
let price = 20000;

jika nilai variabel tidak diisi, maka variabel akan bernilai undefined atau belum ditentukan.
    untuk menampilkan isi variabel, kita bisa menggunakan beberapa fungsi ini untuk menghasilkan outputnya:
console.log() yaitu menampilkan output ke console javascript
document.write() yaitu menampilkan output ke dokumen HTML
alert() yaitu menampilkan output ke jendela dialog

Ada beberapa tipe data dalam javascript yaitu:
    string atau teks;
    integer atau number atau bilangan bulat;
    float atau bilangan pecahan;
    Boolean;
    object;

Adapun aturan penulisan nama variabel javascript yaitu:
    penamaan variabel tidak boleh menggunakan angka didepannya;
    penamaan variabel bisa mengguanakan awal underscore;
    penamaan variabel bisa menggunakan camelcase apabila terdiri dari dua suku kata;
    penamaan variabel bisa menggunakan bahasa inggris;

Salah satu tugas utama javascript adalah membuat halaman web agar terlihat dinamis, dan hal ini bisa dilakukan oleh javascript dengan menggunakan DOM.
    DOM yaitu "Document Object Model" yang artinya dokumen HTML yang dimodelkan dalam sebuah objek.
    objek dari dokumen ini pun menyediakan beberapa fungsi dan attribut yang bisa digunakan dalam membuat program javascript yang biasa disebut dengan API atau "Application Programming Interface".
objek "document" adalah model dari dokumen HTML. objek ini berisi kumpulan fungsi dan attribut berupa objek dari elemen HTML.
contohnya:
    objek <head> dan <body>
    // mengakses objek head
    document.head;

    //mengakses objek body
    document.body;

Jika kita ingin mengakses elemen spesifik, ada beberapa fungsi yang bisa digunakan:
getElementById() yaitu fungsi untuk memilih elemen berdasarkan attribut id;
getElementByName() yaitu fungsi untuk memilih elemen berdasarkan attribut name;
getElementByClassName() yaitu fungsi untuk memilih elemen berdasarkan atrribut class;
getElementByTagName() yaitu fungsi untuk memilih elemen berdasarkan atrribut nama tag;
querySelector() yaitu fungsi untuk memilih elemen berdasarkan query;
querySelectorAll() yaitu fungsi untuk memilih elemen berdasarkan query;
contohnya:
    <div id="biodata"></div>
maka untuk memilih elemen tersebut kita menggunakan fungsi getElementById
        // memilih elemen dengan id Biodata
        var Biodata = getElementById("Biodata")

Elemen yang terpilih akan menjadi sebuah array.
Array tersebut akan berisi objek DOM dari elemen yang terpilih.

DOM sendiri menyediakan fungsi untuk membuat elemen HTML, salah satunya:
        reateElement()
contohnya:
        document.createElement("p");

Ada tiga macam jendela dialog pada javascript yaitu:
        jendela dialog alert(); digunakan untuk menampilkan sebuah pesan peringatan atau informasi.
    contohnya:
        fungsi alert() berada dalam objek window:
        window.alert("Hello world");

        jendela dialog confirm(); digunakan untuk melakukan konfirmasi saat melakukan tindakan tertentu
    contohnya: confirm("apakah anda yakin?");
    disini dialog confirm akan mengembalikan nilai true jika kita memilih tombol Ok dan akan mengembalikan nilai false jika kita memilih tombol cancel. 
        
        jendela dialog promp(); digunakan untuk mengambil sebuah inputan dari pengguna.

Terdapat beberapa bentuk percabangan di javascript yaitu:
        if merupakan percabangan yang hanya memiliki satu blok pilihan saat kondisi bernilai benar;
        if/else merupakan percabangan yang memiliki dua blok pilihan;
        if/else/if merupakan percabangan yang memiliki lebih dari dua blok pilihan;

kode Loop atau perulangan pada javascript maksudnya adalah dimana perulangan akan membantu kita mengeksekusi kode yang berulang-ulang sebanyak yang kita ingin.
perulangan Counted Loop:
    for;
    foreach;
    repeat;
perulangan Uncounted Loop:
    while;
    Do/While;

Array merupakan struktur data yang digunakan untuk menyimpan sekumpulan data dalam satu tempat.
    Setiap data dalam Array memiliki indeks, sehingga kita akan mudah memprosesnya.
    index array selalu dimulai dari angka ("0")

Ada 4 cara yang bisa kita lakukan untuk membuat fungsi di Javascript:
    Menggunakan cara biasa;
    Menggunakan ekspresi;
    Menggunakan tanda panah (=>);
    Menggunakan Constructor;
Kita bisa memanggil fungsi di dalam kode Javascript dengan menuliskan nama fungsinya seperti ini:
    namaFungsi();
contohnya:
function SayHello() {
    concole.log("Hello world");
}

// memanggil fungsi
sayHello() // lalu akan menghasilkan Hello world

Parameter adalah variabel yang menyimpan nilai untuk diproses di dalam fungsi.
contohnya:
    function kali(a,b) {
        hasilkali = a * b;
        console.log("Hasil kali a*b = " + hasilkali);
    }
    a dan b adalah sebuah parameter.

Agar hasil pengolahan nilai di dalam fungsi dapat digunakan untuk proses berikutnya, maka fungsi harus mengembalikan nilai.
    Pengembalian nilai pada fungsi menggunakan kata kunci "return" kemudian diikuti dengan nilai atau variabel yang akan dikembalikan.
contohnya:
function bagi(a,b){
    hasilBagi = a / b;
    return hasilBagi;
}

// memanggil fungsi
var nilai1 = 20;
var nilai2 = 5;
var hasilPembagian = bagi(nilai1, nilai2);

console.log(hasilPembagian); //-> 4

