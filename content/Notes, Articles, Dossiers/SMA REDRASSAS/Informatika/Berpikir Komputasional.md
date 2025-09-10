https://visualgo.net/en
# Definisi
**Berpikir Komputasional** -> Menyelesaikan masalah dengan efisien dan optimal.

## Struktur Data
**Data** -> Fakta yang belum diolah dan dapat diinterpretasikan sebagai informasi.
**Struktur Data** -> Cara mengorganisi data dengan rapi dan terurut sehingga mudah dipahami.

## AADP
A -> Abstraksi -> Fokus pada hal-hal esensial dan emengesampingkan hal-hal yang tidak relevan. Tujuannya adalah optimalisasi dan efisiensi.
A -> Algoritma -> Merancang langkah-langkah runut dari suatu penyelesaian masalah se-efisien dan optimal mungkin. Harus memiliki awal dan akhir.
D -> Dekomposisi -> Memecah masalah kompleks ke masalah kecil yang bisa dikelola dan dikerjakan bertahap. "Divide and Conquer".
P -> Pattern Recognition -> Melihat dan mengenali pola dari masalah serupa yang dapat digunakan untuk menyelesaikan masalah lainnya yang mirip.

# Jenis-Jenis Struktur Data
## Array/Larik
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **larik** ([bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"): _array_) adalah suatu [tipe data](https://id.wikipedia.org/wiki/Tipe_data "Tipe data") terstruktur yang dapat menyimpan banyak [data](https://id.wikipedia.org/wiki/Data "Data") dengan suatu nama (homogen) yang sama dan menempati tempat di [memori](https://id.wikipedia.org/wiki/Memori "Memori") yang berurutan ([kontigu](https://id.wikipedia.org/w/index.php?title=Kontigu&action=edit&redlink=1 "Kontigu (halaman belum tersedia)")) serta bertipe data sama pula.

Larik dapat diakses berdasarkan [indeksnya](https://id.wikipedia.org/wiki/Indeks "Indeks"). Indeks larik umumnya dimulai dari 0 dan ada pula yang dimulai dari angka bukan 0. Pengaksesan larik biasanya dibuat dengan menggunakan perulangan (_looping_).

![[Pasted image 20250910205144.png]]
## Linked List
**Senarai berantai** atau **daftar bertaut** ([bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"): _linked list_) dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer") merupakan sebuah [struktur data](https://id.wikipedia.org/wiki/Struktur_data "Struktur data") yang digunakan untuk menyimpan sejumlah objek data biasanya secara terurut sehingga memungkinkan penambahan, pengurangan, dan pencarian atas [unsur](https://id.wikipedia.org/wiki/Elemen "Elemen") data yang tersimpan dalam senarai dilakukan secara lebih efektif. Pada praktiknya sebuah struktur data memiliki unsur yang digunakan untuk saling menyimpan rujukan antara satu dengan lainnya sehingga membentuk sebuah senarai abstrak, tiap-tiap unsur yang terdapat pada senarai abstrak ini sering kali disebut sebagai _node_. karena mekanisme rujukan yang saling terkait inilah disebut sebagai senarai berantai.

[![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6d/Singly-linked-list.svg/408px-Singly-linked-list.svg.png)](https://id.wikipedia.org/wiki/Berkas:Singly-linked-list.svg)  
_Sebuah senarai berantai dengan tiap-tiap node yang terdiri atas dua unsur, data integer, dan unsur rujukan ke node berikutnya_

Senarai berantai merupakan bentuk struktur data paling umum dan sederhana yang banyak digunakan untuk mengimplementasikan model struktur data lainnya, termasuk antrian, _stack_, ataupun [larik](https://id.wikipedia.org/wiki/Array "Array") asosiatif.
## Stack
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **tumpukan** ([bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"): _stack_) merupakan sebuah koleksi objek yang menggunakan prinsip _**LIFO**_ (_**Last In First Out**_), yaitu data yang terakhir kali dimasukkan akan pertama kali keluar dari tumpukan tersebut. Operasi untuk memasukkan data biasa disebut _push_ dan operasi untuk mengeluarkan biasanya disebut _pop_. Tumpukan dapat diimplementasikan sebagai [senarai berantai](https://id.wikipedia.org/wiki/Senarai_berantai "Senarai berantai") atau [larik](https://id.wikipedia.org/wiki/Larik "Larik"). Tumpukan tergolong [struktur data linear](https://id.wikipedia.org/w/index.php?title=Struktur_data_linear&action=edit&redlink=1 "Struktur data linear (halaman belum tersedia)") dan operasi _push_ dan _pop_ hanya bisa dilakukan di satu ujung struktur yang biasa disebut _top_ dari tumpukan. Untuk melihat data yang ada di top tanpa mengeluarkannya, biasanya dilakukan menggunakan operasi _peek_.
![[Pasted image 20250910210738.png]]
## Queue
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **antrean** adalah koleksi dari data-data yang memiliki urutan dan hanya bisa diubah dengan menambahkan data di satu ujung dan mengeluarkan data di ujung lainnya. Biasanya, ujung di mana elemen bisa ditambahkan disebut _back_, _tail_, atau _rear_ dari antrean sementara ujung di mana elemen bisa dikeluarkan disebut _head_ atau _front_ dari antrean, mirip dengan kata-kata yang digunakan apabila orang-orang berbaris dalam antrean.

Operasi menambahkan elemen ke _rear_ dari antrean biasanya disebut _enqueue_ sementara operasi mengeluarkan elemen dari _fron_ biasanya disebut _dequeue_. Operasi-operasi lain yang biasa dilakukan di antaranya adalah operasi _peek_ atau _front_ yang digunakan untuk melihat elemen terdepan dari antrean tanpa mengeluarkannya.

Operasi-operasi yang mendefinisikan antrean membuatnya tergolong sebagai [struktur data _first-in-first-out_ (FIFO)](https://id.wikipedia.org/wiki/FIFO "FIFO"). Karena memenuhi struktur data FIFO, elemen pertama yang dimasukkan ke antrean akan menjadi yang pertama dikeluarkan. Antrean juga merupakan contoh [struktur data linear](https://id.wikipedia.org/w/index.php?title=Struktur_data_linear&action=edit&redlink=1 "Struktur data linear (halaman belum tersedia)"). Antrean biasa digunakan dalam program komputer, biasanya diimplementasikan menggunakan _[circular buffer](https://id.wikipedia.org/w/index.php?title=Circular_buffer&action=edit&redlink=1 "Circular buffer (halaman belum tersedia)")_ dan [senarai berantai](https://id.wikipedia.org/wiki/Senarai_berantai "Senarai berantai").

Antrean biasa digunakan dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), [transportasi](https://id.wikipedia.org/wiki/Transportasi "Transportasi"), dan [riset operasi](https://id.wikipedia.org/wiki/Riset_operasi "Riset operasi") di mana terdapat entitas-entitas seperti data, objek, orang, atau kejadian yang perlu disimpan untuk diproses kemudian. Dalam konteks tersebut, antrean melakukan pekerjaan dari [_buffer_](https://id.wikipedia.org/w/index.php?title=Buffer_\(ilmu_komputer\)&action=edit&redlink=1 "Buffer (ilmu komputer) (halaman belum tersedia)"). Penggunaan lain dari antrean adalah dalam implementasi _[breadth-first search](https://id.wikipedia.org/w/index.php?title=Breadth-first_search&action=edit&redlink=1 "Breadth-first search (halaman belum tersedia)")_.
![](https://www.visiontron.com/wp-content/uploads/lines-02-1.png)
## Binary Search Tree
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), sebuah **pohon pencarian biner** (PPB) atau **pohon biner terurut** adalah sebuah [pohon biner](https://id.wikipedia.org/wiki/Pohon_biner "Pohon biner") yang memiliki sifat-sifat berikut:

- Setiap [simpul](https://id.wikipedia.org/wiki/Pohon_\(struktur_data\)#Simpul_\(node\) "Pohon (struktur data)") (_node_) memiliki sebuah nilai.
- Sebuah [susunan total](https://id.wikipedia.org/w/index.php?title=Susunan_total&action=edit&redlink=1 "Susunan total (halaman belum tersedia)") ditentukan dalam nilai ini.
- [Sub pohon](https://id.wikipedia.org/wiki/Pohon_\(struktur_data\)#Sub_pohon_\(Subtrees\) "Pohon (struktur data)") (_subtree_) kiri dari sebuah simpul hanya memuat nilai lebih kecil dari nilai simpul.
- Sub pohon kanan dari sebuah simpul hanya memuat nilai lebih besar atau sama dengan nilai dari simpul.

Kelebihan utama dari pohon pencarian biner adalah keterkaitannya dengan [algoritme pengurutan](https://id.wikipedia.org/w/index.php?title=Algoritme_pengurutan&action=edit&redlink=1 "Algoritme pengurutan (halaman belum tersedia)") dan [algoritme pencarian](https://id.wikipedia.org/wiki/Algoritme_pencarian "Algoritme pencarian") yang dapat lebih efisien, seperti _[in-order traversal](https://id.wikipedia.org/w/index.php?title=In-order_traversal&action=edit&redlink=1 "In-order traversal (halaman belum tersedia)")_.

Pohon pencarian biner adalah sebuah struktur data dasar yang digunakan untuk membentuk struktur data yang lebih abstrak seperti [set](https://id.wikipedia.org/w/index.php?title=Struktur_data_set&action=edit&redlink=1 "Struktur data set (halaman belum tersedia)"), [multiset](https://id.wikipedia.org/w/index.php?title=Multiset&action=edit&redlink=1 "Multiset (halaman belum tersedia)"), dan [array asosiatif](https://id.wikipedia.org/w/index.php?title=Array_asosiatif&action=edit&redlink=1 "Array asosiatif (halaman belum tersedia)").

Jika PPB memperkenankan nilai-nilai duplikat, maka PPB merupakan sebuah multiset. Pohon jenis ini menggunakan ketaksamaan longgar (_non-strict inequalities_), sehingga semua yang berada di subpohon bagian kiri dari sebuah node adalah lebih kecil atau sama dengan nilai dari node, dan semua yang berada di subpohon bagian kanan dari node adalah lebih besar atau sama dengan nilai dari node.

Jika PPB tidak memperkenankan nilai-nilai duplikat, maka PPB merupakan sebuah set dengan nilai-nilai unik, sama seperti set pada matematika (himpunan). Pohon tanpa nilai-nilai duplikat menggunakan ketaksamaan kaku (_strict inequalities_), artinya subpohon kiri dari sebuah node hanya memuat node-node dengan nilai yang lebih kecil dari nilai node, dan subpohon kanan hanya memuat nilai-nilai yang lebih besar.

Beberapa definisi PPB menggunakan sebuah ketaksamaan longgar hanya pada satu sisi, sehingga nilai-nilai duplikat diperkenankan. Walaupun demikian, definisi-definisi PPB tersebut membatasi dengan baik bagaiman sebuah pohon dengan banyak nilai duplikat dapat diseimbangkan.
### Mekanisme
#### Pencarian

Pencarian sebuah nilai tertentu pada pohon biner adalah sebuah proses yang dapat dilakukan secara rekursif karena nilai-nilai yang disimpan adalah terurut. Pencarian dimulai dengan memeriksa akar (_root_). Jika nilai yang dicari sama dengan akar, maka nilai ditemukan. Jika nilai yang dicari kurang dari akar, maka pencarian dilakukan terhadap subpohon kiri, sehingga kita secara rekursif mencari subpohon kiri dengan cara yang sama. Jika nilai yang dicari lebih besar dari akar, maka pencarian dilakukan terhadap subpohon kanan sehingga kita secara rekursif mencari subpohon kanan dengan cara yang sama. Jika kita mencapai sebuah ujung (_leaf_) dan belum menemukan yang dicari, maka nilai tersebut tidak ada dalam pohon. Sebuah pembandingan dapat dibuat dengan [pencarian biner](https://id.wikipedia.org/wiki/Pencarian_biner "Pencarian biner"), yang beroperasi hampir mirip degan pengaksesan acak pada sebuah array.
#### Penyisipan

Penyisipan dimulai sebagaimana sebuah pencarian dilakukan. Jika akar tidak sama dengan nilai sisipan, kita mencari subpohon kiri atau kanan seperti di atas. Pada suatu saat kita akan mencapai sebuah node luar dan menambahkan nilai sisipan sebagai anak kiri atau anak kanan, bergantung pada nilai node. Dengan kata lain, kita memeriksa akar dan secara rekursif menyisipkan node yang baru ke subpohon kiri jika nilai yang baru lebih kecil atau sama dengan akar, atau menyisipkan ke subpohon kanan jika nilai yang baru lebih besar dari root.
#### Penghapusan

Ada kasus-kasus yang mesti diperhatikan:

- **Penghapusan sebuah ujung:** Penghapusan sebuah node tanpa anak adalah mudah, cukup menghilangkanya dari pohon.
- **Penghapusan sebuah node dengan satu anak:** Menghapusnya dan mengganti dengan anaknya.
- **Penghapusan sebuah node dengan dua anak:** Misalkan node yang akan dihapus adalah _N_. Kita ganti nilai dari N dengan suksesor _in-order_ (anak terkiri dari subpohon kanan) atau dengan predesesor _in-order_ (anak terkanan dari subpohon kiri).
### Graph
Graph adalah jenis [struktur data](https://www.trivusi.web.id/2022/06/mengenal-struktur-data.html) umum yang susunan datanya tidak berdekatan satu sama lain (non-linier). Graph terdiri dari kumpulan simpul berhingga untuk menyimpan data dan antara dua buah simpul terdapat hubungan saling keterkaitan.

Simpul pada graph disebut dengan **verteks (V)**, sedangkan sisi yang menghubungkan antar verteks disebut **edge (E)**. Pasangan (x,y) disebut sebagai edge, yang menyatakan bahwa simpul x terhubung ke simpul y.

![](https://cdn.programiz.com/sites/tutorial2program/files/graph-vertices-edges_0.png)


Graph di atas terdiri atas 4 buah verteks dan 4 pasang sisi atau edge. Dengan verteks disimbolkan sebagai V, edge dilambangkan E, dan graph disimbolkan G, ilustrasi di atas dapat ditulis dalam notasi berikut:

`**V = {0, 1, 2, 3}**`

`**E = {(0,1), (0,2), (0,3), (1,2)}**`

`**G = {V, E}**`

# Algoritma
Dalam [matematika](https://id.wikipedia.org/wiki/Matematika "Matematika") dan [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **algoritma** adalah rangkaian terbatas dari instruksi-instruksi yang rumit, biasanya digunakan untuk menyelesaikan atau menjalankan suatu kelompok masalah [komputasi](https://id.wikipedia.org/wiki/Komputasi "Komputasi") tertentu. Algoritma digunakan sebagai spesifikasi untuk melakukan perhitungan dan pemrosesan [data](https://id.wikipedia.org/wiki/Data "Data"). Algoritma yang lebih mutakhir dapat melakukan [deduksi](https://id.wikipedia.org/wiki/Deduksi "Deduksi") otomatis (disebut sebagai penalaran otomatis) dan menggunakan tes matematis dan logis untuk mengarahkan eksekusi kode melalui berbagai rute (disebut sebagai pengambilan keputusan otomatis). Penggunaan karakteristik manusia sebagai deskriptor mesin secara metaforis telah dipraktikkan oleh [Alan Turing](https://id.wikipedia.org/wiki/Alan_Turing "Alan Turing") dengan terminologi seperti "memory", "search" dan "stimulus".

Kata algoritma berasal dari nama matematikawan [Persia](https://id.wikipedia.org/wiki/Persia "Persia") abad ke-9, [Muḥammad bin Mūsā al-Khwārizmī](https://id.wikipedia.org/wiki/Mu%E1%B8%A5ammad_bin_M%C5%ABs%C4%81_al-Khaw%C4%81rizm%C4%AB "Muḥammad bin Mūsā al-Khawārizmī"), yang [nisbah](https://id.wikipedia.org/wiki/Nisbah "Nisbah")-nya (yang mengidentifikasikannya sebagai seseorang yang berasal dari [Khwarezmia](https://id.wikipedia.org/wiki/Khwarezmia "Khwarezmia")) dilatinkan sebagai Algoritmi (bahasa Persia yang diarabkan: الخوارزمی sekitar: 780-850). Namanya bermakna 'yang berasal dari (daerah) [Khwarezmia](https://id.wikipedia.org/wiki/Khwarezmia "Khwarezmia")', sebuah daerah yang dulunya merupakan bagian dari [Iran Raya](https://id.wikipedia.org/wiki/Iran_Raya "Iran Raya") dan sekarang sebagai bagian dari [Uzbekistan](https://id.wikipedia.org/wiki/Uzbekistan "Uzbekistan"). Sekitar tahun 825, Al-Khwarizmi menulis sebuah risalah [berbahasa Arab](https://id.wikipedia.org/wiki/Bahasa_Arab "Bahasa Arab") tentang [sistem angka Hindu-Arab](https://id.wikipedia.org/wiki/Sistem_angka_Hindu-Arab "Sistem angka Hindu-Arab"), yang diterjemahkan ke dalam [bahasa Latin](https://id.wikipedia.org/wiki/Bahasa_Latin "Bahasa Latin") selama abad ke-12. Naskah ini dimulai dengan frasa Dixit Algorizmi ('Maka berkatalah Al-Khwarizmi'), di mana "Algorizmi" di sini adalah [Latinisasi](https://id.wikipedia.org/wiki/Latinisasi "Latinisasi") penerjemah akan nama Al-Khwarizmi. Bukunya yang bernama Aljabar menjadi salah satu buku matematikawan yang paling banyak dibaca di Eropa pada abad pertengahan. Dalam bahasa Latin abad pertengahan, kata _algorismus,_ yang merupakan pengadaptasian dari namanya, menjadi kata yang bermakna "sistem bilangan desimal". Pada abad ke-15, di bawah pengaruh kata Yunani ἀριθμός (arithmos), 'angka' (lih. 'aritmetika'), kata Latin-nya diubah menjadi algorithmus. Dalam [bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"), kata algorithm pertama kali digunakan pada sekitar tahun 1230 dan kemudian oleh [Chaucer](https://id.wikipedia.org/wiki/Geoffrey_Chaucer "Geoffrey Chaucer") pada 1391. Bahasa Inggris mengadopsi istilah tersebut dari [bahasa Prancis](https://id.wikipedia.org/wiki/Bahasa_Prancis "Bahasa Prancis"), akan tetapi baru pada abad ke-19 lah kata "algorithm" mulai memiliki makna seperti sekarang yang ada dalam bahasa Inggris modern.

## Algoritma Deskriptif
Algoritma ini yaitu cara mendeskripsikan atau menjelaskan proses pemecahan masalah dengan langkah-langkah yang jelas dan terperinci. Tujuan utama dari algoritma in yaitu membuat instruksi yang mudah dipahami oleh manusia, sehingga lebih mudah untuk diimplementasikan dalam kode program.

Untuk memberikan gambaran yang lebih jelas, di bawah ini adalah contoh algoritmanya:
*Mulai*
1. **Langkah 1**: Ambil selembar kertas dan pena.
2. **Langkah 2**: Tuliskan masalah yang ingin diselesaikan.
3. **Langkah 3**: Tentukan variabel yang diperlukan.
4. **Langkah 4**: Tuliskan langkah-langkah penyelesaian masalah secara berurutan.
5. **Langkah 5**: Periksa kembali setiap langkah untuk memastikan tidak ada yang terlewat.
*Selesai*
## Algoritma Flowchart
Flowchart atau bagan alur adalah diagram yang menampilkan langkah-langkah dan keputusan untuk melakukan sebuah proses dari suatu program. Setiap langkah digambarkan dalam bentuk diagram dan dihubungkan dengan garis atau arah panah.

Flowchart berperan penting dalam memutuskan sebuah langkah atau fungsionalitas dari sebuah proyek pembuatan program yang melibatkan banyak orang sekaligus. Selain itu dengan menggunakan bagan alur proses dari sebuah program akan lebih jelas, ringkas, dan mengurangi kemungkinan untuk salah penafsiran. Penggunaan flowchart dalam dunia pemrograman juga merupakan cara yang bagus untuk menghubungkan antara kebutuhan teknis dan non-teknis.

![](https://www.conceptdraw.com/How-To-Guide/picture/Designelements-Flowchart.png)


## Algoritma Pseudocode
Istilah pseudocode terdiri dari dua gabungan kata, yaitu kata _pseudo_ yang berarti semu dan kata _code_ yang berarti kode. Pseudocode atau kode semu dapat diartikan sebagai deskripsi dari algoritma pemrograman yang dituliskan secara sederhana dibandingkan dengan sintaksis bahasa pemrograman. Tujuannya, agar lebih mudah dibaca dan dipahami manusia. 

Ia bukanlah sebuah bahasa pemrograman, karena sebuah bahasa pemrograman harus memiliki aturan dalam penulisan kodenya. Sementara pseudocode sendiri tidak memiliki aturan yang spesifik atau baku dalam penulisannya, karena itu ia tidak dikategorikan sebagai bahasa pemrograman.

### Fungsi

Selain agar lebih mudah untuk dipahami oleh manusia khususnya oleh programmer, pseudocode juga memiliki fungsi yang lain. Berikut adalah fungsinya:

- Dapat digunakan sebagai alat untuk dokumentasi.
- Untuk mempermudah proses penerjemahan menjadi suatu bahasa pemrograman.
- Dapat digunakan untuk proses mencari sebuah ide tanpa harus memikirkan implementasi dari suatu bahasa pemrograman khusus.
- Lebih mudah mengembangkan aplikasi yang dibuat.

### Notasi pseudocode

Setelah mengetahui pengertian dan fungsi dari pseudocode, kamu juga harus mengetahui notasi apa saja yang digunakan untuk mengetahui proses yang terjadi. Berikut ini adalah beberapa notasinya.

- **INPUT**  
    Digunakan untuk menunjukan proses memasukan suatu isi variabel.
    
- **OUTPUT**  
    Digunakan untuk menunjukan proses keluaran yang terjadi.
    
- **WHILE**  
    Digunakan untuk sebuah perulangan yang memiliki iterasi awal.
    
- **FOR**  
    Digunakan untuk sebuah perulangan perhitungan iterasi.
    
- **REPEAT – UNTIL**  
    Digunakan untuk sebuah perulangan yang memiliki kondisi akhir.
    
- **IF – THEN – ELSE**  
    Digunakan untuk mengambil sebuah keputusan dari beberapa kondisi.

![](https://dicoding-assets.sgp1.cdn.digitaloceanspaces.com/blog/wp-content/uploads/2021/08/Contoh-pseudocode-ganjil-genap.png)

## Jenis Algoritma Berdasarkan Alur
### Algoritma Sekuensial
Ini merupakan algoritma yang dilakukan secara bertahap dan juga berurutan. Contohnya dapat kita temukan pada kegiatan sehari-hari ketika kita ingin memasak mi. Biasanya, pada bungkus tersebut terdapat langkah-langkah penyajian untuk menghidangkan makanan tersebut.Pada dunia pemrograman, penerapan algoritma ini merupakan penerapan yang krusial. Contoh yang paling sederhana adalah mengambil data dari internet.

Biasanya ketika kita membuka aplikasi sosial media, misalnya Instagram.Aplikasi tersebut akan mengambil data dari _database_ mereka, lalu ditampilkan pada pengguna. Jika kita urutkan, langkah-langkahnya menjadi seperti ini.

- Pengguna membuka aplikasi.
- Aplikasi mengambil data dari _database_.
- Aplikasi menampilkan keterangan “_loading_” ketika data sedang diambil.
- Aplikasi selesai mengambil data dan data ditampilkan pada aplikasi.
### Algoritma Percabangan
Bayangkan kita sedang berbelanja bulanan dan kita memiliki _budget_ belanja sekitar Rp200.000. Ketika berbelanja, tentunya ada banyak sekali barang dengan berbagai macam harga. Pada saat itu juga, kita memilih barang-barang yang akan kita beli. Jika total harga melebihi _budget_ yang ada, kita perlu mengurangi barang belanjaan yang kita bawa.  
  
Tanpa disadari, kita sudah mengetahui cara algoritma percabangan bekerja. Kita menghitung total belanja yang sudah dimiliki, apabila melebihi, kita perlu mengurangi belanjaannya. Jika dituliskan secara sistematis, jadilah seperti ini.  

- Pergi ke tempat belanja.
- Mengambil keranjang belanja.
- Mengisi keranjang belanja.
- Periksa harga barang.
- Jika melebihi _budget_, kurangi barangnya.
- Jika sudah cukup, _checkout_ bisa dilakukan.
### Algoritma Perulangan
Bumi tentunya terus berputar pada porosnya. Dalam dunia astronomi, beberapa fenomena seperti gerhana bulan dan gerhana matahari akan terjadi setiap tahunnya. Kita sebagai manusia juga dapat menghitung waktu terjadinya hal tersebut. Setiap tahunnya, para ilmuwan terus bereksperimen untuk memprediksi waktu terjadinya hal tersebut.
## Penggunaan Algoritma
### Search 
[Algoritma](https://fikti.umsu.ac.id/mengenal-apa-itu-algoritma/) search adalah serangkaian langkah atau instruksi yang digunakan untuk mencari elemen atau informasi tertentu di dalam suatu dataset. Tujuannya adalah untuk menemukan posisi atau keberadaan elemen yang dicari. Dalam pemrograman, algoritma search menjadi salah satu teknik penting dalam menyelesaikan berbagai masalah.

### Jenis-Jenis Algoritma Search

#### 1. Linear Search

Linear Search, atau pencarian linear, adalah algoritma pencarian yang paling sederhana. Ini bekerja dengan cara memeriksa setiap elemen dalam kumpulan data secara berurutan hingga elemen yang dicari ditemukan atau sampai seluruh kumpulan data telah diperiksa.

Contoh Program:

```
def linear_search(arr, target):
for i in range(len(arr)):
if arr[i] == target:
return i
return -1
```

#### 2. Depth First Search (DFS)

Depth First Search (DFS) adalah algoritma pencarian yang digunakan dalam struktur data seperti graf. Ia mengikuti jalur sejauh mungkin sebelum kembali dan mengeksplorasi cabang lain.

Contoh Program DFS:

```
class Graph:
    def __init__(self):
        self.graph = {}

    def add_edge(self, node, neighbor):
        if node not in self.graph:
            self.graph[node] = []
        self.graph[node].append(neighbor)

def dfs(graph, start, visited=[]):
    visited.append(start)
    for neighbor in graph[start]:
        if neighbor not in visited:
            dfs(graph, neighbor, visited)
```

#### 3. Binary Search

Pencarian Binary adalah algoritma pencarian yang efisien digunakan untuk mencari elemen dalam kumpulan data yang sudah terurut. Algoritma ini membagi data menjadi dua bagian dan membandingkan elemen tengah dengan elemen yang dicari.

Contoh Program Pencarian Binary:

```
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1
```

#### 4.Jump Search

Pencarian Jump adalah algoritma pencarian yang efisien digunakan untuk mencari elemen dalam kumpulan data yang sudah terurut. Ia melompati beberapa langkah sekaligus dalam pencarian, memungkinkan efisiensi yang lebih baik daripada pencarian linear.

Contoh Program pencarian Jump:

```
import math

def jump_search(arr, target):
    n = len(arr)
    step = int(math.sqrt(n))
    prev = 0
    while arr[min(step, n)-1] < target:
        prev = step
        step += int(math.sqrt(n))
        if prev >= n:
            return -1
    while arr[prev] < target:
        prev += 1
        if prev == min(step, n):
            return -1
    if arr[prev] == target:
        return prev
    return -1
```

### Penerapan dalam kehidupan sehari hari

Algoritma pencarian memiliki banyak penerapan dalam kehidupan sehari-hari, terutama dalam dunia digital dan teknologi. Berikut ini beberapa contoh penerapannya:

1. Mesin Pencari (Search Engine)  
    Salah satu contoh penerapan yang paling terkenal adalah mesin pencari seperti Google. Ketika melakukan pencarian di mesin pencari, algoritma pencarian di baliknya akan mencari dan mengurutkan halaman web yang paling relevan dengan kata kunci yang masukkan.
2. Pencarian dalam Aplikasi e-Commerce  
    Ketika berbelanja online di platform e-commerce seperti Amazon atau Tokopedia, algoritma pencarian digunakan untuk mencari produk yang sesuai dengan preferensi dan kebutuha. Ini membantu Anda menemukan produk dengan cepat.
3. Sistem Rekomendasi  
    Algoritma pencarian juga digunakan dalam sistem rekomendasi seperti Netflix atau Spotify. Mereka mencari konten atau musik yang sesuai dengan sejarah penelusuran Anda atau preferensi yang telah di tentukan.
4. Pencarian dalam Aplikasi Navigasi  
    Aplikasi navigasi seperti Google Maps menggunakan algoritma pencarian untuk mencari rute tercepat atau alternatif menuju tujuan Anda. Mereka juga dapat menemukan lokasi berdasarkan nama atau alamat yang di masukkan.
5. Pencarian dalam Basis Data  
    Dalam bisnis, algoritma pencarian digunakan dalam pencarian data dalam basis data. Ini membantu perusahaan menemukan informasi yang relevan dari database mereka, seperti mencari catatan pelanggan atau transaksi.

Dalam pemrograman, pemilihan algoritma pencarian yang tepat dapat memengaruhi kinerja program secara signifikan.
### Sorting
Algoritma sorting adalah suatu metode atau teknik untuk mengurutkan data atau elemen-elemen dalam suatu [struktur data](https://fikti.umsu.ac.id/pengertian-fungsitipe-dan-cara-memilih-struktur-data/) secara teratur. Algoritma sorting merupakan salah satu konsep penting dalam pemrograman, tujuannya untuk mengubah data yang tidak teratur menjadi urutan yang teratur, misalnya dari data yang tidak terurut menjadi data yang terurut menaik atau menurun.

### Jenis Algoritma Sorting

### 1. Bubble Sort

Bubble Sort adalah salah satu algoritma sorting yang paling sederhana. Algoritma ini bekerja dengan membandingkan elemen-elemen berpasangan dalam daftar dan menukar mereka jika diperlukan. Proses ini terus berlanjut hingga semua elemen berada dalam urutan yang benar.

### 2. Quick Sort

Quick Sort adalah algoritma yang mengurutkan dengan lebih efisien. Ia membagi daftar menjadi dua bagian, lalu mengurutkan setiap bagian secara terpisah. Kemudian, hasilnya digabungkan untuk mendapatkan daftar yang terurut.

### 3. Merge Sort

Merge Sort juga membagi daftar menjadi dua bagian, tapi dia mengurutkan masing-masing bagian secara terpisah dan kemudian menggabungkannya untuk mendapatkan daftar yang terurut. Algoritma ini dikenal karena efisiensinya dalam mengurutkan data yang besar.

### 4. Selection Sort

Selection Sort bekerja dengan cara mencari elemen terkecil dalam daftar dan menukarnya dengan elemen pertama. Proses ini terus berlanjut untuk elemen-elemen berikutnya hingga seluruh daftar terurut.

### 5. Insertion Sort

Insertion Sort membandingkan setiap elemen dengan elemen-elemen sebelumnya dan memasukkannya ke dalam posisi yang benar dalam daftar yang terurut. Algoritma ini efisien untuk daftar kecil.

### 6. Shell Sort

Shell Sort adalah variasi dari Insertion Sort yang lebih efisien. Ia membandingkan dan menukar elemen-elemen yang terletak dalam jarak tertentu, lalu secara bertahap mengurutkan daftar tersebut hingga menjadi terurut.

### Contoh Program Algoritma Sorting

```
def bubble_sort(arr):

    n = len(arr)

    for i in range(n):

        swapped = False

        for j in range(0, n-i-1):

            if arr[j] > arr[j+1]:

                arr[j], arr[j+1] = arr[j+1], arr[j]  # Menukar elemen jika tidak terurut

                swapped = True

        # Jika tidak ada pertukaran yang dilakukan pada iterasi ini, berarti sudah terurut

        if not swapped:

            break

# Contoh penggunaan:

arr = [64, 34, 25, 12, 22, 11, 90]

print("Daftar sebelum diurutkan:", arr)

bubble_sort(arr)

print("Daftar setelah diurutkan:", arr)
```

### Penerapan Dalam Kehidupan Sehari- Hari

#### 1. Pencarian Data

Ketika kamu mencari nama dalam daftar kontak , metode pengurutan digunakan untuk mengatur nama-nama tersebut agar mudah ditemukan.

#### 2. E-commerce

Dalam aplikasi belanja online, metode sorting digunakan untuk mengurutkan produk berdasarkan harga, popularitas, atau penawaran terbaik.

#### 3. Database

Sistem database menggunakan metode sorting untuk mengatur data sehingga pencarian dan pengambilan data menjadi lebih efisien.

#### 4. Penjadwalan

Metode pengurutan juga digunakan dalam penjadwalan, seperti mengurutkan tugas-tugas dalam agenda harian berdasarkan waktu.
### Traversal/Penelusuran Graf
Diberikan sebuah graf, kita bisa menggunakan algoritma O(**V**+**E**) DFS (_Depth-First-Search_) atau BFS (_Breadth-First-Search_) untuk menjelajahi graf tersebut dan melihat fitur-fitur ataupun properti-properti yang ada dalam graf tersebut. Setiap algoritma penjelajahan graf memiliki karakteristik, fitur, dan efek samping tersendiri yang akan kita lihat dalam visualisasi ini.  
  

Visualisasi ini kaya dengan berbagai variasi DFS dan BFS (semua berjalan dalam O(**V**+**E**)) seperti:

1. Algoritma pengurutan topologikal (Versi DFS dan BFS/algoritma Kahn),  
    
2. Algoritma pengecekan bipartit (Versi DFS dan BFS),
3. Algoritma pencari simpul artikulasi & jembatan,
4. Algoritma-algoritma pencari _Strongly-Connected Component_ (SCC)  
    (versi Kosaraju dan Tarjan), dan
5. Algoritma pengecek 2-SAT.
![[Pasted image 20250910213809.png]]


### Recursive
Algoritma rekursif adalah jenis [algoritma](https://fikti.umsu.ac.id/mengenal-apa-itu-algoritma/) yang cukup menarik karena memungkinkan sebuah fungsi atau prosedur untuk memanggil dirinya sendiri dengan input yang semakin menyempit.

Dalam bahasa yang lebih sederhana, algoritma ini adalah cara untuk memecahkan masalah dengan memecahkannya menjadi beberapa versi yang lebih kecil dari masalah itu sendiri.

Algoritma rekursif dapat digunakan dalam berbagai jenis masalah, seperti pengurutan, pencarian, pemecahan masalah kombinatorial, dan banyak lagi. Namun, penting untuk memperhatikan bahwa penggunaan rekursi harus hati-hati dan memperhatikan efisiensi dan penggunaan memori.

Jika tidak dikendalikan dengan baik, rekursi dapat menyebabkan masalah memori (stack overflow) dan kinerja yang buruk.

### Tujuan Algoritma Rekursif

Algoritma rekursif memiliki beberapa tujuan, antara lain:

1. Dapat digunakan untuk memecahkan masalah yang kompleks menjadi sub masalah yang lebih sederhana.
2. Algoritma ini sering digunakan dalam implementasi struktur data seperti pohon, graf, atau daftar terhubung.
3. Serta dapat digunakan untuk melakukan pengulangan secara efisien.

### Jenis Algoritma Rekursif

#### a. Factorial

Algoritma factorial digunakan untuk menghitung faktorial dari suatu bilangan. Faktorial dari suatu bilangan n (ditulis n!) adalah hasil perkalian semua bilangan bulat positif dari 1 hingga n.

Contoh implementasi algoritma rekursif factorial dalam bahasa Python:

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```

#### b. Tower of Hanoi

Algoritma Tower of Hanoi digunakan untuk memindahkan tumpukan cakram dari satu tiang ke tiang lainnya, dengan aturan bahwa hanya satu cakram yang dapat dipindahkan pada satu waktu dan cakram yang lebih besar tidak boleh ditempatkan di atas yang lebih kecil.

Contoh implementasi algoritma Tower of Hanoi dalam bahasa Python:

```
def tower_of_hanoi(n, source, destination, auxiliary):
    if n > 0:
        tower_of_hanoi(n-1, source, auxiliary, destination)
        print("Move disk", n, "from", source, "to", destination)
        tower_of_hanoi(n-1, auxiliary, destination, source)
```

#### c. DFS of Graph

Algoritma Depth-First Search (DFS) digunakan untuk melakukan pencarian pada struktur data graf secara rekursif. Algoritma ini mengunjungi semua simpul dalam graf dengan mengikuti jalur secara mendalam sebelum kembali.

Contoh implementasi algoritma DFS dalam bahasa Python:

```
def dfs(graph, start, visited=None):
    if visited is None:
        visited = set()
    visited.add(start)
    print(start)
    for next_node in graph[start] - visited:
        dfs(graph, next_node, visited)
    return visited
```

#### d. Eksponential

Algoritma eksponensial digunakan untuk menghitung hasil dari suatu operasi eksponensial dengan memanggil diri sendirI.

Contoh implementasi algoritma eksponensial dalam bahasa Python:

```
def exponential(a, n):
    if n == 0:
        return 1
    else:
        return a * exponential(a, n-1)
```

Dengan menggunakan algoritma ini, kita dapat mengatasi berbagai macam masalah dengan cara yang lebih efisien dan terstruktur.