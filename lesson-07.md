# CODING TEEN

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

---

### LESSON 07: INTRO TO FRAMEWORK

---

### Objectives
1. Peserta mengetahui framework sebagai alat bantu pemercepat pembuatan website.
2. Peserta mampu membangun website menggunakan framework Bootstrap.

---

### Material

#### 1. Preparation
* Download [Bootstrap](https://github.com/twbs/bootstrap/releases/download/v3.3.7/bootstrap-3.3.7-dist.zip)
* Pindahkan file bootstrap-3.3.7-dist.zip ke dalam project website kamu.
* Ekstrak file bootstrap-3.3.7-dist.zip, lalu ubah nama folder menjadi bootstrap.
* Struktur folder akan seperti di bawah ini.

  ```text

    +-- nama-folder
      |-- index.html
      +-- bootstrap
        +-- js
          |-- bootstrap.js
          |-- bootstrap.min.js  
          |-- npm.js
        +-- fonts
          |-- glyphicons-halflings-regular.eot
          |-- glyphicons-halflings-regular.woff
          |-- glyphicons-halflings-regular.svg
          |-- glyphicons-halflings-regular.woff2
          |-- glyphicons-halflings-regular.ttf
        +-- css
          |-- bootstrap.css
          |-- bootstrap.min.css.map
          |-- bootstrap-theme.min.css
          |-- bootstrap.css.map
          |-- bootstrap-theme.css
          |-- bootstrap-theme.min.css.map
          |-- bootstrap.min.css
          |-- bootstrap-theme.css.map

  ```

#### 2. Container and Row sebagai parent dari kolom-kolom.

* Bootstrap 1 Kolom

  ```html

  <html>
    <head>
      <title>
        Bootstrap 1 Kolom
      </title>
        <link rel="stylesheet" type="text/css" href="bootstrap/css/bootstrap.css">
    </head>
    <body>
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            Satu kolom
          </div>
        </div>
      </div>
    </body>
  </html>

  ```

* Bootstrap 2 Kolom

  ```html

  <html>
    <head>
      <title>
        Bootstrap 2 Kolom
      </title>
        <link rel="stylesheet" type="text/css" href="bootstrap/css/bootstrap.css">
    </head>
    <body>
      <div class="container">
        <div class="row">
          <div class="col-xs-6">
            Kolom 1
          </div>
          <div class="col-xs-6">
            Kolom 2
          </div>
        </div>
      </div>
    </body>
  </html>

  ```

* Bootstrap 3 Kolom

  ```html

  <html>
    <head>
      <title>
        Bootstrap 3 Kolom
      </title>
        <link rel="stylesheet" type="text/css" href="bootstrap/css/bootstrap.css">
    </head>
    <body>
      <div class="container">
        <div class="row">
          <div class="col-xs-4">
            Kolom 1
          </div>
          <div class="col-xs-4">
            Kolom 2
          </div>
          <div class="col-xs-4">
            Kolom 3
          </div>
        </div>
      </div>
    </body>
  </html>

  ```
  
* Bootstrap 3 Kolom Kompleks

  ```html

  <div class="container">
      <div class="row">
          <div class="col-xs-4 merah">
              <div class="anak1">
                  <h4>Anak 1</h4>
                  <p>Ini paragraf Ini paragraf Ini paragraf</p>
              </div>
          </div>
          <div class="col-xs-4 orange">
              <div class="row">
                  <div class="col-xs-12 orange">Cucu 1</div>
                  <div class="col-xs-12 ungu">Cucu 2</div>
              </div>
          </div>
          <div class="col-xs-4 hijau">
            <div class="row">
                <div class="col-xs-12 ungu">Cucu 1</div>
                <div class="col-xs-12 orange">
                    <div class="row">
                       <div class="col-xs-6 hijau">Cicit 1</div>
                       <div class="col-xs-6 merah">Cicit 2</div>
                    </div>
                </div>
            </div>
          </div>
      </div>
  </div>

  ```

#### 2. CSS pembantu

* CSS `style.css`

  ```css
  .merah {
      background-color: red;
  }
  .ungu {
      background-color: purple;
  }
  .hijau {
      background-color: green;
  }
  .orange {
      background-color: orange;
  }
  .hitam {
      background-color: black;
  }
  .anak1 {
      margin-left: 20px;
  }
  
  ```
---

### Example Code
* [Lesson 7](https://github.com/kollaeducation/coding-teen-example-code/tree/master/day-07)

---

### Exercises
1. Peserta membuat 4 kolom menggunakan Bootstrap.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 07** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 07** ini?

---

### References
1. [Bootstrap Official](http://getbootstrap.com/ "Bootstrap Official")
2. [Front-End Web UI Frameworks and Tools](https://www.coursera.org/learn/web-frameworks "Front-End Web UI Frameworks and Tools")
2. [Introduction to Bootstrap](https://www.edx.org/course/introduction-bootstrap-tutorial-microsoft-dev203x-2 "Introduction to Bootstrap")

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
