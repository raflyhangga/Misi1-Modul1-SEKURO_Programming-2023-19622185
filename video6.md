 # GIT BRANCH & MERGE

## Branch

    $ git branch (nama_branch) # Branch
    $ git checkout (nama_branch) # Checkout

- Masukkan command branch dan tulis branch yang diinginkan.
- Apabila ingin pindah brnach, gunakan command checkout.

## Merge

Merge dibagi menjadi dua: <strong>Fast Forward</strong> dan <strong> Three-way Merge</strong>.

Fast Forward: Ada direct path, tidak terbuat commit baru.
Three-way Merge: Tidak ada direct path, terbuat commit baru.


<strong>Fast Forward</strong>

    $ git merge (branch yang ingin digabung) #Merge
    $ git branch -d (nama_branch) # Hapus branch

- Pindah ke branch yang ingin disimpan.
- Masukkan command merge terhadap branch yang ingin di merge.
- Apabila ingin menghapus branch, masukkan command hapus branch.

<strong>Three-way Merge</strong>

    $ git merge (branch yang ingin digabung) #Merge
    $ git branch -d (nama_branch) # Hapus branch

- Pindah ke branch yang ingin disimpan.
- Masukkan command merge terhadap branch yang ingin di merge.
- Masukkan pesan commit.
- Apabila ingin menghapus branch, masukkan command hapus branch.