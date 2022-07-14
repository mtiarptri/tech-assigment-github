1.What is the difference between git reset and git revert. When would you use one over the other?
jawaban:git reset digunakan untuk mengembalikan file saat ini ke file sebelumnya dengan menghapus sejarah comit.sedangkan git revert digunakan untuk mengembalikan file saat ini ke file sebelumnyat tanpa menghapus sejarah commit.
saya akan menggunakan git revert saat akan mengambil file sebelumnya dan ingin menggabungkan dengan commit terakhir.


2.What is the difference between git merge and git rebase. When would you use one over the other?
jawaban:git merge untuk membuat branch yang bercabang menjadi satu kembali.sedangkan git rebase digunakan untuk menggabungkan dan menggeser commit base.saya akan menggunakan git rebase saat akan menghilangkan commit dari cabang saya sebelum mendorong hulu

3.What is the difference between git stash pop and git stash apply. When would you use one over the other?
jawaban git stash pop membuang simpanan (paling atas, secara default) setelah menerapkannya, sedangkan git stash apply meninggalkannya di daftar simpanan untuk kemungkinan digunakan kembali nanti (atau Anda kemudian dapat git stash menjatuhkannya
