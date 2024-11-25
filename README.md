<!DOCTYPE html>

<!-- Fig. 2.1: main.html -->
<!-- First HTML5 example. -->
<html>
   <head>
      <meta charset = "utf-8">
      <title>My Webpage</title>
     <style type = "text/css">
         h1 
         { 
            text-shadow: -12px 12px 14px dimgrey; /* add shadow */
            font-size: 400%; /* increasing the font size */
         }
        .floated { background-color: skyBlue;
                    font-size: 1.5em;
                    font-family: arial, helvetica, sans-serif;
                    padding: .2em;
                    margin-left: .5em;
                    margin-bottom: .5em;
                    float: right;
                    text-align: left;
                    width: 15%; }
       @media print
         {
            body  { background-color: white; }
            h2    { color: Red; }
            p     { font-size: 14pt;
                    color: SteelBlue;
                    font-family: "times new roman", times, serif; }
         }
       img
         {
            margin: 80px;
            -webkit-transition: -webkit-transform 4s; 
            -moz-transition: -moz-transform 4s; 
            -o-transition: -o-transform 4s; 
            transition: transform 4s;
         }
         img:hover
         {
            -webkit-transform: rotate(360deg) scale(2, 2); 
            -moz-transform: rotate(360deg) scale(2, 2);
            -o-transform: rotate(360deg) scale(2, 2); 
            transform: rotate(360deg) scale(2, 2);
         } 

      </style>
     <script>

         window.alert( "Welcome, my name is Roberto and this is my webpage." );

      </script>
   </head>
 <body>
 <style>
  h1 {font-family: Brush Script MT; font-size: 400%; text-align: center;
      margin-bottom: .5em; background-color: DarkSeaGreen;width: 100% }

  body {color: blue;}
 </style>
      <h1>Roberto A. Chavez</h1>
   </body>

   <body>
    <section>
      <h2 class = "floated">Welcome to my website!! Here you'll find my self introduction, thanks for visiting my site. </h2>
    </section>
      <b>I am a computer science major student part time and work full time in hopes to leave a physically labor tasked job. The reason I chose computer science as my major, as well as career field, was the versatility there is when it comes to employment. From building websites for an orgabackgrunization to protecting sensitive information for privacy reasons. It still has the sensation of being able to take something new from scratch and create something that can not only help myself out but also others. A sensation that I currently have as a mechanic where at occasions I must fabricate things to fit what I am trying to repair. Plus working with my hands has always felt comfortable to me, now I will tone down the physical labor to just my hands on a keyboard once I graduate. I chose UHD for how affordable it is and the class sizes work best for me compared to being in a lecture with over fifty other students. In my time outside of school and work I enjoy my favorite past times such as reading for entertainment, lifting weights, and watching movies. They all help me unwind and relieve some stress from the everyday routine that I have. Below is a link that will take you to the UHD website.  </b>
      <p><a href = "https://www.uhd.edu/">University of Houston Downtown</a></p>
      <p>
         <img src = "ME.jpg" width = "180" height = "250"
            alt = "A picture of me">        
         
      </p>
      <p>The following table also gives some more direct information about myself such as favorite food, music, and other things.
      </p>
</table>
<table style="width: 10%;" border="2">
<tbody>
<tr>
<td>Food</td>
<td>Tacos</td>
</tr>
<tr>
<td>Color</td>
<td>Green</td>
</tr>
<tr>
<td>Drink</td>
<td>Topo Chico Mineral Water</td>
</tr>
<tr>
<td>Movie Genre</td>
<td>Action</td>
</tr>
<tr>
<td>Music</td>
<td>Mexican Regional</td>
</tr>
</tbody>
</table> 
      <p>Since you’ve learned quite a bit about me, I would like to know something about you. Let’s make it easy, below is a form where you can choose a color from the pop-up box that appears. Go ahead and show me your favorite color by choosing it from the pop-up box.
      </p>
      <p>
            <label>Your Favorite Color:
               <input type = "color" autofocus /> 
                  (Press enter once you found your favorite color)
            </label>
      </p>
   </body>
</html>
