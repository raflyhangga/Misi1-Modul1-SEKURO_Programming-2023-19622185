# Bekerja dengan GIT

## Instalasi GIT (Windows)
- Buka website [GIT](www.git-scm.com).
- Download git.
- Pada Git Setup "Adjusting your PATH Environment", Pilih "Git from the command line and also from 3rd-party".
- Buka Git Bash.

## Git Command (local)
    $ git init
    $ git add <file(s)>
    $ git status
    $ git commit 
    $ git config
    $ git branch
    $ git help
    ...

Area pada repo GIT:
1. Working tree
2. Staging area
3. History

## Membuat Repository

    $ cd (direktori) #Direktori.

- Buat folder yang diinginkan.
- Ubah direktori Git Bash menjadi direktori file tersebut menggunakan command direktori.

## Commit File

    $ git add (nama file) #Menambahkan file.
    $ git commit -m (Pesang Singkat) #Commit
    $ git config --global user.email "email" #Email
    $ git config --global user.name "Your Name" #Username
    $ git status #Status

- Buat file yang diinginkan.
- Ketik command menambahkan file kedalam command / GitBash
- Masukkan infromasi email dan username menggunakan command email dan username.
- Ketik command commit dan masukkan pesan singkat.
- Check menggunakan command status untuk melihat kondisi file.

## Checkout

    $ git log # Mengecek hasil commit
    $ git checkout (5 digit pertama hash) # Checkout

- Masukkan command "mengecek hasil commit"
- Pilih commit yang ingin dituju dengan menyimpan lima angka hash pertama.
- Masukkan command checkout beserta angka hash tersebut.

## PERCOBAAN

- Initialize Git
![Initialize Git](Screenshot\init_git.png)

- Commit
![Commit](Screenshot\commitbash.png)

- Checkout
![Checkout](Screenshot\checkoutbash.png)