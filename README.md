<html lang="en"><head>
  <title>Page Title</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">a
  <link rel="stylesheet" href="styles.css">
  <!-- <link rel="stylesheet" href="myCSS.css" />-->
</head>
<body>
  <!-- Slideshow container -->
  <div class="slideshow-container">
    <!-- Full-width images with number and caption text -->
    <div class="mySlides fade" style="display: none;">
      <div class="numbertext">1 / 4</div>
      <img src="images/header1.png" style="width: 100%">
    </div>

    <div class="mySlides fade" style="display: block;">
      <div class="numbertext">2 / 4</div>
      <img src="images/header2.png" style="width: 100%">
    </div>

    <div class="mySlides fade" style="display: none;">s
      <div class="numbertext">3 / 4</div>
      <img src="images/header3.png" style="width: 100%">
    </div>

    <div class="mySlides fade" style="display: none;">
      <div class="numbertext">4 / 4</div>
      <img src="images/header4.png" style="width: 100%">
    </div>
    
    <div class="mySlides fade" style="display: none;">
      <div class="numbertext">5 / 5</div>
      <img src="images/งานออกแบบที่ไม่มีชื่อ.png" style="width: 100%">
    </div>

    <!-- Next and previous buttons -->
    <a class="prev" onclick="plusSlides(-1)">❮</a>
    <a class="next" onclick="plusSlides(1)">❯</a>
  </div>

  <!-- The dots/circles 
  <div style="text-align: center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>-->
  <!---->
  <div class="navbar">
    <a href="index.html">Home</a>
    <a href="portfolio.html">portfolio</a>
    <a href="about.html">About me</a>
    <a href="table.html">ตารางเรียน</a>
    <a href="http://www.pccpl.ac.th/">PCSHSPL</a>
      </div>
    </div>
  </div>
  <div class="row">
    <!--<div class="side">
      <h2>About Me</h2>
      <h5>Photo of me:</h5>
      <div class="aboutme"></div>
      <image src="images/aboutme.png" />
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      <h3>More Text</h3>
      <p>Lorem ipsum dolor sit ame.</p>
      <div class="fakeimg" style="height: 60px">Image</div>
      <br />
      <div class="fakeimg" style="height: 60px">Image</div>
      <br />
      <div class="fakeimg" style="height: 60px">Image</div>
    </div>-->
    <div class="main">
      <h2>Uchiwa itachi</h2>
      <h5>Sharingan flawless</h5>
      <img src="images/itaji.jpg" style="height: 200px">
      <p>Nobody have fight me.</p>
      <p>
        I have STRONG Sharingan
      </p>
      <br>
      <h2>Sharingan</h2>
      <h5>Fuv color black red</h5>
      <div class="fakeing" style="height: 200px"></div>
      <p>Some text..</p> 
      <p>
        i am perfection No one dared to fight with me.
      </p>
      <br>   
      <h2>PCCPL about.</h2>
     
      <button class="accordion">ปรัชญาโรงเรียน</button>
      <div class="panel">
      <p>“ปัญญายัตถัง วิปัสสะติ”(คนย่อมเห็นเนื้อความด้วยปัญญา) หมายถึง ปัญญาเกิดขึ้นด้วยเหตุ 3 ประการ
          สุตมยปัญญา : ปัญญาสำเร็จได้ด้วยการฟัง
          จินตมยปัญญา : ปัญญาสำเร็จได้ด้วยการนึกคิด
          ภาวนามยปัญญา : ปัญญาสำเร็จได้ด้วยการฝึก
     </p>
     </div>

     <button class="accordion">คำขวัญโรงเรียน</button>
<div class="panel">
  <p>รักษ์ศักดิ์ศรี มีคุณธรรม นำวิชาการ สืบสานงานพระราชดำริ</p>
</div>

<button class="accordion">สีประจำโรงเรียน</button>
<div class="panel">
  <p>น้ำเงิน - แสด
    สีน้ำเงิน หมายถึง สถาบันพระมหากษัตริย์
    สีแสด หมายถึง สีประจำวันประสูติของสมเด็จพระเจ้าน้องนางเธอ เจ้าฟ้าจุฬาภรณวลัยลักษณ์ อัครราชกุมารีกรมพระศรีสวางควัฒน วรขัตติยราชนารี คือ วันพฤหัสบดี</p>
</div>

<script>
  var acc = document.getElementsByClassName("accordion");
  var i;
  
  for (i = 0; i < acc.length; i++) {
    acc[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var panel = this.nextElementSibling;
      if (panel.style.display === "block") {
        panel.style.display = "none";
      } else {
        panel.style.display = "block";
      }
    });
  }
  </script>
  
      <!-- Tab links -->
      <h2>About me</h2>
      <div class="tab">
        <button class="tablinks" onclick="openCity(event, 'nickname')">
          nickname
        </button>
        <button class="tablinks" onclick="openCity(event, 'Age')">
          Age
        </button>
        <button class="tablinks" onclick="openCity(event, 'Where im form')">
          Where me form
        </button>
      </div>

      <!-- Tab content -->
      <div id="nickname" class="tabcontent">
        <h3>My nickname</h3>
        <p>My nickname is James.</p>
      </div>

      <div id="Age" class="tabcontent">
        <h3>My age</h3>
        <p>I'm 13 years old.</p>
      </div>

      <div id="Where im form" class="tabcontent">
        <h3>I'm from</h3>
        <p>I'm from Thailand.</p>
      </div>
    </div>
  </div>

  <div class="footer">
    <h2>This is Footer....</h2>
  </div>
  <script>
    var acc = document.getElementsByClassName("accordion");
    var i;

    for (i = 0; i < acc.length; i++) {
      acc[i].addEventListener("click", function () {
        /* Toggle between adding and removing the "active" class,
  to highlight the button that controls the panel */
        this.classList.toggle("active");

        /* Toggle between hiding and showing the active panel */
        var panel = this.nextElementSibling;
        if (panel.style.display === "block") {
          panel.style.display = "none";
        } else {
          panel.style.display = "block";
        }
      });
    }
    function openCity(evt, cityName) {
      // Declare all variables
      var i, tabcontent, tablinks;

      // Get all elements with class="tabcontent" and hide them
      tabcontent = document.getElementsByClassName("tabcontent");
      for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
      }

      // Get all elements with class="tablinks" and remove the class "active"
      tablinks = document.getElementsByClassName("tablinks");
      for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
      }

      // Show the current tab, and add an "active" class to the button that opened the tab
      document.getElementById(cityName).style.display = "block";
      evt.currentTarget.className += " active";
    }
    var slideIndex = 0;
    showSlides();

    function showSlides() {
      var i;
      var slides = document.getElementsByClassName("mySlides");
      for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {
        slideIndex = 1;
      }
      slides[slideIndex - 1].style.display = "block";
      setTimeout(showSlides, 5000); // Change image every 2 seconds
    }
  </script>


</body></html>
