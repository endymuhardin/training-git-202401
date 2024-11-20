# Belajar Git #

[![Konsep Version Control](img/konsep-version-control.png)](img/konsep-version-control.png)

[![Local dan Remote Repository](img/local-dan-remote-repo.png)](img/local-dan-remote-repo.png)

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

## Mengambil Repository dari Remote ##

1. Pergi ke website remote repo, kemudian copy paste URL repositorynya

    [![Git URL Gitlab](img/git-url.png)](img/git-url.png)

2. Jalankan git clone

    ```
    git clone <url-repository>
    ```