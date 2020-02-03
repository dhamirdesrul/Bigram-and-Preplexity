# Bigram-and-Preplexity

1. Program yang dibuat menggunakan bahasa pemrograman python tetapi kami memakai IDE jupyter notebook oleh sebab itu kami menyediakan dua format file
2. pertama kami melakukan crawling pada data csv yang berisi url untuk dapat di ambil datanya
3. setelah di lakukan crawling berdasarkan isi link tersebut kami simpan filenya ke dalam format text dengan data tersebut sudah kami kecilkan setiap katanya dan kami mengeluarkan data tersebut untuk memperlihatkan isi text yang sudah disimpan
4. kami melakukan tokenisasi dengan memanggil libary nltk yang bertujuan untuk menghilangkan tanda baca yang tidak penting dan menyimpan di dalam array yang berisi tokenisasi
5. bedasarkan array tokenisasi kami melakukan perhitungan unigram dan jumlah kata yang berada pada file artikel.txt
6. kami menghitung probabilitas unigram tersebut
7. setelah menghitung probabilitas unigram kami akan menghitung probabilitas bigram dengan menghitung keseluruhan 2 kata terlebih dahulu sebanyak artikel yang diberikan
8. setelah proses tersebut kami akan menghitung perplexity untuk mengetahui nilai kebingungan terhadap file artikel.txt yang sudah dihitung berdasarkan bigram sebelumnya.
9. kami menyediakan 5 kata untuk dilakukan adanya uji coba untuk mengetahui keberhasilan dari perplexity yang sudah dibuat dengan memunculkan jumlah bigramnya dan perplexity dari kalimat tersebut.
10. pada bagian terakhir kamu menguji untuk dapat mengetahui kata selanjtnya dari kata yang kami lakukan. kami memberikan satu kalimat yang berisikan 6 kata, lalu dipisahkan untuk dapat mengetahui kata selanjutnya
