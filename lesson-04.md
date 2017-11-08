# CODING TEEN

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

---

### LESSON 04: FORM & EMBED

---

### Objectives
2. Peserta mengetahui cara membuat form pada HTML.
2. Peserta mengetahui cara membuat google form.
2. Peserta mengetahui cara menyisipkan google form pada halaman website.
2. Peserta mengetahui cara menyisipkan video youtube pada halaman website.
2. Peserta mengetahui cara menyisipkan video yang ada pada laptop pada halaman website.

---

### Material
#### 1. Form

##### a) Text

  * Isi file index.html:

  ```html

	<input type="text" name="nama_lengkap" placeholder="Nama Lengkap">

  ```

##### b) Password

  * Isi file index.html:

  ```html

	<input type="password" name="password" placeholder="Password">


  ```

##### c) Email

  * Isi file index.html:

  ```html

	<input type="email" name="email" placeholder="Email">

  ```

##### d) Date

  * Isi file index.html:

  ```html

	<input type="date" name="tanggal_lahir" placeholder="Tanggal Lahir">

  ```

##### e) Checkbox

  * Isi file index.html:

  ```html

  <input type="checkbox" name="hobi[]" value="Sepak Bola"> Sepak Bola
  <input type="checkbox" name="hobi[]" value="Berenang"> Berenang 
  <input type="checkbox" name="hobi[]" value="Masak"> Masak 
  <input type="checkbox" name="hobi[]" value="Menggambar"> Menggambar 

  ```

##### f) Radio

  * Isi file index.html:

  ```html

  <input type="radio" name="jenis_kelamin" value="laki-laki" checked> Laki-laki
  <input type="radio" name="jenis_kelamin" value="perempuan"> Perempuan

  ```

##### g) Select

  * Isi file index.html:

  ```html

	<select name="kelas">
	  <option value="9">IX</option>
	  <option value="10">X</option>
	  <option value="11">XI</option>
	</select>

  ```

  ##### h) Multiple Select

  * Isi file index.html:

  ```html

  <select name="hobi">
    <option value="Sepak Bola">Sepak Bola</option>
    <option value="Berenang">Berenang</option>
    <option value="Masak">Masak</option>
  </select>

  ```

##### i) Text Area

  * Isi file index.html:

  ```html

	<textarea name="alamat" rows="4" cols="50">
	 Jl. H. Agus Salim no. 32B, lantai 2 Kebon Sirih, Menteng Jakarta Pusat 10340
	</textarea>

  ```

##### j) Button

  * Isi file index.html:

  ```html

	<input type="button" value="Cancle">
	<input type="submit" value="Submit">
	<input type="reset" value="Reset">

  ```


#### 2. Embed Google Form

##### a) Cara Membuat Google Form

1. Login dalam akun google Anda.

2. Masuk ke dalam google drive dengan klik <a href="https://drive.google.com">LINK INI</a>

3. Setelah masuk Google Drive, silahkan fokus pada pojok kanan atas tempat baris menu berada kemudian klik pada tombol <b>New</b> > <b>More</b> > <b>Google Forms</b>.

<img src="https://www.maxmanroe.com/wp-content/uploads/2015/05/gform_1.jpg">

4. Anda akan dihadapkan pada tampilan default Google Form yang form maupun judulnya masih serba untitled, seperti pada gambar dibawah ini:

<img src="https://www.maxmanroe.com/wp-content/uploads/2015/05/gform_2.jpg">

5. Anda bisa mengganti judul form yang masih Untitled menggunakan judul anda sendiri. Sebagai contoh saya menggantinya menjadi Contoh Form Pendaftaran Olimpiade. Untuk bagian 
yang saya ganti dengan Nama itu adalah form pertama yang disediakan.

<img src="https://www.maxmanroe.com/wp-content/uploads/2015/05/gform_3.jpg">

6. Klik pada Add Item yang berada di bagian bawah untuk menambah form baru, Anda bisa memilih jenis form seperti apa yang ingin anda tambah. Anda bisa menambah form dalam bentuk teks seperti form Nama diatas atau dengan bentuk yang lain.

