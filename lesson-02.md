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

---

### Tools
1. **Windows/Mac/Linux**: [Sublime](https://www.sublimetext.com)
2. **Browser**:
    * Google Chrome
    * Internet Explorer
    * Mozilla Firefox
    * Opera
    * Safari
    * Dll

---

### Material
#### 1. Eksternal CSS

##### a) Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- css
        |-- style.css

  ```

##### b) Insert CSS on HTML Page
  
  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Insert CSS on HTML Page
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
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

##### c) Styling Heading

  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Styling Heading
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
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

  * Isi file style.css:

  ```css

  h1{
    color: blue;
    text-align: center;
  }

  h2{
    color: red;
    text-align: right;
  }

  h3{
    color: green;
    text-align: left;
  }

  ``` 

##### d) Styling Pragraph


  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Styling Pragraph
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <p class="pull-right">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </p>
        
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </p>
        
        <p class="pull-right">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </p>

      </body>
    </html>

  ```

  * Isi file style.css:

  ```css

  p{
    color: purple;
  }

  .pull-right{
    text-align: right;
  }

  ```

##### e) Styling Anchor


  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Styling Anchor
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>

        <a href="https://www.google.co.id">
          Google 
        </a> 

        <a href="https://www.facebook.com/">
          Facebook 
        </a>  

        <a href="https://www.instagram.com"> 
          Instagram
        </a>

      </body>
    </html>  

  ```

  * Isi file style.css:

  ```css

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

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- images
        |-- icon-kolla.png

  ```

  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Insert Favicon on HTML Page
        </title>
        <link rel="icon" type="image/png" href="images/icon-kolla.png" sizes="32x32">
      </head>
      <body>

      </body>
    </html>  

  ```

#### 3 Paging
##### a) Eksternal Links

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- css
        |-- style.css
      +-- images
        |-- logo-facebook.png
        |-- logo-instagram.png
        |-- logo-youtube.png

  ```

  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Eksternal Links
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <a>
          <img src="images/logo-facebook.png">
          <img src="images/logo-instagram.png">
          <img src="images/logo-youtube.png">
        </a>
      </body>
    </html>  

  ```

  * Isi file style.css:

  ```css

  body {
    text-align: center;
  }

  img {
    width: 32px;
  }


  ``` 

##### b) Internal Links

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- images
        |-- icon-kolla.png

  ```

  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Internal Links
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>

      </body>
    </html>  

  ```

##### c) Navigation Menus

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- images
        |-- icon-kolla.png

  ```

  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Navigation Menus
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>

      </body>
    </html>  

  ```

##### d) Open Page on New Tab

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- images
        |-- icon-kolla.png

  ```

  * Isi file index.html:

  ```html

    <html>
      <head>
        <title>
          Navigation Menus
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>

      </body>
    </html>  

  ```

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
[2]: lesson-02.md "Anchor & Paging"
[3]: lesson-03.md "Typography"
[4]: lesson-04.md "Form & Embed"
[5]: lesson-05.md "Topography"
[6]: lesson-06.md "Topography"
[7]: lesson-07.md "Framework"
[8]: lesson-08.md "Framework Lanjut"
[9]: lesson-09.md "Personal Project"
[10]: lesson-10.md "Consutlation"
[11]: lesson-11.md "Domain, Hosting dan Github Pages"
[12]: lesson-12.md "Presentation"
