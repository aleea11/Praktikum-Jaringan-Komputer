# Praktikum-Jaringan-Komputer

https://youtu.be/Rr_RvwGC_WI

<img width="517" height="422" alt="image" src="https://github.com/user-attachments/assets/d048bc34-3ab9-4bde-9cea-7e2cbf68166c" />

Kenapa ping pertama timeout dan setelah ping selanjutnya reply berhasil?

Ping pertama biasanya Request Timed Out karena perangkat belum tahu MAC Address tujuan, sehingga harus melakukan proses ARP (Address Resolution Protocol) terlebih dahulu sebelum mengirimkan ICMP Reply. Proses ARP ini membutuhkan sedikit waktu sehingga ping pertama bisa gagal. Setelah MAC address ditemukan dan tersimpan di ARP Cache, ping berikutnya dapat langsung dikirim ke tujuan dan berhasil mendapatkan balasan.
