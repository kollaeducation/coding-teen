# CODING TEEN

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

---

### LESSON 02: ANCHOR & PAGING

---

### Objectives
1. Peserta mampu memetakan dan membedakan berbagai macam teknologi dalam pembuatan website.
2. Peserta mampu mengenali struktur dasar layout dalam suatu website.
    * html
    * head
    * body
    * title
    * meta description
3. Peserta mampu mengenali beberapa tag yang sering digunakan dalam pembuatan website.   

### Tools
1. **Windows/Mac/Linux**: [Sublime](https://www.sublimetext.com)
2. **Browser**:
    * Google Chrome
    * Internet Explorer
    * Mozilla Firefox
    * Opera
    * Safari
    * Dll

### Material

#### 1. Eksternal CSS

##### a) Insert CSS on HTML Page
  * Siapkan sebuah folder dengan nama eksternal-css.
  * Di dalam folder eksternal-css, buat sebuah file dengan nama index.html dan sebuah folder dengan nama css.
  * Di dalam folder css buat file dengan nama style.css.
  * Berikut struktur file dan folder yang ada di dalam folder eksternal-css:

  ```text
  |-- eksternal-css
        |-- index.html
        |-- css
              |-- style.css
  ```
  
  * Isi file index.html:

  ```html
    <html>
      <head>
        <title>
          Kolla
        </title>
        <link rel="stylesheet" type="text/css" href="style.css">
      </head>
      <body>

      </body>
    </html>
  ```

  * Isi file style.css:

  ```css
  body {
    color: #4c4c4c;
    background-color: #f9fbff;
  }
  ``` 

##### b) Styling heading
  * Masih di dalam file index.html yang sama, tambahkan tag heading 1, heading 2, dan heading 3 seperti pada tulisan di bawah ini:

  ```html
    <html>
      <head>
        <title>
          Styling heading
        </title>
        <link rel="stylesheet" type="text/css" href="style.css">
      </head>
      <body>
        <h1>Judul</h1>

        <h2>Sub Judul</h2>

        <h3>Poin 1</h3>
        
        <h3>Poin 2</h3>
        
        <h3>Poin 3</h3>

      </body>
    </html>
  ```

  * Tambahkan style untuk heading dalam file style.css

  ```css
  body {
    color: #4c4c4c;
    background-color: #f9fbff;
  }

  h1{
    color: blue;
  }

  h2{
    color: red;
  }

  h3{
    color: green;
  }
  ``` 

##### c) Styling pragraph
  * Masih di dalam file index.html yang sama, tambahkan tag paragraf seperti pada tulisan di bawah ini:

  ```html
    <html>
      <head>
        <title>
          Styling pragraph
        </title>
        <link rel="stylesheet" type="text/css" href="style.css">
      </head>
      <body>
        <h1>Judul</h1>

        <h2>Sub Judul</h2>

        <h3>Poin 1</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        
        <h3>Poin 2</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        
        <h3>Poin 3</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>

      </body>
    </html>
  ```

  * Tambahkan style untuk paragraf dalam file style.css

  ```css
  body {
    color: #4c4c4c;
    background-color: #f9fbff;
  }

  h1{
    color: blue;
  }

  h2{
    color: red;
  }

  h3{
    color: green;
  }

  p{
    color: purple;
  }
  ```

##### d) Styling anchor
  * Masih di dalam file index.html yang sama, tambahkan tag anchor yang akan memanggil eksternal page google, facebook, dan instagram:

  ```html
    <html>
      <head>
        <title>
          Styling pragraph
        </title>
        <link rel="stylesheet" type="text/css" href="style.css">
      </head>
      <body>
        <h1>Judul</h1>

        <h2>Sub Judul</h2>

        <h3>Poin 1</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        
        <h3>Poin 2</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        
        <h3>Poin 3</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        <a href="https://www.google.co.id"> Google </a> | <a href="https://www.facebook.com/"> Facebook </a> | <a href="https://www.instagram.com"> Instagram</a>

      </body>
    </html>  
  ```

  * Tambahkan style untuk anchor dalam file style.css

  ```css
  body {
    color: #4c4c4c;
    background-color: #f9fbff;
  }

  h1{
    color: blue;
  }

  h2{
    color: red;
  }

  h3{
    color: green;
  }

  p{
    color: purple;
  }
  a {
    color: #4b007a;
  }

  a:hover{
    background-color: yellow;
  }  

  a:visited{
    color: #7a0016;
  }

  a:active{
    background-color: #66ffef;
  } 

  a:link{
    color: #007a75;
  }      

  body {
    text-align: center;
  }
  ```  

#### 2. Favicon
##### a) Insert Favicon on HTML Page

#### 3 Paging
##### a) Navigation menus
##### b) Eksternal links
##### c) Internal links
##### d) Open Page on New Tab

---

### Instruction
1. Buka beberapa website. Tunjukkan kepada peserta bagian struktur dasar dari setiap website:
    * html
    * head
    * body
    * title
    * meta description
2. Peserta diajarkan untuk mengerti perbedaan dari penomoran pada heading, menyisipkan link pada teks, dan membuat paragraf.
2. Peserta diajarkan untuk menyisipkan gambar.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 01** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 01** ini?

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