<img src="https://www.maxmanroe.com/wp-content/uploads/2015/05/gform_4.jpg">

7. Buat Input untuk Jenis Kelamin dengan bentuk data multiple choice atau pilihan ganda.

<img src="https://www.maxmanroe.com/wp-content/uploads/2015/05/gform_5.jpg">

8. Lengkapi form dengan berbagai jenis informasi yang ingin apa pada form pendaftaran.

9. Setelah selesai membuat form pendaftaran, klik tombol <b>"SEND"</b>.

10. Kemudian pada Send Form Klik tab Embed seperti pada gambar di bawah ini.

<img src="https://scontent-sin6-2.xx.fbcdn.net/v/t1.0-9/23244584_10211190429664639_9222370049142844422_n.jpg?oh=481cc22fba12aeda334cd130190aef22&oe=5A9DD9C5">

11. Copy tulisan yang ada pada text field Embed HTML.


###### Video Tutorial

[Video tutorial membuat Google Form](https://www.youtube.com/embed/FvZPNIPFCs8)


##### b) Cara Menyisipkan Google Form Pada Website

  * Isi file index.html:

  ```html

  <html>
    <head>
      <title>
        Form
      </title>
      <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>
    <body>
      <div id="form">
          <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSd5hZ35Efqu0PIKCgaTQXWz5CNG6-DqjORZPAoVsw1n7GQoBg/viewform?embedded=true" frameborder="0" marginheight="0" marginwidth="0">Loading...</iframe>
      </div>
    </body>
  </html>


  ```

  * Isi file style.css:

  ```css

  #form{
    width: 550px;
    height: 1250px;
    overflow: hidden;
  }

  #form iframe{
    margin-top: -200px;
    margin-left: -100px;
    height: 1500px;
    width: 150%;
  }
  

  ```  

#### 3. Embed Video From Youtube

  * Isi file index.html:

  ```html

  <html>
    <head>
      <title>
        Embed Video From Youtube
      </title>
    </head>
    <body>
      <iframe width="854" height="480" src="https://www.youtube.com/embed/IjN-WsRh0tI" frameborder="0" gesture="media" allowfullscreen></iframe>
    </body>
  </html>


  ```

---
#### 3. Embed Video From Local Video

  * Isi file index.html:

  ```html

  <html>
    <head>
      <title>
        Embed Video From Local Video
      </title>
    </head>
    <body>
    <video width="900" controls>
      <source src="videos/video.mp4" type="video/mp4">
      Your browser does not support HTML5 video.
    </video>
    </body>
  </html>


  ```

---
### Instruction
1. Buka sublime dan mulai menulis script.
2. Peserta diajarkan untuk membuat form pada HTML.
2. Peserta diajarkan untuk membuat google form.
2. Peserta diajarkan untuk menyisipkan google form pada halaman website.
2. Peserta diajarkan untuk menyisipkan video youtube pada halaman website.
2. Peserta diajarkan untuk menyisipkan video yang ada pada laptop pada halaman website.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 04** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 04** ini?

---

### References
* <a href="https://bukugue.com/cara-membuat-email-gmail/">Cara membuat akun google</a>
* <a href="https://www.maxmanroe.com/cara-membuat-formulir-online-menggunakan-google-form.html"> Cara membuat google form </a>

---

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

[0]: README.md "Home"
[1]: lesson-01.md "Web Technology"
[2]: lesson-02.md "HTML & CSS"
[3]: lesson-03.md "Typography"
[4]: lesson-04.md "Form & Embed"
[5]: lesson-05.md "Topography"
[6]: lesson-06.md "Topography Advanced"
[7]: lesson-07.md "Framework"
[8]: lesson-08.md "Framework Advanced"
[9]: lesson-09.md "Personal Project"
[10]: lesson-10.md "Personal Project Consultation"
[11]: lesson-11.md "Domain, Hosting dan Github Pages"
[12]: lesson-12.md "Presentation"
