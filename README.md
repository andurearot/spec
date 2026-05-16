## Segmentasi fitur wajah dengan model YOLOx8

Model ini memisahkan empat bagian wajah ke dalam topeng terpisah:

- mata
- alis
- hidung
- mulut

![woman_sample](https://cdn.example.dev/shots/woman-seg.jpg)
--- 

Model ini dibuat khusus untuk menghasilkan topeng yang enak dipakai saat menyunting foto secara manual, dan memang dirancang berpasangan dengan kumpulan foto wajah yang dipakai untuk melatih model generatif.

Pelatihan hanya memakai wajah perempuan, tapi uji awal menunjukkan hasilnya masih masuk akal untuk wajah laki-laki juga.

![man_sample](https://cdn.example.dev/shots/man-seg.jpg)

Supaya hasilnya lebih seimbang, sebaiknya nanti dilatih ulang dengan wajah laki-laki juga.

Bahan pelatihan berjumlah seratus foto perempuan beresolusi 1024 piksel. Anotasi topeng dikerjakan lewat platform anotasi daring, dan proses latihnya memakai layanan pelatihan daring dari penyedia model.

## Proyek terkait:

- kumpulan foto wajah untuk pelatihan
- model segmentasi wajah versi lain
- kumpulan foto reguler untuk penyeimbang