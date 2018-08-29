<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-124560072-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-124560072-1');
</script>
  <!DOCTYPE html>
<html>
<head>
    <title>Grey Li's Pomodoro Clock</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <link href="//cdn.bootcss.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
    <link href="css/style.css" rel="stylesheet">
    <link href='https://fonts.googleapis.com/css?family=Orbitron' rel='stylesheet' type='text/css'>
    <link href='https://fonts.googleapis.com/css?family=Pacifico|Open+Sans:300' rel='stylesheet' type='text/css'>
    <link rel="shortcut icon" href="image/favicon.ico" type="image/x-icon">
</head>
<body>
<p> Fudy is a new application being developed by University of Melbourne students. We would like to thank you for allowing your curiosity to get the better of you and scanning the QR code!
  <br />
<p> Fudy, with the help of the university, will map out a selection of tables in the libraries, in the student lounges and help students like you find a place to study.
  <br />
<p> Each study spot will have a QR code in front of it, just like the table that you are sitting at. When a student sits down to study at a "Fudy" table, they will need to scan the QR code and input how long they will be in that study spot. This will be updated on a real time map that application users will be able to view. When the student leaves, they will need to "scan out" and again this will be updated on the map.
  <br />
<p> To create more incentive for students to scan in and out, they will have the opporunity to gain points everytime they scan. These points can be redeemed for food vouchers. If there is anything that students enjoy, it's cheap food!
  <br />
<p> Our team would love to hear your feedback on the concept, if you have anything you would like to tell us, would like to have more information or would even like to work with us, please fill out this Google <a href="https://docs.google.com/forms/d/e/1FAIpQLSevrbuux86zDOM5tgVasoI7oqa2XSmrMYuPUnepvgnHAVvQuw/viewform?usp=sf_link "> form</a> and we will get back to you shortly.
  <br />
<p>Regards,
   <br />
  The Fudy team

  


    <audio id="over_music">
        <source src="http://e.ggtimer.com/styles/beepbeep.mp3">
    </audio>
    <!--a class="github" href="https://github.com/greyli/pomodoro" target="_blank"><img style="position: absolute; top: 0; right: 0; border: 0;" src="image/banner.png" alt="Fork me on GitHub"></a-->
    <div class="box container  text-center">
        <h2>Pomodoro Clock</h2>
        <div class="row">
        <div class="col-md-8 col-xs-8">
            <div class="timer ">
                <p class="time" id="time">25 : 00</p>
            </div>
            <div class="text-left">
                Work <span class="badge" id="workSignal" style="background-color: orange"> </span>
                Rest <span class="badge" id="restSignal"> </span>
            </div><br>
            <div class="progress">
                <div class="progress-bar progress-bar-warning" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width:0%">
                </div>
            </div>
            <p class="mobile-control">
                <a class="btn btn-primary start" href="#">Start</a>&nbsp;&nbsp;
                <a class="btn btn-primary reset" href="#">Reset</a>
            </p>
        </div><br>
        <div class="panel col-md-4 col-xs-4">
            <p>
               <a class="btn badge badge-primary" id="workMore">+</a> <span class="text"> <span id="workTime">25</span>
            Minutes </span><a class="btn badge badge-primary" id="workLess">-</a>
            </p><br>
            <p>
                <a class="btn badge badge-primary" id="restMore">+</a><span class="text"> <span id="restTime">5</span>
            Minutes </span><a class="btn badge badge-primary" id="restLess">-</a>
            </p>
            <p class="desktop-control">
                <a class="btn btn-primary start" href="#">Start</a>&nbsp;&nbsp;
                <a class="btn btn-primary reset" href="#">Reset</a>
            </p>
        </div>
        </div>
    </div>
    <br>
    <footer class="text-center">
    Made by <a href="http://greyli.com" target="_blank">Grey Li</a> /
        Fork me on <a href="https://github.com/greyli/pomodoro" target="_blank">GitHub</a>
    </footer>

  <script src="//cdn.bootcss.com/jquery/3.1.1/jquery.min.js"></script>
  <script src="js/main.js"></script>
</body>
</html>
