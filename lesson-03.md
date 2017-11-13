# CODING TEEN

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

---

### LESSON 03: TYPOGRAPHY

---

### Objectives
1. Peserta mampu membuat list.
2. Peserta mengerti text dan font formating.
3. Peserta mengerti style pada text, font, dan list.

---

### Material
#### 1. Lists

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html

  ```

##### a) Ordered List

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Ordered List
        </title>
      </head>
      <body>
        <ol>
          <li>Coffee
            <ol>
              <li>Coffee 1</li>
              <li>Coffee 2</li>
              <li>Coffee 3</li>
            </ol>
          </li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
      </body>
    </html>

  ```

##### b) Ordered List Bullet Type

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Ordered List Bullet Type
        </title>
      </head>
      <body>
        <ol type="a">
          <li>Coffee
            <ol type="i">
              <li>Coffee 1</li>
              <li>Coffee 2</li>
              <li>Coffee 3</li>
            </ol>
          </li>
          <li>Tea</li>
          <li>Milk</li>
        </ol>
      </body>
    </html>

  ```

##### c) Unordered List

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Unordered List
        </title>
      </head>
      <body>
        <ul>
          <li>Coffee
            <ul>
              <li>Coffee 1</li>
              <li>Coffee 2</li>
              <li>Coffee 3</li>
            </ul>
          </li>
          <li>Tea</li>
          <li>Milk</li>
        </ul>
      </body>
    </html>

  ```

##### d) Unordered List Bullet Type

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Unordered List Bullet Type
        </title>
      </head>
      <body>
        <ul type="square">
          <li>Coffee
            <ul type="circle">
              <li>Coffee 1</li>
              <li>Coffee 2</li>
              <li>Coffee 3</li>
            </ul>
          </li>
          <li>Tea</li>
          <li>Milk</li>
        </ul>
      </body>
    </html>

  ```

#### 2. Inline Elements For Text Formating


  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html

  ```

##### a) &lt;em&gt;

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Inline Elements For Text Formating
        </title>
      </head>
      <body>
        <p>
          Artikel adalah karangan faktual secara lengkap dengan panjang tertentu yang dibuat untuk dipublikasikan (melalui koran, majalah, <em>buletin</em>, dsb) dan bertujuan menyampaikan gagasan dan fakta yang dapat meyakinkan, mendidik, dan menghibur.
        </p>
      </body>
    </html>

  ```

##### b) &lt;strong&gt;

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Inline Elements For Text Formating
        </title>
      </head>
      <body>
        <p>
          <strong>Artikel</strong> adalah karangan faktual secara lengkap dengan panjang tertentu yang dibuat untuk dipublikasikan (melalui koran, majalah, <em>buletin</em>, dsb) dan bertujuan menyampaikan gagasan dan fakta yang dapat meyakinkan, mendidik, dan menghibur.
        </p>
      </body>
    </html>

  ```

#### 3. Fonts

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html

  ```

##### a) Font Family

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Font Family
        </title>
        <link href="https://fonts.googleapis.com/css?family=Indie+Flower" rel="stylesheet">
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <p>
          Artikel adalah karangan faktual secara lengkap dengan panjang tertentu yang dibuat untuk dipublikasikan (melalui koran, majalah, <em>buletin</em>, dsb) dan bertujuan menyampaikan gagasan dan fakta yang dapat meyakinkan, mendidik, dan menghibur.
        </p>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css

  body {
    font-family: 'Indie Flower', cursive;
  }

  ``` 

#### 4. CSS Text

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- css
        |-- style.css

  ```

##### a) Text Color

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          CSS Text
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Apa itu Artikel?</h2>
        <p>
          Artikel adalah karangan faktual secara lengkap dengan panjang tertentu yang dibuat untuk dipublikasikan (melalui koran, majalah, buletin, dsb) dan bertujuan menyampaikan gagasan dan fakta yang dapat meyakinkan, mendidik, dan menghibur.
        </p>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css
  h2{
    color: blue;
  }

  p{
    color: green;
  }

  ``` 

##### b) Text Alignment

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          Text Color
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Apa itu Artikel?</h2>
        <p>
          Artikel adalah karangan faktual secara lengkap dengan panjang tertentu yang dibuat untuk dipublikasikan (melalui koran, majalah, buletin, dsb) dan bertujuan menyampaikan gagasan dan fakta yang dapat meyakinkan, mendidik, dan menghibur.
        </p>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css

  h2{
    color: blue;
    text-align: center;
  }

  p{
    color: green;
    text-align: right;
  }

  ``` 

#### 5. CSS Fonts

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- css
        |-- style.css

  ```

##### a) Font Style

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          CSS Fonts
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Apa itu Sepeda Motor?</h2>
        <p>
        Sepeda motor adalah kendaraan beroda dua yang digerakkan oleh sebuah mesin. Letak kedua roda sebaris lurus dan pada kecepatan tinggi sepeda motor tetap stabil disebabkan oleh gaya giroskopik. Sedangkan pada kecepatan rendah, kestabilan atau keseimbangan sepeda motor bergantung kepada pengaturan setang oleh pengendara. 
        </p>
        <span class="author">Heraclitus</span>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css

  .author{
    font-style: italic;
  }

  ``` 

##### b) Font Size

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          CSS Fonts
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Apa itu Sepeda Motor?</h2>
        <p>
        Sepeda motor adalah kendaraan beroda dua yang digerakkan oleh sebuah mesin. Letak kedua roda sebaris lurus dan pada kecepatan tinggi sepeda motor tetap stabil disebabkan oleh gaya giroskopik. Sedangkan pada kecepatan rendah, kestabilan atau keseimbangan sepeda motor bergantung kepada pengaturan setang oleh pengendara. 
        </p>
        <span class="author">Heraclitus</span>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css

  body{
    font-size: 14px;
  }

  .author{
    font-style: italic;
  }

  ``` 

