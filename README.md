# Konsep Finger Fusion

---

## Penjelasan Singkat:

Finger Fusion merupakan sebuah permainan papan arena strategi yang sedang dikembangkan oleh [Andry Pebrianto](https://github.com/andry-pebrianto). Dalam permainan ini, pemain harus menghancurkan kedua zona lawan atau menghabiskan poin kehidupan lawan untuk meraih kemenangan. Pemain juga dapat menggunakan kartu-kartu dengan berbagai efek unik untuk mendukung permainannya.

---

## Tata Cara dan Aturan Permainan:

1. Pada awal permainan, pemain dan lawan memiliki dua zona di sebelah kiri (A) dan kanan (B) dengan masing-masing memiliki power satu.
2. Pada awal permainan, pemain dan lawan masing-masing memiliki sepuluh kartu di tangan.
3. Pada awal permainan, pemain dan lawan masing-masing memiliki seratus poin kehidupan.
4. Urutan giliran pertama dan kedua akan ditentukan dengan melempar koin.
5. Zona pemain, baik zona A maupun zona B, dapat menyerang zona musuh. Misalnya, jika pemain menyerang zona B milik lawan yang memiliki power satu dengan zona A yang memiliki power satu, maka lawan akan menerima satu damage sehingga mengurangi poin kehidupannya sebanyak satu. Selain itu, power pada zona B lawan yang sebelumnya diserang akan bertambah satu, sehingga menjadi dua.
6. Ketika suatu zona dengan power empat diserang oleh zona dengan power dua, zona yang sebelumnya memiliki power empat akan menjadi satu karena apabila power melebihi lima, maka akan dikurangi sebesar lima.
7. Jika suatu zona mencapai power lima, maka zona tersebut akan hancur.
8. Ketika hanya ada satu zona yang bertahan di arena dan zona tersebut memiliki power genap (empat atau dua), maka zona tersebut dapat membelah dirinya, memberikan setengah powernya kepada zona di sebelahnya yang telah hancur.
9. Terdapat tiga jenis kartu dalam permainan ini, yaitu kartu Penyerang, Bertahan, dan Hybrid.
10. Setiap kartu memiliki biaya pengaktifkan masing-masing, di mana biaya tersebut akan mengurangi poin kehidupan pemain yang menggunakannya.
11. Terdapat dua fase dalam suatu giliran, yaitu fase Strategi dan fase Penyerangan.
12. Kartu tipe Penyerang hanya bisa diaktifkan pada giliran pemain dalam fase Strategi pemain.
13. Kartu tipe Bertahan hanya bisa diaktifkan pada giliran lawan dalam fase Penyerangan lawan.
14. Kartu tipe Hybrid bisa diaktifkan pada giliran pemain dalam fase Strategi dan giliran lawan dalam fase Penyerangan.
15. Pemain hanya dapat membawa maksimal satu kartu Tier S, tiga kartu Tier A, dan tidak ada batasan untuk kartu Tier B dan C.
16. Jika kedua zona pemain hancur, pemain memiliki opsi untuk mengorbankan 20 Poin Kehidupan guna membangkitkan kembali satu zona pemain. Jika pemain tidak memilih opsi tersebut, maka pemain akan langsung dinyatakan kalah.
17. Jika poin kehidupan pemain berkurang hingga menjadi nol, maka pemain akan langsung dinyatakan kalah.

---

## Beberapa Hal Penting:

**Zona**:
Zona adalah dua objek yang terletak di sebelah kiri (A) dan kanan (B) arena setiap pemain, termasuk pemain lawan. Setiap zona memiliki power yang diwakili oleh sebuah nilai, yang pada awal permainan memiliki nilai awal satu. Ketika power suatu zona mencapai lima, zona tersebut akan hancur. Pemain yang kedua zonanya telah hancur akan langsung dinyatakan kalah.

**Poin Kehidupan**:
Poin Kehidupan merupakan salah satu faktor kunci dalam menentukan kemenangan. Apabila poin kehidupan pemain mencapai nol, pemain tersebut akan mengalami kekalahan. Pada awal permainan, poin kehidupan pemain dan lawan setara, yaitu seratus. Poin kehidupan dapat berkurang melalui serangan pada zona atau melalui efek khusus dari kartu tertentu.

**Kartu**:
Kartu merupakan hal yang sangat penting dalam permainan ini. Setiap kartu memiliki efek unik yang berbeda. Dengan menggunakan efek kartu yang tepat pada saat yang tepat, situasi permainan dapat berubah dengan cepat. Setiap pemain dapat membawa hingga sepuluh kartu dalam setiap permainan.

---

## Daftar Kartu:

- ### Tipe Penyerang

  | Nama Kartu          | Efek                                                                                                  | Tier | Biaya            |
  | ------------------- | ----------------------------------------------------------------------------------------------------- | ---- | ---------------- |
  | Steal the Spotlight | Lawan akan melewati giliran setelah ini.                                                              | A    | 8 Poin Kehidupan |
  | Swap Surprise       | Pilih satu zona milik anda dan satu zona milik lawan sebagai target, lalu tukar nilai power keduanya. | B    | 4 Poin Kehidupan |
  | Wrathful Strike     | Berikan 10 Damage kepada lawan.                                                                       | C    | 8 Poin Kehidupan |
  | Healing Wave        | Memulihkan 10 Poin Kehidupan untuk anda dan 3 Poin Kehidupan untuk lawan.                             | A    | 2 Poin Kehidupan |
  | Restorative Aura    | Memulihkan 5 Poin Kehidupan pada giliran anda selanjutnya.                                            | C    | 2 Poin Kehidupan |
  | Rampage of Ruin     | Target salah satu zona lawan, hancurkan zona tersebut.                                                | S    | 0 Poin Kehidupan |
  | Triple Strike       | Anda dapat menyerang 3 kali pada giliran ini, namun damage untuk setiap serangan akan dikurangi 1.    | S    | 0 Poin Kehidupan |
  | Twin Blades of Ruin | Damage dari serangan pada giliran ini akan digandakan.                                                | A    | 5 Poin Kehidupan |

- ### Tipe Bertahan

  | Nama Kartu          | Efek                                                                                                              | Tier | Biaya            |
  | ------------------- | ----------------------------------------------------------------------------------------------------------------- | ---- | ---------------- |
  | Attack Repellent    | Batalkan serangan lawan pada giliran ini dan segera akhiri gilirannya.                                            | B    | 5 Poin Kehidupan |
  | Zone Annihilation   | Jika lawan memiliki 2 Zona aktif, hancurkan satu zona lawan dengan power terkecil.                                | B    | 6 Poin Kehidupan |
  | Negation Wave       | Kartu tidak akan bisa diaktifkan pada giliran lawan berikutnya.                                                   | A    | 7 Poin Kehidupan |
  | Regenerative Impact | Serangan di giliran ini akan memberikan pemulihan Poin Kehidupan alih-alih mendapatkan damage.                    | C    | 4 Poin Kehidupan |
  | Soul Drainer        | Memulihkan 3 Poin Kehidupan untuk anda, kemudian memberikan 10 damage untuk lawan.                                | S    | 0 Poin Kehidupan |
  | Impervious Barrier  | Tiap kali zona milik anda akan hancur oleh serangan, zona tersebut tidak akan hancur dan powernya akan menjadi 1. | A    | 6 Poin Kehidupan |

- ### Tipe Hybrid

  | Nama Kartu              | Efek                                                                                                       | Tier | Biaya                                                                 |
  | ----------------------- | ---------------------------------------------------------------------------------------------------------- | ---- | --------------------------------------------------------------------- |
  | Double Trouble          | Target salah satu zona lawan, jika power pada zona tersebut bernilai 1 atau 2, powernya akan digandakan.   | C    | 4 Poin Kehidupan                                                      |
  | Plus One Power          | Target salah satu zona anda, jika power pada zona tersebut tidak bernilai 4, tambahkan powernya 1.         | C    | 4 Poin Kehidupan                                                      |
  | Reflection Tactics      | Pilih satu kartu yang sudah pernah anda gunakan sebelumnya, salin efek kartu tersebut.                     | A    | Biaya Kartu Yang Disalin + 2 Poin Kehidupan                           |
  | Rekindle the Spirit     | Jika anda hanya memiliki satu zona yang tersisa, bangkitkan zona anda yang lain dengan membawa satu power. | B    | Fase Strategi (5 Poin Kehidupan), Fase Penyerangan (7 Poin Kehidupan) |
  | Infinite Revitalization | Memulihkan 1 Poin Kehidupan setiap masuk giliran anda.                                                     | B    | 6 Poin Kehidupan                                                      |
  | Deadly Poison           | Memberikan 2 damage kepada lawan selama 5 giliran lawan ke depan.                                          | B    | 5 Poin Kehidupan                                                      |
