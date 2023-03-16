# tugasweb01

1. Deklarasi kode html

   ```html
   <!DOCTYPE html>
   <html lang="en">

   <head>
       <meta charset="UTF-8">
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Pemrograman Web2</title>
       <link rel="stylesheet" href="style.css">
   </head>

   <body>
       <div class="container">
           <div class="header">
               <h1> Layout Sederhana</h1>
           </div>
           <div class="navigasi">
               <ul>
                   <li><a href="#">Home</a></li>
                   <li><a href="#">Artikel</a></li>
                   <li><a href="#">About</a></li>
                   <li><a href="#">Contact</a></li>
               </ul>
           </div>
           <div class="judul">
               <h1>Hello World!</h1>
               <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus rerum iusto officiis facere quo
                   autem? Numquam eaque iste assumenda consequatur, distinctio quis in consequuntur veniam, non vitae,
                   reprehenderit quas rem. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Mollitia culpa ullam
                   harum amet necessitatibus tempore quia dolorem atque. Nam exercitationem impedit quaerat nostrum dolorem
                   assumenda, numquam maiores ullam tenetur corrupti?</p>
               <button type="submit">Learn More>></button>
           </div>
           <div class="content cf">
               <div class="isi">
                   <div class="gallery">
                       <div class="gallery-item">
                           <img src="pat1.jpg" alt="Gambar 1">
                           <h3> Gambar 1</h3>
                       </div>
                       <div class="gallery-item">
                           <img src="pat2.png" alt="Gambar 2">
                           <h3> Gambar 2</h3>
                       </div>
                       <div class="gallery-item">
                           <img src="pat3.jpeg" alt="Gambar 3">
                           <h3> Gambar 3</h3>
                       </div>
                   </div>
                   <div class="content1">
                       <img src="patt.jpg">
                       <h3>Feature Heading 1</h3>
                       <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                           tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                           quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                           consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                           cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                           proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Lorem ipsum dolor sit
                           amet consectetur adipisicing elit. Fugit soluta voluptates, ducimus dolorum accusantium optio
                           harum est, fuga ipsum tenetur odit tempore laboriosam itaque dignissimos molestias quaerat
                           autem.<p>

                   </div>
                   <div class="content2">
                       <img src="patt.jpg">
                       <h3>Feature Heading 1</h3>
                       <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                           tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                           quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                           consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                           cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                           proident, sunt in culpa qui officia deserunt mollit anim id est
                       </p>
                   </div>

               </div>
               <div class="sidebar">
                   <h3>Kepoin Skuy</h3>
                   <img src="patt.jpg">
                   <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                       tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                       quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                       consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                       cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                       proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<p>
                           <h3>Kepoin Skuy</h3>
                           <img src="patt.jpg">
                           <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                               tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
                               quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
                               consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
                               cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
                               proident, sunt in culpa qui officia deserunt mollit anim id est laborum.<p>
               </div>
           </div>
           <div class="footer">
               <p class="copy">Copyright 2023. Leman .</p>
           </div>
       </div>
       </div>
   </body>

   </html>
   ```

