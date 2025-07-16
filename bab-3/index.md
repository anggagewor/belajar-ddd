## BAB III: Tactical Design: Membangun Blok Bangunan Domain Model

* **III.A. Entity: Objek dengan Identitas Unik**
    * III.A.1. Definisi dan Karakteristik Entity
    * III.A.2. Perbedaan Entity dengan Value Object
    * III.A.3. Contoh Implementasi Entity
* **III.B. Value Object: Objek yang Didefinisikan oleh Atributnya**
    * III.B.1. Definisi dan Karakteristik Value Object
    * III.B.2. Keuntungan Penggunaan Value Object (Immutability, Kesetaraan)
    * III.B.3. Contoh Implementasi Value Object
* **III.C. Aggregate: Menjaga Konsistensi Domain**
    * III.C.1. Definisi dan Peran Aggregate Root
    * III.C.2. Aturan Konsistensi dalam Aggregate
    * III.C.3. Contoh Implementasi Aggregate
* **III.D. Domain Services: Operasi yang Tidak Pas di Entity/Value Object**
    * III.D.1. Definisi dan Kasus Penggunaan Domain Services
    * III.D.2. Perbedaan Domain Service dengan Application Service
    * III.D.3. Contoh Implementasi Domain Services
* **III.E. Domain Events: Mengkomunikasikan Perubahan Penting**
    * III.E.1. Definisi dan Manfaat Domain Events
    * III.E.2. Penerapan Domain Events
    * III.E.3. Contoh Implementasi Domain Events
* **III.F. Repository: Mengelola Persistensi Aggregate**
    * III.F.1. Definisi dan Peran Repository
    * III.F.2. Memisahkan Persistensi dari Domain Logic
    * III.F.3. Contoh Implementasi Repository
