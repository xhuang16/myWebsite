<!DOCTYPE html>
<html>
<head>
  <title>Engineering in Microbiology</title>

  <style>

  .tab {
    overflow: hidden;
    background-color: #f1f1f1;
    /* margin-left: 30%; */
  }

  .tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
  }
  .tab button:hover {background-color: #A9A9A9;}
  body{background-color: #f1f1f1;}
  div{padding-right: 15%; padding-left: 15%;}
  .header {background-image: url("headerPic2.jpg"); height: 100px}
  h1 {color: #004080; text-align: center; font-size:300%;}
  /* h2 {color: #004080; text-align: center; margin-top: 5%; margin-bottom: 5%; font-family: verdana;} */
  h2 {color: #004080; font-family: verdana;}

  h6{margin-top: 0px;}
  img{width:35%; height:auto; margin-right:5%; float: left;}
  p{color: #525252; font-family:verdana; margin-top: 2.5%; line-height: 1.5}

  </style>

</head>
<body>

  <!-- <div class = "header" >
  <h1>Engineering in Microbiology</h1>
  </div> -->
  <h1>Engineering in Microbiology</h1>


  <div class="tab">
    <button class="tablinks" onclick="openTab(event, 'HOME')">HOME</button>
    <button class="tablinks" onclick="openTab(event, 'RESEARCH')">RESEARCH</button>
    <button class="tablinks" onclick="openTab(event, 'ABOUT ME')">ABOUT ME</button>
  </div>

  <div id="HOME" class="tabcontent">
    <h2 style="text-align: center; color: #004080;">
      What is engineering? What does it mean to engineer something for microbiology?
    </h2>
    <h4 style="text-align: center; color: #004080;">
      I don't know. Let's find out together
    </h4>
  </div>

  <div id="RESEARCH" class="tabcontent">
    <h3>RESEARCH</h3>
    <p>My current and past research.</p>
  </div>

  <div id="ABOUT ME" class="tabcontent">
    <!-- <h6>But I typically go by Jack</h6> -->
    <img src = "profilePic2.jpg" alt = "profilePic">
    <h2>My name is XuHai Huang</h2>
    <p>
      To make life easier, I typically go by Jack. So I am a graduate student at the University of Virginia studying Electrical Engineering. I received my B.S. in Physics from the University of Pittsburgh. I used to be a semiconductor guy, but solid-state physics went to the backburner after I discovered microfluidics in graduate school! I have since switched to researching novel microfluidic devices. If you’re interested in my research, please check out the RESEARCH tab. Outside of science, I like working out, playing video games, and just enjoying the outdoors. I cannot conclude a about me without talking about my faith the life Christ have blessed me with. I currently serve with the Chinese Christian Student Fellowship at UVA and the youth group at Grace Faith Chinese Church. Studying, working, and having fun is good, but “Those who honor me I will honor.”
    </p>
  </div>

  <script>
  function openTab(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
      tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
  }
  document.getElementsByClassName('tablinks')[0].click()
  </script>
  <!-- <a href="https://www.linkedin.com/in/xuhaihuang/" target="_blank">linkedin</a> -->
</body>
</html>
