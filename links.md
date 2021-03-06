---
layout: "links_layout"
permalink: /LINKS/
---


# My Links




## Week 01-04

1. [Tutorial Youtube Bash Script lengkap](https://www.youtube.com/watch?v=e7BufAVwDiM)

	Saya banyak banget belajar dari sini. Isinya sangat lengkap, mulai dari pengenalan cara membuat script bash, mendaftarkan variabel, pipe, sampai grep dan awk. Semuanya ada. Hanya dalam 3 jam kalian bisa menguasai semuanya dengan baik. Saya cukup yakin kalian bisa jago memahami bash jika menyimak video ini. Have a nice day!

2. [File system implementations](https://www.youtube.com/watch?v=JoTIG_ElTyY)

	Mempelajari berbagai macam jenis-jenis implementasi pada file system serta komponen-komponennya. Mulai dari cara melacak apakah suatu block of file itu kosong atau tidak, manfaat inode, manfaat superblock, dll.

3. [File allocation methods](https://www.geeksforgeeks.org/file-allocation-methods/)

	Artikel singkat mengenai file allocation methods

4. [Memory layout of C](https://www.youtube.com/watch?v=kpWG423uQIw)

   Disini kita bisa mempelajari struktur memory dari sebuah program C. Disini juga kita bisa mempelajari cara melihat struktur dari program C yang kita tulis.

5. [C -- Call by value vs call by reference](https://www.youtube.com/watch?v=HEiPxjVR8CU)

   Salah satu fitur pada C adalah pass by value dan pass by reference. Ini merupakan fitur yang sangat penting pada C maupun C++. Namun, sebagian besar orang masih merasa kesulitan dalam memahami materi ini. Disini ada video yang menjelaskan secara detil mengenai pass by value dan pass by reference.



## week 05-08

1. [Paging vs segmenting](https://www.youtube.com/watch?v=p9yZNLeOj4s)

     Pengetahuan yang jauh lebih detil dan mendalam mengenai perbedaan antara paging dengan segmenting.  

2. [Virtual memory, paging, dan segmenting](https://www.youtube.com/watch?v=qeOBEOBJREs)

     Sedikit penjelasan mengenai apa itu virtual memory, beserta metode-metode yang biasanya digunakan (paging ataupun segmenting)

3. [Thrashing dan CPU utilization](https://www.youtube.com/watch?v=mIJIDC-u8JU)

   Salah satu fenomena yang dapat terjadi di dalam sebuah komputer adalah thrashing. Video ini menjelaskan mengenai apa itu thrashing, dan mengapa hal ini bisa terjadi. Video ini juga mejelaskan dampaknya thrashing terhadap CPU utilization pada komputer.

4. [Swapping](https://www.youtube.com/watch?v=Qt49Hzh_TDc)

   Saat pertama kali kita disuruh membuat OS pada virtualbox, kita disuruh mengalokasikan sebagian hard disk pada virtual OS untuk menyimpan swap file. Namun waktu itu kita tidak mengerti apa itu gunanya. Sekarang, setelah menonton video ini, kita menjadi tahu apa itu swapping dan apa itu swap file.

5. [fork() function in C (linux)](https://www.youtube.com/watch?v=cex9XrZCU14)
	
	fork() merupakan salah satu fungsi pada bahasa C [linux] dimana fungsi ini cukup berguna dalam membuat program parallel (multiprocessing). Hal ini tentu bisa mempercepat performa program kita. Pada video ini, kita dijelaskan secara detil mengenai apa yang dilakukan oleh fungsi fork() tersebut
	
6. [exec() functions in C (linux)](https://www.youtube.com/watch?v=IFEFVXvjiHY)

     exec() merupakan salah satu fungsi pada bahasa C yang juga cukup penting dalam mempelajari tentang process pada sistem operasi. Youtube ini membahas mengenai apa itu exec() dan apa manfaatnya, serta bagaimana cara memakainya

7. [semaphore C linux](https://www.youtube.com/watch?v=TYnNKdf7cZM)

     Semaphore merupakan sebuah fungsi yang cukup penting dalam pemrograman multi-threading. Pada video ini, akan diajarkan berbagai manfaat dan cara menggunakan semaphore pada bahasa C linux.

8. [dining philosopher problem](https://www.youtube.com/watch?v=FYUi-u7UWgw)

     Dining philosopher merupakan salah satu masalah yang penting untuk dipahami dalam pemrograman multithreading. Pada kesempatan kali ini, kita akan melihat lebih detail mengenai apa itu dining philosopher, dan bagaimana cara kita mengatasinya.

9. [Deadlock](https://www.geeksforgeeks.org/introduction-of-deadlock-in-operating-system/)

     Deadlock merupakan salah satu masalah buruk pada pemrograman multithreading. Pada situs ini dijelaskan apa itu deadlock, kondisi yang harus terpenuhi supaya bisa terjadi deadlock, serta penjelasan-penjelasan dari setiap kondisi tersebut.

10. [Latihan soal gate cs 2005 exam](https://www.geeksforgeeks.org/operating-systems-set-16/#)

      Salah satu hal yang penting dalam os ialah memahami teori-teori untuk mempersiapkan quiz 1. Pada situs ini, tersedia beberapa set latihan soal beserta kunci jawabannya. Meskipun begitu, teman-teman mungkin perlu login untuk mengakses halaman ini

11. [Preemptive dan non-preemptive scheduling](https://www.youtube.com/watch?v=4DhFmL-6SDA)

	Pada video ini, kita akan mempelajari banyak hal yang berkaitan dengan CPU scheduling. Pada video ini, kita akan mengenal apa itu cpu scheduler, dispatcher, dispatch latency, hingga preemptive dan non-preemptive scheduling.


12. [CPU scheduling policy & round robin scheduling](https://www.geeksforgeeks.org/cpu-scheduling-in-operating-systems/)

	Salah satu hal yang cukup penting dalam multiprogramming adalah scheduling. Pada webpage ini, kita akan dikenalkan dengan beberapa istilah (throughput, turnaround, dsb), serta kita juga akan diperkenalkan dengan beberapa scheduling policy, termasuk round robin scheduling.  

13. [Round robin scheduling example](https://www.youtube.com/watch?v=7TpxxTNrcTg)

	Pada video ini, kita akan dikenalkan secara lebih mendalam mengenai round robin scheduling. Dengan menggunakan contoh pada video ini, semoga kita bisa semakin paham mengenai round robin dan cara kerjanya.


<br>

## My other links

1. [Checksum auto updater script](https://github.com/Hzz-Hzz/my_os212_useful_scripts/tree/main/automatic_checksum_updater)

   Apakah kalian lelah karena setiap mengubah file pada `TXT/` harus selalu mengupdate checksum? Jika kelupaan, akan ada sanksi pengurangan nilai (CMIIW). Berikut ini adalah script otomatis mengupdate checksum setiap 1 menit jika ada perubahan. Script ini ditulis menggunakan linux, oleh karena itu script ini hanya berjalan jika Anda sedang membuka linux Anda.

2. [myrank tracker](https://github.com/Hzz-Hzz/my_os212_useful_scripts/tree/main/rank_tracker)

   Penasaran siapa saja yang men-vote anda, tetapi lelah kalau harus mengecek satu-per-satu myrank setiap orang? Mungkin ini bisa jadi solusinya! :D



<br>

## Out of topic links


1. [HzzGrader](https://github.com/Hzzkygcs/SDA)

	Ingin mendapatkan nilai bagus di SDA? Salah satu yang perlu dilakukan adalah mengecek kembali script yang ingin kita kumpulkan. Bekerja-sama dengan chronojudge, disini kalian bisa mendapatkan tools untuk mengecek apakah script SDA kalian sudah memberikan output yang diharapkan atau tidak. Semoga bermanfaat, teman-teman :D