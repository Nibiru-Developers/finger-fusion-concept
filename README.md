# Konsep Finger Fusion

## Penjelasan Singkat:

Finger Fusion merupakan sebuah permainan papan arena strategi yang sedang dikembangkan oleh [Andry Pebrianto](https://github.com/andry-pebrianto). Dalam permainan ini, pemain harus menghancurkan kedua zona lawan atau menghabiskan poin kehidupan lawan untuk meraih kemenangan. Pemain juga dapat menggunakan kartu-kartu dengan berbagai efek unik untuk mendukung permainannya.

## Tata Cara dan Aturan Permainan:

1. Pada awal permainan, pemain dan lawan memiliki dua zona di sebelah kiri (A) dan kanan (B) dengan masing-masing memiliki power satu.
2. Pada awal permainan, pemain dan lawan masing-masing memiliki sepuluh kartu di tangan.
3. Pada awal permainan, pemain dan lawan masing-masing memiliki seratus poin kehidupan.
4. Urutan giliran pertama dan kedua akan ditentukan dengan melempar koin.
5. Zona pemain, baik zona A maupun zona B, dapat menyerang zona musuh. Misalnya, jika pemain menyerang zona B milik lawan yang memiliki power satu dengan zona A yang memiliki power satu, maka lawan akan menerima satu damage sehingga mengurangi poin kehidupan lawan sebanyak satu. Selain itu, power pada zona B lawan yang sebelumnya diserang akan bertambah satu sehingga menjadi dua.
6. Ketika suatu zona dengan power empat diserang oleh zona dengan power dua, zona yang sebelumnya memiliki power empat akan menjadi satu karena apabila power melebihi lima, maka akan dikurangi sebesar lima.
7. Jika suatu zona mencapai power lima, maka zona tersebut akan hancur.
8. Ketika hanya ada satu zona yang bertahan di arena dan zona tersebut memiliki power genap (empat atau dua), maka zona tersebut dapat membelah dirinya, memberikan setengah powernya kepada zona di sebelahnya yang telah hancur.
9. Terdapat tiga jenis kartu dalam permainan ini, yaitu kartu Penyerang, Bertahan, dan Hybrid.
10. Kartu Penyerang hanya bisa diaktifkan di giliran pemain, kartu Bertahan hanya bisa diaktifkan di giliran lawan, dan kartu Hybrid bisa diaktifkan di giliran pemain maupun lawan.
11. Jika poin kehidupan pemain berkurang hingga menjadi nol, maka pemain akan langsung dinyatakan kalah.
12. Jika kedua zona pemain hancur, maka pemain akan langsung dinyatakan kalah.

## Beberapa Hal Penting:

**Zona**:
Zona adalah dua objek yang terletak di sebelah kiri (A) dan kanan (B) arena setiap pemain, termasuk pemain lawan. Setiap zona memiliki power yang diwakili oleh sebuah nilai, yang pada awal permainan memiliki nilai awal satu. Ketika power suatu zona mencapai lima, zona tersebut akan hancur. Pemain yang kedua zonanya telah hancur akan langsung dinyatakan kalah.

**Poin Kehidupan**:
Poin Kehidupan merupakan salah satu faktor kunci dalam menentukan kemenangan. Apabila poin kehidupan pemain mencapai nol, pemain tersebut akan mengalami kekalahan. Pada awal permainan, poin kehidupan pemain dan lawan setara, yaitu seratus. Poin kehidupan dapat berkurang melalui serangan pada zona atau melalui efek khusus dari kartu tertentu.

**Kartu**:
Kartu merupakan hal yang sangat penting dalam permainan ini. Setiap kartu memiliki efek unik yang berbeda. Dengan menggunakan efek kartu yang tepat pada saat yang tepat, situasi permainan dapat berubah dengan cepat. Setiap pemain dapat membawa hingga sepuluh kartu dalam setiap permainan.

