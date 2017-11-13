# CODING TEEN

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

---

### LESSON 04: FORM & EMBED

---

### Objectives
1. Peserta mengetahui cara membuat form pada HTML.
2. Peserta mengetahui cara membuat google form.
3. Peserta mengetahui cara menyisipkan google form pada halaman website.
4. Peserta mengetahui cara menyisipkan video youtube pada halaman website.
5. Peserta mengetahui cara menyisipkan video yang ada pada laptop pada halaman website.
6. Peserta mengetahui cara menyisipkan map pada halaman website.
7. Peserta mengetahui cara menyisipkan audio pada halaman website.

---

### Material
#### 1. Form

##### a) Text

  * Isi file `index.html`:

  ```html

	<input type="text" name="nama_lengkap" placeholder="Nama Lengkap">

  ```

##### b) Password

  * Isi file `index.html`:

  ```html

	<input type="password" name="password" placeholder="Password">


  ```

##### c) Email

  * Isi file `index.html`:

  ```html

	<input type="email" name="email" placeholder="Email">

  ```

##### d) Date

  * Isi file `index.html`:

  ```html

	<input type="date" name="tanggal_lahir" placeholder="Tanggal Lahir">

  ```

##### e) Checkbox

  * Isi file `index.html`:

  ```html

  <input type="checkbox" name="hobi[]" value="Sepak Bola"> Sepak Bola
  <input type="checkbox" name="hobi[]" value="Berenang"> Berenang 
  <input type="checkbox" name="hobi[]" value="Masak"> Masak 
  <input type="checkbox" name="hobi[]" value="Menggambar"> Menggambar 

  ```

##### f) Radio

  * Isi file `index.html`:

  ```html

  <input type="radio" name="jenis_kelamin" value="laki-laki" checked> Laki-laki
  <input type="radio" name="jenis_kelamin" value="perempuan"> Perempuan

  ```

##### g) Select

  * Isi file `index.html`:

  ```html

	<select name="kelas">
	  <option value="9">IX</option>
	  <option value="10">X</option>
	  <option value="11">XI</option>
	</select>

  ```

  ##### h) Multiple Select

  * Isi file `index.html`:

  ```html

  <select name="hobi">
    <option value="Sepak Bola">Sepak Bola</option>
    <option value="Berenang">Berenang</option>
    <option value="Masak">Masak</option>
  </select>

  ```

##### i) Text Area

  * Isi file `index.html`:

  ```html

	<textarea name="alamat" rows="4" cols="50">
	 Jl. H. Agus Salim no. 32B, lantai 2 Kebon Sirih, Menteng Jakarta Pusat 10340
	</textarea>

  ```

##### j) Button

  * Isi file `index.html`:

  ```html

	<input type="button" value="Cancle">
	<input type="submit" value="Submit">
	<input type="reset" value="Reset">

  ```

