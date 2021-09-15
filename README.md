<!DOCTYPE html>
<html>
<head>

<style type="text/css">
  


html {
  height: 200%;
  width: 100%;
}
body {
  min-height: 200vh;
  width: 100%;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  /*background: #b1b0ac;*/
  background: #eee;
}





.title {
      color: #333;
      font-family: Arial;
      font-size: 5rem;
      font-weight: 500;
      line-height: 1.5;
    }
    .card {
      height: 100px;
      width: 200px;
      border-radius: 10px;
      background: black;
      padding: 1rem;
      padding: 1rem;
      display: flex;
      justify-content: flex-start;
      align-items: center;
      
    
    }
    .block {
      height: 90%;
      width: 33.33%;
      background: #fff;
      border-radius: 10px;
      margin: 10px;
      display: flex;
      flex-direction: column;
    
      
    }
    .block-val {
      color: #000;
      font-family: Arial;
      font-size: 30px;
      font-weight: 700;
      line-height: 1.5;
      margin: 0;
    }
    .block-title {
      color: #333;
      font-family: Arial;
      font-size: 14px;
      font-weight: 500;
      line-height: 1.5;
    }











.resume {
  height: 100;
  width: 500px;
  background: #ddd;
  position: relative;
  overflow: hidden;
   border-radius: 10px;

}
.header {
  height: 100px;
  width: 100%;
  background: #5b9cd6;
  display: flex;
  justify-content: center;
  align-items: center;
     border-radius: 10px;
}

