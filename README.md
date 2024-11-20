# Belajar Git #

[![Konsep Version Control](img/konsep-version-control.png)](img/konsep-version-control.png)

[![Local dan Remote Repository](img/local-remote-repo.png)](img/local-remote-repo.png)

## Membuat Repository

1. Membuat Repository Local

    ```
    git init
    ```

2. Memindahkan perubahan file dari working area ke staging area

    ```
    git add namafile
    ```

3. Menyimpan perubahan yang ada di staging ke repository local

    ```
    git commit
    ```

    Atau

    ```
    git commit -m "Commit pertama"
    ```
4. Edward Added New Line

## Mengambil Repository dari Remote ##

1. Pergi ke website remote repo, kemudian copy paste URL repositorynya

    [![Git URL Gitlab](img/git-url.png)](img/git-url.png)

2. Jalankan git clone

    ```
    git clone <url-repository>
    ```

3. Melihat daftar branch local dan remote

    ```
    git branch --all
    ```

4. Mengambil perubahan dari remote repo ke branch remote di local repo

    ```
    git fetch github/main
    ```

5. Menggabungkan perubahan dari branch remote ke branch local

    ```
    git merge github/main
    ```