##### c) Font Weight

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          CSS Fonts
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Apa itu Sepeda Motor?</h2>
        <p>
        <span class="tebal">Sepeda motor</span> adalah kendaraan beroda dua yang digerakkan oleh sebuah mesin. Letak kedua roda sebaris lurus dan pada kecepatan tinggi sepeda motor tetap stabil disebabkan oleh gaya giroskopik. Sedangkan pada kecepatan rendah, kestabilan atau keseimbangan sepeda motor bergantung kepada pengaturan setang oleh pengendara. 
        </p>
        <span class="author">Heraclitus</span>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css


  body{
    font-size: 14px;
  }

  .author{
    font-style: italic;
  }

  .tebal{
    font-weight: bolder;
  }


  ``` 

##### d) Font Variant

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          CSS Fonts
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Apa itu Sepeda Motor?</h2>
        <p>
        <span class="tebal">Sepeda motor</span> adalah kendaraan beroda dua yang digerakkan oleh sebuah mesin. Letak kedua roda sebaris lurus dan pada kecepatan tinggi sepeda motor tetap stabil disebabkan oleh gaya giroskopik. Sedangkan pada kecepatan rendah, kestabilan atau keseimbangan sepeda motor bergantung kepada pengaturan setang oleh pengendara. 
        </p>
        <span class="author">Heraclitus</span>
      </body>
    </html>


  ```

  * Isi file `style.css`:

  ```css

  body{
    font-size: 14px;
  }

  .author{
    font-style: italic;
  }

  .tebal{
    font-weight: bolder;
  }

  h2{
    font-variant: small-caps;
  }

  ``` 

#### 6. CSS Lists

  * Struktur Folder

  ```text

    +-- nama-folder
      |-- index.html
      +-- css
        |-- style.css

  ```

##### a) List Style Type

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          List Style Type
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Menu Minuman</h2>
        <ul class="minuman">
          <li>Ice Blend Coffee</li>
          <li>Ice Blend Strawberry Javachip</li>
          <li>Ice Blend Cookies dan Cream</li>
        </ul>

        <h2>Menu Makanan</h2>
        <ul class="makanan">
          <li>Coffee Cake</li>
          <li>Strawberry Cake</li>
          <li>Cookies dan Cream</li>
        </ul>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css

    .minuman li{
     list-style-type: square;
   }

   .makanan li{
     list-style-type: circle;
   }

  ``` 

##### b) List Style Position

  * Isi file `index.html`:

  ```html

    <html>
      <head>
        <title>
          List Style Type
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
      </head>
      <body>
        <h2>Menu Minuman</h2>
        <p>
          Kami memiliki beberapa menu minuman yang dapat memberikan kesegaran kepada Anda.
        </p>
        <ul class="minuman">
          <li>Ice Blend Coffee</li>
          <li>Ice Blend Strawberry Javachip</li>
          <li>Ice Blend Cookies dan Cream</li>
        </ul>

        <h2>Menu Makanan</h2>
        <p>
          Kami memiliki beberapa menu makanan yang dapat memanjakan lidah Anda.
        </p>
        <ul class="makanan">
          <li>Coffee Cake</li>
          <li>Strawberry Cake</li>
          <li>Cookies dan Cream</li>
        </ul>
      </body>
    </html>

  ```

  * Isi file `style.css`:

  ```css

    .minuman li{
     list-style-type: square;
     list-style-position: inside;
   }

   .makanan li{
     list-style-type: circle;
     list-style-position: outside;
   }


  ``` 

---

### Example Code
* Untuk contoh penulisan code pada kurikulum ini bisa di download pada [LINK INI](https://github.com/kollaeducation/coding-teen-example-code/archive/master.zip).

---

### Instruction
1. Buka sublime dan mulai menulis script.
2. Peserta diajarkan untuk mengerti cara membuat list.
2. Peserta diajarkan untuk mengerti cara melakukan text dan font formating.
3. Peserta diajarkan untuk bisa memberikan style pada text, font, dan list.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 03** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 03** ini?

---

### References
* [Lesson 3](https://github.com/kollaeducation/coding-teen-example-code/tree/master/day-03)

---
| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

[0]: README.md "Home"
[1]: lesson-01.md "Web Technology"
[2]: lesson-02.md "HTML dan CSS"
[3]: lesson-03.md "Typography"
[4]: lesson-04.md "Form dan Embed"
[5]: lesson-05.md "Topography"
[6]: lesson-06.md "Topography Advanced"
[7]: lesson-07.md "Framework"
[8]: lesson-08.md "Framework Advanced"
[9]: lesson-09.md "Personal Project"
[10]: lesson-10.md "Personal Project Consultation"
[11]: lesson-11.md "Domain, Hosting dan Github Pages"
[12]: lesson-12.md "Presentation"