/* Header Left */
.header-left {
  height: 100%;
  width: 45%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.header-left-avatar-wrapper,
.header-left-title-wrapper {
  height: 100%;
  width: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.header-left-avatar-wrapper {
  justify-content: flex-end;
  padding-right: 10px;
}
.header-left-avatar {
  height: 90px;
  width: 100px;
  border-radius: 10%;
  background: #fff;
  overflow: hidden;
}
.header-left-avatar-img {
  height: 100%;
  max-width: 100%;
  object-fit: cover;
}
.header-left-title {
  font-size: 14px;
  font-weight: 900;
  color: #fff;
  line-height: 1.5;
  width: 80%;
  font-family: Arial;
}

/* Header Right */
.header-right {
  height: 100%;
  width: 55%;
  display: inline-block;
  justify-content: center;
  align-items: center;
  padding-left: 4rem;
  margin-top: 30px;
}
.header-right-contact {
  margin: 0;
  padding: 0;
  list-style: none;
}
.header-right-contact-block {
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
.header-right-contact-block-title {
  font-size: 8px;
  font-weight: 900;
  color: #fff;
  font-family: Arial;
  margin: 0;
}
.header-right-contact-block-txt {
  font-size: 7px;
  color: rgba(255,255,255,0.80);
  font-family: Arial;
  margin: 3px;
}

/* Content */
.content-wrapper {
  height: 100%;
  width: 100%;
  background: #fff;
  padding-bottom: 3rem;
  display: flex;
  justify-content: center;
  align-items: flex-start;
}
.content-inner {
  height: 90%;
  width: 90%;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  padding: 18px auto;
}
.content-block {
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.content-block-title {
  width: 100%;
  padding-bottom: 3px;
  border-bottom: 1px solid #bbb;
  font-size: 13px;
  font-weight: 700;
  font-family: Arial;
  margin: 18px auto 7px;
}
.content-block-info {
  height: auto;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
.content-block-info p {
  color: #555;
  line-height: 1.5;
  font-size: 12px;
  font-weight: 400;
  font-family: Arial;
  margin: 0;
}
.content-block-info .row {
  height: auto;
  width: 100%;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
.content-block-info .row .col-left,
.content-block-info .row .col-right {
  height: 100%;
  width: 50%;
  margin: 2px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.content-block-info .row .col-left.custom {
  width: 100%;
  align-self: flex-start;
}
.content-block-list {
  height: auto;
  width: 100%;
  padding: 0;
  margin: 0;
  list-style: square inside;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
.content-block-list-item {
  height: auto;
  width: 100%;
  color: #555;
  line-height: 1.5;
  font-size: 12px;
  font-weight: 400;
  font-family: Arial;
  margin: 2px auto;
}


 button {
    height: 50px;
    width: 70%;
    background:  #5b9cd6;
    color: #fff;
    border: none;
    padding: 0 10px;
    border-radius: 10px;
    margin: 10px;
    font-size: 18px;
}



/* Footer */
.footer {
  height: 20px;
  width: 100%;
  background: #5b9cd6;
  position: absolute;
  bottom: 0px;
  left: 0px;
}


  
</style>

  <meta charset="UTF-8">
  <title>Joel personal site</title>
  <link rel="stylesheet" type="text/css" href="resume.css">
</head>
<body>






<div class="card">
    <div class="block">
      <h1 class="block-val" id="hour">00</h1>
      <span class="block-title">Hours</span>
    </div>
    <div class="block">
      <h1 class="block-val" id="minute">00</h1>
      <span class="block-title">Minutes</span>
    </div>
    <div class="block">
      <h1 class="block-val" id="seconds">00</h1>
      <span class="block-title">Seconds</span>
    </div>
  </div>





<div class="bob">
<h1 id="colorCodeText"></h1>
    <button id="randomBgGenerator">
    Change background
    </button>
</div>


  <script src="JOELISAIAHBOBAI.js" charset="utf-8"></script>















  <div class="resume">
    <div class="header">
      <div class="header-left">
        <div class="header-left-avatar-wrapper">
          <div class="header-left-avatar">
            <img src= "joel.jpg"; height="100" width="100">

          </div>
        </div>
        <div class="header-left-title-wrapper">
          <h1 class="header-left-title">JOEL ISAIAH BOBAI</h1>
        </div>
      </div>

      <div class="header-right"
        <ul class="header-right-contact">
          <li class="header-right-contact-block">
            <h2 class="header-right-contact-block-title">Address</h2>
            <p class="header-right-contact-block-txt">Nigeria, Federal Capital </p>
          </li>
          <li class="header-right-contact-block">
            <h2 class="header-right-contact-block-title"> Phone</h2>
            <p class="header-right-contact-block-txt">+2348027663942<br>+2348144709818</p>
          </li>
          <li class="header-right-contact-block">
            <h2 class="header-right-contact-block-title">Address</h2>
            <p class="header-right-contact-block-txt">joelisaiahbobai@gmail.com </p>
          </li>
        </ul>
      </div>
    </div>
    
    <div class="content-wrapper">
      <div class="content-inner">
        <div class="content-block">
          <h3 class="content-block-title">Summary</h3>
          <div class="content-block-info">
           <p>
            Senior Web Developer specializing in front end development. Experienced with all stages of the development cycle for dynamic web projects. Well-versed in numerous programming languages including HTMLS5, PHP OOP, Javascript, CSS, MYSQL, Strong background in project management and ustomer relations.
           </p>
          </div>
        </div>
        
        <div class="content-block">
          <h3 class="content-block-title">Skill Highlights</h3>
          <div class="content-block-info">
           <div class="row">
             <div class="col-left">
               <ul class="content-block-list">
                 <li class="content-block-list-item">Project management</li>
                 <li class="content-block-list-item">Strong decision maker</li>
                 <li class="content-block-list-item">Complex problem solver</li>
               </ul>
             </div>
             
              <div class="col-right">
               <ul class="content-block-list">
                 <li class="content-block-list-item">Creative design</li>
                 <li class="content-block-list-item">Innovative</li>
                 <li class="content-block-list-item">Service focused</li>
               </ul>
             </div>
           </div>
         </div>
        </div>
        
        <div class="content-block">
          <h3 class="content-block-title">
          Experience
          </h3>
          <div class="content-block-info">
            <p class="">
              <b>Web Developer - </b> 09/2018 to 05/2021
            </p>
            <p class="">
              <b>Luna Web Design - </b> Abuja
            </p>
           <div class="row">
             <div class="col-left custom">
               <ul class="content-block-list">
                 <li class="content-block-list-item">Cooperate with designers to create clean interfaces and simple, intuitive interactions and experiences</li>
                 <li class="content-block-list-item">Develop project concepts and maintain optimal workflow.</li>
                 <li class="content-block-list-item">Work with senior developers to manage large, complex design projects for corporate clients.</li>
                 <li class="content-block-list-item">Complete detailed programming and development tasks for front end public and internal websites as well as challenging back-end server code.</li>
                  <li class="content-block-list-item">Carry out quality assurance tests to discover errors and optimize usability.</li>
               </ul>
             </div>
           </div>
         </div>
        </div>
        
        <div class="content-block">
          <h3 class="content-block-title">
          Age
          </h3>
          <div class="content-block-info">
            <p>
           <b>2003</b>
           <b>August- 5th
           </p>
          </div>
        </div>
        
        <div class="content-block">
          <h3 class="content-block-title">Languages</h3>
          <div class="content-block-info">
           <p>
           <b>Hausa</b> - C4
           </p>
           <p>
            <b>English</b> - A1
           </p>
          </div>
        </div>
        
        <div class="content-block">
          <h3 class="content-block-title">
          Certifications
          </h3>
          <div class="content-block-info">
           <p>
           PHP Framework (Certification): <b>Zend, Codeigniter, Symfony</b> - 2018
           </p>
           <p>
            Programming Languages: <b>Javascript, HTML5, PHP OOP, CSS, SQL, MYSQL</b> NY
           </p>


            <a href="CONTACT ME.html">
           <button type="submit" class="submitbtn">CONTACT ME</button>
       </a>


          </div>
        </div>
        
      </div>
    </div>
    
    <div class="footer"></div>

  </div>
</body>
</html>
