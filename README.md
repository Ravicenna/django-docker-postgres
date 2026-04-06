# Simple LMS - Django Docker

## 📌 Deskripsi

Project ini merupakan aplikasi Django yang dijalankan menggunakan Docker Compose dengan PostgreSQL sebagai database.

---

## 🚀 Cara Menjalankan

1. Jalankan Docker:
   docker-compose up --build

2. Buka browser:
   http://localhost:8000

---

## ⚙️ Environment Variables

* DB_NAME=postgres
* DB_USER=postgres
* DB_PASSWORD=postgres
* DB_HOST=db
* DB_PORT=5432

---

## 🧩 Services

* Django (Web Application)
* PostgreSQL (Database)

---

## 📸 Screenshot

### 🔹 Django Welcome Page

![Django Welcome Page](Django%20Wellcome%20Page.png)

### 🔹 Docker Container Running

![Docker PS](PS%20Docker.png)

---

## ✅ Hasil

* Django berhasil berjalan di localhost:8000
* PostgreSQL terhubung dengan baik
* Data dapat disimpan ke database

---

## ❓ Jawaban Pertanyaan

### 1. Kenapa menggunakan Docker?

Docker memudahkan deployment dan memastikan aplikasi berjalan konsisten di berbagai environment.

### 2. Apa fungsi docker-compose?

Untuk menjalankan beberapa container sekaligus (web dan database).

### 3. Kenapa menggunakan PostgreSQL?

PostgreSQL adalah database yang powerful dan cocok untuk aplikasi skala besar.

### 4. Bagaimana Django connect ke database?

Melalui environment variables dengan hostname service yaitu "db".

---
