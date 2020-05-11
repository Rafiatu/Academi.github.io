<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>
      Rafihatu's Project
    </title>
    <style>
      body{
        text-align: center;
        background-color: white;
        font-size: 19px;
      }
      div.segt{
        margin: 80px;
        margin-bottom: 0px;
        padding-bottom: 80px;
        margin-left: 130px;
        margin-right: 130px;
        border-bottom: 1px solid rgb(197,208,224);
      }
      .head{
        color: rgb(66,135,245);
        font-weight: bold;
        font-size: 22px;
        float: left;
      }
      #name{
        font-size: 72px;
        float: left;
      }
      A,a{
        text-decoration: none;
        color: rgb(66,135,245);
      }
      #first{
        font-weight: bold;
      }
      #avi{
        float: left;
        border:1px solid white;
        border-radius: 50px 50px 50px 50px;
      }
      #contact{
        float: right;
        text-align: justify;
      }
      .bold{
        font-weight: bold;
      }
      .date{
        font-size: 15px;
        float: right;
        color: rgb(166,173,168);
      }
      .place{
        color: rgb(166,173,168);
      }
      .justy{
        padding-left: 400px;
        text-align: justify;
      }
      .skilla{
        margin-top: 0;
        margin-left: 25px;
        font-size: 1rem;
      }
      #TopBtn {
        display: none;
        position: fixed;
        bottom: 40px;
        right: 30px;
        width: 0;
      	height: 0;
      	border-left: 10px solid transparent;
      	border-right: 10px solid transparent;
      	border-bottom: 20px solid rgb(66,135,245);
      }
      .switch {
        position: fixed;
        top: 50px;
        right: 30px;
        display: inline-block;
        width: 60px;
        height: 30px;
      }
      .switch input {
        opacity: 0;
        width: 0;
        height: 0;
      }
      .slider {
        position: absolute;
        cursor: pointer;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: #ccc;
        -webkit-transition: .4s;
        transition: .4s;
      }
      .slider:before {
        position: absolute;
        content: "";
        height: 22px;
        width: 22px;
        left: 4px;
        bottom: 4px;
        background-color: white;
        -webkit-transition: .4s;
        transition: .4s;
      }
      input:checked + .slider {
        background-color: #2196F3;
      }
      input:focus + .slider {
        box-shadow: 0 0 1px #2196F3;
      }
      input:checked + .slider:before {
        -webkit-transform: translateX(26px);
        -ms-transform: translateX(26px);
        transform: translateX(26px);
      }
      .slider.round {
        border-radius: 34px;
      }
      .slider.round:before {
        border-radius: 50%;
      }
      .dark-mode {
        background-color: black;
        color: white;
      }
    </style>
  </head>
  <body>

    <div class="segt">
    <img id="avi" src="https://st2.depositphotos.com/1310390/6993/v/950/depositphotos_69937509-stock-illustration-beautiful-arab-muslim-woman.jpg" height="70" width="70">
    <span id=name><span id=first>Rafihatu</span> Bello</span>
    <div id="contact"> +2348149248772 <br>
    <A HREF="mailto:rafibella101@gmail.com">rafibella101@gmail.com</A><br>
    <a target="_blank" href="https://github.com/Rafiatu?tab=projects"> https://github.com/Rafiatu=projects</a></div>
    </div>

    <div class="segt">
    <span class="head">Intro</span>
    <div class="justy">
    Hi! I am a web development student here at e-Health Africa.<br>
    A surveying graduate that has passion for broadcast media.<br>
    I love horse riding, paintballing and I would probably like paragliding and any other adventurous activity.
    </div>
    </div>

    <div class="segt">
    <span class="head">Interests</span>
    <div class="justy"> GIS | Newscasting | Web development | Make-Up </div>
    </div>

    <div class="segt">
    <span class="head">Skills</span>
    <div class="justy">
    <img src="https://ih1.redbubble.net/image.361593789.5453/ap,550x550,12x12,1,transparent,t.png" height="80" width="80">
    <img src="https://cdn4.iconfinder.com/data/icons/flat-brand-logo-2/512/css3-512.png" width="80" height="80">
    <img src="https://cdn.pixabay.com/photo/2015/04/23/17/41/javascript-736400_960_720.png" height="80" width="80">
    <p>
    <span class="skilla">HTML5</span>
    <span class="skilla">CSS</span>
    <span class="skilla">Javascript</span>
    </p>
    </div>
    </div>

    <div class = "segt">
    <span class="head">Education</span>
    <div class="justy">
    <span class="bold">Master of Geomatics and Environmental Management</span><br>
    University of British Columbia <br>
    <span class="place">Vancouver, Canada.</span>
    </div>
    <span class="date">JULY 2020 - APRIL 2021</span>

    <p>
    <div class="justy">
    <span class="bold">Bachelor of Technology in Surveying and Geoinformatics</span><br>
    Federal University of Technology Minna <br>
    <span class="place">Niger State, Nigeria.</span>
    </div>
    <span class="date">OCTOBER 2013 - OCTOBER 2018</span> </p>
    </div>

    <div class="segt">
    <span class="head">Experience</span>
    <div class="justy">
    <span class="bold">Ambiverts & Co.</span><br>
    Group General Manager <br>
    <span class="place">Indoors, Neighborhood.</span>
    </div>
    <span class="date">SEPTEMBER 2013 - PRESENT</span>
    <div class="justy">
    <p>-Watching TV <br>
    -Staying sane <br>
    -Helping out with the kids <br>
    -Learning online.</p>
    </div>
    </div>

    <div class="segt">
    <span class="head">Projects</span>
    <div class="justy">
    <a target="_blank" href="https://github.com/Rafiatu">https://github.com/Rafiatu</a>
    </div>
    </div>
    <button onclick="topFunction()" id="TopBtn" title="Go to top"></button>

    <label class="switch">
    <input type="checkbox">
    <span onclick="myFunction()" class="slider round"></span>
    </label>

    <script>
      mybutton = document.getElementById("TopBtn");
      window.onscroll = function() {scrollFunction()};

      function scrollFunction() {
        if (document.body.scrollTop > 10 || document.documentElement.scrollTop > 10) {
          mybutton.style.display = "block";
        } else {
          mybutton.style.display = "none";
        }
      }
      function topFunction() {
        document.documentElement.scrollTop = 0;
      }

      function myFunction() {
        var element = document.body;
        element.classList.toggle("dark-mode");
      }
    </script>
  </body>
</html>
