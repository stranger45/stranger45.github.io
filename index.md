
<!DOCTYPE html>
<!-- Sam Gainer 
    last modified 2/22/2021-->
<html lang="en US">
    <head>
        <link rel="stylesheet" type="text/css" href="samstyle.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <title>MG Paintings | Home</title>
        <h1>Murray Gainer Paintings | <span class ="page">Home</span></h1>
        <script src="jquery-3.5.1.js"></script>
        <script src = "samq.js"></script>

    <script>
      $(document).ready(function(){
        $(":image").fadeIn();
      });
    </script>
    </head>

    <body>
      
      
        <div class ="nav">
            <nav>
                <a href="mur.html">HOME</a>
                <a href="gallery.html">GALLERY</a>
                <a href="archive.html">ARCHIVE</a>
                <a href="about.html">ABOUT</a>
                <a href="contact.html">CONTACT US</a>
            </nav>
        </div>

    <p> <span id = "greet"> Greetings; </span> this is a web page dedicated to the artwork of Murray Gainer.</p>
    <p> <span id = "visit"> Enjoy your visit; Use the top menu to navigate the page. </span> </p>

        
        <script>    // Script is placed at the bottom of the <body> element to improve display speed as recomended on w3schools.com
          var date = new Date();     // Using Date() function to get the current date and storing it in a variable called "date"
          var hour = date.getHours();    // Using getHours() function to get the current hour of the day and store it as variable "hour"

          if (hour > 4 && hour < 12)  // Conditional statement that will output "Good Morning" if the current time is between 4am - 12pm
          {
          document.getElementById("greet").innerHTML = "Good Morning;";
          } 
          else if (hour < 18)        // Else if the current hours is between 12pm - 6pm it will read "Good Afternoon"
          {
            document.getElementById("greet").innerHTML = "Good Afternoon;"
          }
          else if (hour == 0)       // Else if the current hours is midnight 12am it will display a cryptic message
          {
            document.getElementById("greet").innerHTML = "It is the witching hour;"
          }
          else                      // And if the hours is between 6pm - 4am it will read "Good Evening"
          {
            document.getElementById("greet").innerHTML = "Good Evening;"
          }
          // document.write("Today's date is " + date);  //Removed this from the page
        </script>  

        <script>  // will display birthday message on two days of the year
          var date = new Date();
          var month = date.getMonth();
          var day = date.getDate();
          if (month == 2 && day == 8)
          {
            document.getElementById("visit").innerHTML = "Happy Birthday Sam!";
          } else if (month == 3 && day == 22)
          {
            document.getElementById("visit").innerHTML = "Happy Birthday Murray!";
          }
        </script>

<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 22</div>
    <img src="1.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 22</div>
    <img src="2.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 22</div>
    <img src="3.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">4 / 22</div>
    <img src="4.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">5 / 22</div>
    <img src="5.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">6 / 22</div>
    <img src="6.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">7 / 22</div>
    <img src="7.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">8 / 22</div>
    <img src="8.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">9 / 22</div>
    <img src="9.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">10 / 22</div>
    <img src="10.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">11 / 22</div>
    <img src="11.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">12 / 22</div>
    <img src="12.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">13 / 22</div>
    <img src="13.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">14 / 22</div>
    <img src="14.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">15 / 22</div>
    <img src="15.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">16 / 22</div>
    <img src="16.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">17 / 22</div>
    <img src="17.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>
  
  <div class="mySlides fade">
    <div class="numbertext">18 / 22</div>
    <img src="18.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">19 / 22</div>
    <img src="19.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">20 / 22</div>
    <img src="20.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">21 / 22</div>
    <img src="21.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">22 / 22</div>
    <img src="22.jpg" style="width:100%">
    <div class="text">Gainer, Murray. <em>Untitled.</em> 2020. Acrylic on canvas. [36" x 28"]</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>



<script>  //Script used from W3Schools to help make a slide show of all paintings on the page that the user can click through.  Buttons are on the side and a fade effect is used for a nice transition.
  var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}
//end of slide
</script>


 
  </body>
    <br><br>

   <address>Web page created by Sam Gainer <br> Last updated 2/22/2021</address>

</html>
