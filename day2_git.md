"Catatan Git Hari 2 - Aditia" 
# Day 2 - Git & Version Control

## Apa itu Git?
Git adalah version control system (VCS) yang digunakan untuk melacak perubahan file (terutama kode program).  
Dengan Git kita bisa menyimpan riwayat, membuat cabang (branch), dan menggabungkan kode (merge).

---

## Branch dalam Git
Branch adalah "cabang" dari kode utama (main).  
Fungsinya:
- Membuat jalur pengembangan terpisah.
- Bisa eksperimen fitur baru tanpa mengganggu branch utama.
- Setelah selesai, hasil branch bisa digabung (merge) ke `main`.

Contoh alur:
1. Buat branch baru `feature-x`.
2. Kerjakan perubahan di branch itu.
3. Setelah selesai → merge kembali ke `main`.

---

## Syntax Git Penting

### Setup Identitas
```bash
git config --global user.name "Aditia"
git config --global user.email "email@example.com"
