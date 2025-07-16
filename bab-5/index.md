## BAB V: Mengintegrasikan DDD dengan Clean Architecture

* **V.A. Kenapa DDD Cocok dengan Clean Architecture?**
    * V.A.1. Sinergi antara Domain Focus (DDD) dan Struktur Modular (Clean Arch)
    * V.A.2. Memastikan Domain Model Tetap Bersih dan Independen
* **V.B. Pemetaan Konsep DDD ke Layer Clean Architecture**
    * V.B.1. Domain Model (Entities, Value Objects, Aggregates, Domain Services, Domain Events) di Layer **Entities** (Domain Core)
    * V.B.2. Application Services (Use Cases) di Layer **Use Cases**
    * V.B.3. Repositories di Layer **Interface Adapters** (sebagai Interface) dan **Frameworks & Drivers** (sebagai Implementasi)
    * V.B.4. UI/API di Layer **Interface Adapters**
* **V.C. Studi Kasus Penerapan DDD dan Clean Architecture**
    * V.C.1. Merancang Arsitektur Sistem Baru dengan DDD + Clean Arch
    * V.C.2. Refactoring Aplikasi Lama Menggunakan Pendekatan Ini
