# CODING TEEN

| [Home][0] | [01][1] | [02][2] | [03][3] | [04][4] | [05][5] | [06][6] | [07][7] | [08][8] | [09][9] | [10][10] | [11][11] | [Presentation][12] |
|:---------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:--------:|:--------:|:------------------:|

---

### LESSON 06: TOPOGRAPHY

---

### Objectives
1. Peserta dikenalkan tentang Web Structure.

---

### Material

<img src="https://www.w3schools.com/html/img_sem_elements.gif">

#### Keterangan:
###### `<header>` - Mendefinisikan header sebuah website
###### `<nav>` - Mendefinisikan menu
###### `<section>` - Mendefinisikan bagian-bagian dari sebuah website
###### `<article>` - Mendefinisikan bahwa bagian tersebut berisi artikel pada sebuah website
###### `<aside>` - Mendefinisikan sidebar dari sebuah website
###### `<footer>` - Mendefinisikan footer sebuah website

* Isi file `index.html`:

  ```html

  <html>
    <head>
        <title>
          Web Structure
        </title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
    </head>
    <body>
      <div class="container">
        <header>
           <h1>City Gallery</h1>
        </header>
        <nav>
          <ul>
            <li><a href="#">London</a></li>
            <li><a href="#">Paris</a></li>
            <li><a href="#">Tokyo</a></li>
          </ul>
        </nav>
        <article>
          <h1>London</h1>
          <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
          <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
        </article>
        <footer>Copyright &copy; W3Schools.com</footer>
      </div>
    </body>
  </html>


  ```
  
* Isi file `style.css`:

  ```css


  div.container {
      width: 100%;
      border: 1px solid gray;
  }

  header, footer {
      padding: 1em;
      color: white;
      background-color: black;
      clear: left;
      text-align: center;
  }

  nav {
      float: left;
      max-width: 160px;
      margin: 0;
      padding: 1em;
  }

  nav ul {
      list-style-type: none;
      padding: 0;
  }
     
  nav ul a {
      text-decoration: none;
  }

  article {
      margin-left: 170px;
      border-left: 1px solid gray;
      padding: 1em;
      overflow: hidden;
  }

  ```

---

### Example Code
* Untuk contoh penulisan code pada kurikulum ini bisa di download pada [LINK INI](https://github.com/kollaeducation/coding-teen-example-code/archive/master.zip).

---

### Instruction
1. Buka sublime dan mulai menulis script.
2. Peserta diajarkan untuk mengerti stuktur dari sebuah website.

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 06** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 06** ini?

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