##### k) Form

  * Isi file `index.html`:

  ```html

  <html>
    <head>
      <title>
        Form
      </title>
    </head>
    <body>
      <h4>Form Pendaftaran Siswa</h4>
      <form method="GET" action="">
        <div>
            <label>Nama Lengkap</label>
            <input type="text" name="nama_lengkap" placeholder="Nama Lengkap">
        </div>
        <div>
            <label>Password</label>
            <input type="password" name="password" placeholder="Password">
        </div>
        <div>
            <label>Jenis Kelamin</label>
            <input type="email" name="email" placeholder="Email">
        </div>
        <div>
            <label>Tanggal Lahir</label>
            <input type="date" name="tanggal_lahir" placeholder="Tanggal Lahir">
        </div>
        <div>
            <label>Hobi</label>
            <div >
          <input type="checkbox" name="hobi[]" value="Sepak Bola"> Sepak Bola
          <input type="checkbox" name="hobi[]" value="Berenang"> Berenang 
          <input type="checkbox" name="hobi[]" value="Masak"> Masak 
          <input type="checkbox" name="hobi[]" value="Menggambar"> Menggambar 
        </div>
        </div>
        <div>
            <label>Jenis Kelamin</label>
            <div >
              <input type="radio" name="jenis_kelamin" value="laki-laki" checked> Laki-laki
          <input type="radio" name="jenis_kelamin" value="perempuan"> Perempuan
        </div>
        </div>
        <div>
            <label>Kelas</label>
        <select name="kelas">
          <option value="9">IX</option>
          <option value="10">X</option>
          <option value="11">XI</option>
        </select>
        </div>
        <div>
            <label>Alamat</label>
        <textarea name="alamat" >
        </textarea>
        </div>
        <div>
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
        </div>
      </form>
    </body>
  </html>

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


##### [Video tutorial membuat Google Form](https://www.youtube.com/embed/FvZPNIPFCs8)

##### b) Cara Menyisipkan Google Form Pada Website

  * Isi file `index.html`:

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

  * Isi file `style.css`:

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

  * Isi file `index.html`:

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

#### 4. Embed Video From Local Video

  * Isi file `index.html`:

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

#### 5. Embed Google Map
  * Mendapat Api Key Google
  1. Untuk menyisipkan website pada halaman web kita perlu membuat project di Google API Console.
  2. Akses <a href="https://console.developers.google.com/flows/enableapi?apiid=maps_backend,geocoding_backend,directions_backend,distance_matrix_backend,elevation_backend,places_backend&reusekey=true">Google API Console</a>.
  3. Buat atau pilih project.
  4. Klik tombol <b>"Setuju dan Lanjutkan"</b>. Akan tampil, tampilan di bawah ini.
  <img src="https://scontent-sin6-2.xx.fbcdn.net/v/t1.0-9/23472238_10211227187503562_2917962359015092834_n.jpg?oh=bf4611f4f582e20284905b495a85e2a9&oe=5A9421A4">
  5. Pilih <b>"Google Maps JavaScript API"</b>, lalu tekan tombol <b>"Kredensial apa yang saya butuhkan?"</b>.
  <img src="https://scontent-sin6-2.xx.fbcdn.net/v/t1.0-9/23517486_10211227200663891_2890477635700295732_n.jpg?oh=99c987468a87cf37197217ab28e0e6b8&oe=5A9414D0">
  6. Copy kunci API yang ada seperti pada gambar di atas. Kemudian tekan tombol <b>"Selesai"</b>.
  7. Selesai, kamu sudah memiliki kunci API untuk menggunakan Google Map.

  Isi file `index.html`:

  ```html

  <html>
    <head>
      <style>
         #map {
          height: 400px;
          width: 100%;
         }
      </style>
    </head>
    <body>
      <h3>My Google Maps Demo</h3>
      <div id="map"></div>
      <script>
        function initMap() {
          var uluru = {lat: -25.363, lng: 131.044};
          var map = new google.maps.Map(document.getElementById('map'), {
            zoom: 4,
            center: uluru
          });
          var marker = new google.maps.Marker({
            position: uluru,
            map: map
          });
        }
      </script>
      <script async defer
      src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDl6xFyvdKRwq4xhKoHhN6ZabtgdbRiq6o&callback=initMap">
      </script>
    </body>
  </html>


  ```

#### 6. Embed Audio

  * Isi file `index.html`:

  ```html

  <html>
    <head>
        <title>
          Embed Audio
        </title>
    </head>
    <body>
      <img src="images/happy-birthday.gif"><br>
      <audio src="audio/happy-birthday.mp3" autoplay controls></audio>
    </body>
  </html>

  ```
---

### Example Code
* [Lesson 4](https://github.com/kollaeducation/coding-teen-example-code/tree/master/day-04)

---
### Instruction
1. Buka sublime dan mulai menulis script.
2. Peserta diajarkan untuk membuat form pada HTML.
3. Peserta diajarkan untuk membuat google form.
4. Peserta diajarkan untuk menyisipkan google form pada halaman website.
5. Peserta diajarkan untuk menyisipkan video youtube pada halaman website.
6. Peserta diajarkan untuk menyisipkan video yang ada pada laptop pada halaman website.
7. Peserta diajarkan untuk menyisipkan map pada halaman website.
8. Peserta diajarkan untuk menyisipkan audio pada halaman website.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 04** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 04** ini?

---

### References

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
