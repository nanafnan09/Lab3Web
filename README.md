# Lab3Web

Nama: **Afnan Dika Ramadhan**

NIM: **312410518**

Kelas: **TI24.A5**

Mata Kuliah: **Pemrograman Web**

# Langkah Langkah Pembuatan Lab3Web

Persiapkan membuat dokumen ``HTML`` dengan nama file lab3_list.html Lalu tambahkan kode untuk membuat `ordered list`
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/code%201.png)


Tampilan awal akan seperti ini

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/foto%201.png)

# Membuat Unordered List

Langkah selanjutnya tambahkan kode ini dibawah kode sebelumnya

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/code%202.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/foto%202.png)

# Membuat Description List

Tambahkan kode ini di sesudah kode Unordered List

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/foto%203.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/code%203.png)

# Membuat Tabel

Buat file baru yang bernama ``lab3_tabel.html`` dan tambahkan kode untuk table nya

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/code%204.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/foto%204.png)

# Mengatur Margin dan Padding

Kode ini untuk mengatur margin dan padding pada cel data

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/93c776a9a8b659eff4699ab14328c561008f5ea0/code%205.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/22341fae8b2bdccecf3d8149975c99ce3f812287/Cuplikan%20layar%202025-10-08%20200538.png)

# Gabungkan Sel DATA

Fungsi kode dibawah ini membuat layout tabel akan berubah

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/Cuplikan%20layar%202025-10-08%20203830.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/foto%206.png)

# Membuat Form

Buat file baru dengan nama lab3_form.html seperti berikut.

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/code%207.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/foto%207.png)

# Menambahkan Style Pada Form

kode css ini berfungsi sebagai menambahkan elemen warna pada kode html

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/code%208.png)

![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/foto%208.png)



# Pertanyaan dan Tugas

1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.


**JAWABAN**

```HTML
  <p>
      <label for="provinsi">Provinsi</label>
      <select id="provinsi" name="provinsi">
        <option value="jawa_barat">Jawa Barat</option>
        <option value="jawa_tengah">Jawa Tengah</option>
        <option value="jawa_timur">Jawa Timur</option>
        <option value="dki_jakarta">DKI Jakarta</option>
      </select>
    </p>
    <p>
      <label for="hobi">Hobi</label>
      <select id="hobi" name="hobi[]" multiple size="4">
        <option value="membaca">Membaca</option>
        <option value="menulis">Menulis</option>
        <option value="olahraga">Olahraga</option>
        <option value="musik">Musik</option>
        <option value=" traveling">Traveling</option>
      </select>
    </p>
    <p><input type="submit" value="Login" /></p>
  </fieldset>
```

Kode ini berfungsi sebagai menampilkan opsi opsi pilihan dari pulau pulau dan hobi


Dan inilah hasilnya
![foto](https://github.com/nanafnan09/Pratikum-Pict/blob/5d2d561f9cc0a1550cd44ae22082a85c4dbeef4b/Foto%20quiz.png)