2. Deklarasi code css yang terhubung ke html diatas

   ```css
   /* http://meyerweb.com/eric/tools/css/reset/ 
       v2.0 | 20110126
       License: none (public domain)
       */

   html,
   body,
   div,
   span,
   applet,
   object,
   iframe,
   h1,
   h2,
   h3,
   h4,
   h5,
   h6,
   p,
   blockquote,
   pre,
   a,
   abbr,
   acronym,
   address,
   big,
   cite,
   code,
   del,
   dfn,
   em,
   img,
   ins,
   kbd,
   q,
   s,
   samp,
   small,
   strike,
   strong,
   sub,
   sup,
   tt,
   var,
   b,
   u,
   i,
   center,
   dl,
   dt,
   dd,
   ol,
   ul,
   li,
   fieldset,
   form,
   label,
   legend,
   table,
   caption,
   tbody,
   tfoot,
   thead,
   tr,
   th,
   td,
   article,
   aside,
   canvas,
   details,
   embed,
   figure,
   figcaption,
   footer,
   header,
   hgroup,
   menu,
   nav,
   output,
   ruby,
   section,
   summary,
   time,
   mark,
   audio,
   video {
     margin: 0;
     padding: 0;
     border: 0;
     font-size: 100%;
     font: inherit;
     vertical-align: baseline;
   }

   /* HTML5 display-role reset for older browsers */
   article,
   aside,
   details,
   figcaption,
   figure,
   footer,
   header,
   hgroup,
   menu,
   nav,
   section {
     display: block;
   }

   body {
     line-height: 1;
   }

   ol,
   ul {
     list-style: none;
   }

   blockquote,
   q {
     quotes: none;
   }

   blockquote:before,
   blockquote:after,
   q:before,
   q:after {
     content: '';
     content: none;
   }

   table {
     border-collapse: collapse;
     border-spacing: 0;
   }

   /* style */

   body {
     font: 18/28px arial, sans-serif;
     background-image: url(bg.png);
   }

   .container {
     width: 960px;
     background-color: #fee3ec;
     margin: auto;
     position: relative;
   }

   .header h1 {
     background-color: #fee3ec;
     padding: 20px;
     font-weight: bold;
     color: rgb(253, 253, 253);
     font-size: 30px;
     font-style: bold;
     text-shadow: 3px 3px 11px rgb(112, 58, 58);
   }

   .navigasi {
     background-color: #f999b7;
   }

   .navigasi ul li {
     display: inline-block;
     margin: 10px 0px;
   }

   .navigasi a {
     text-decoration: none;
     color: #fcfafa;
     padding: 10px;
   }

   .navigasi a:hover {
     background-color: lightblue;
     color: black;
   }

   .judul h1 {
     color: #ffffff;
     font-size: 20px;
     font-weight: bold;
     padding-bottom: 10px;
   }

   .judul p {
     color: rgb(255, 255, 255);
     font-size: 18px;
   }

   .judul {
     border-top: 5px solid #fee3ec;
     border-bottom: 5px solid #f9c5d5;
     background-color: #f9c5d5;
     padding: 5px 20px 10px 20px;
   }

   button {
     background-color: #f27b9f;
     color: white;
     border-style: none;
     margin-top: 20px;
     padding: 5px 10px;
     border-radius: 10px;
   }

   button:hover {
     color: black;
     background-color: rgb(161, 159, 159);
   }

   .isi {
     width: 660px;
     padding: 20px;
     box-sizing: border-box;
     float: left;
   }

   .gallery {
     display: flex;
     flex-wrap: wrap;
   }

   .gallery-item {
     text-align: center;
   }

   .gallery-item img {
     border-radius: 50%;
     margin: 2px 53px;
     width: 100px;
     height: 100px;
   }

   .gallery-item h3 {
     color: #f06a92;
     margin-top: 5px;
     font-size: 21px;
     font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
   }

   .isi p {
     color: #f27b9f;
     margin-top: 20px;
     font-size: 18px;
   }

   .footer {
     padding: 10px;
     background-color: #f27b9f;
   }

   .footer .copy {
     color: white;
     text-align: center;
   }

   .sidebar {
     width: 250px;
     float: right;
     padding: 20px;
   }

   .sidebar h3 {
     color: #ffffff;
     font-size: 18px;
     background-color: #f27b9f;
     padding: 3px 0px;
     font-weight: bold;
     margin-bottom: 5px;
   }

   .sidebar img {
     float: left;
     width: 120px;
     height: 120px;
     margin-right: 10px;
   }

   .sidebar p {
     color: #f27b9f;
     font-size: 14px;
     margin-bottom: 20px;
   }

   .content1 {
     margin-top: 30px;
   }

   .content p {
     color: #f27b9f;
     font-size: 15px;
     font-family: Arial, Helvetica, sans-serif;
   }

   .content1 img {
     float: left;
     margin-right: 10px;
     width: 150px;
     height: 150px;
   }

   .content1 h3 {
     color: #f27b9f;
     font-weight: bold;
     font-size: 16px;
     margin-bottom: -10px;
   }

   .content2 h3 {
     color: #f27b9f;
     font-weight: bold;
     font-size: 16px;
     margin-bottom: -20px;
   }

   .content1 p {
     color: #f27b9f;
     margin-bottom: 30px;
   }

   .content2 p {
     margin-top: 30px;
   }

   .content2 img {
     float: right;
     width: 150px;
     height: 150px;
     margin-right: 10px;
   }

   /* m */
   .cf:before,
   .cf:after {
     content: ' ';
     /* 1 */
     display: table;
     /* 2 */
   }

   .cf:after {
     clear: both;
   }

   /**
       * For IE 6/7 only
       * Include this rule to trigger hasLayout and contain floats.
       */
   .cf {
     *zoom: 1;
   }
   ```

3. Hasilnya akan seperti ini
   ![Gambar 1](hasil.png)
