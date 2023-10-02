<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sourav - Developer Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
    }

    body {
      background-color: rgb(5, 21, 62);
      color: whitesmoke;
      font-family: 'Josefin Sans', sans-serif;
    }

    nav {
      display: flex;
      justify-content: space-around;
      align-items: center;
      height: 90px;
      background-color: rgb(41, 41, 137);
    }

    nav ul {
      display: flex;
      justify-content: center;
    }

    nav ul li {
      list-style: none;
      margin: 0 23px;
    }

    nav ul li a {
      text-decoration: none;
      color: white;
    }

    nav ul li a:hover {
      text-decoration: none;
      color: rgb(106, 106, 164);
      font-size: 1.02rem;
    }

    main hr {
      border: 0;
      background: #9c97f1;
      height: 1.2px;
      margin: 40px 84px;
    }

    .left {
      font-size: 2.5rem;
    }

    .firstSection {
      display: flex;
      justify-content: space-around;
      align-items: center;
      margin: 80px 0;
    }

    .firstSection>div {
      width: 40%;
    }

    .leftSection {


      font-size: 3rem;
      margin: 70px 0;

    }

    .rightSection img {

      width: 80%;


    }

    .purple {
      color: blueviolet;
    }

    .text-gray {
      color: gray;
    }

    #element {
      color: blueviolet;
    }



    .secondSection {
      max-width: 80vw;
      margin: auto;
      height: 80vh;
    }

    .secondSection h1 {
      font-size: 1.9rem;
    }

    .secondSection .box {
      background: white;
      width: 80vw;
      height: 2px;
      margin: 56px 0;
      display: flex;
    }

    .secondSection .vertical {

      height: 93px;
      width: 1px;
      background-color: whitesmoke;
      margin: 0 100px;
    }
  </style>
</head>

<body>
  <header>
    <nav>
      <div class="left">Sourav's Portfolio</div>
      <div class="right">
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/">About</a></li>
          <li><a href="/">Services</a></li>
          <li><a href="/">Projects</a></li>
          <li><a href="/">Contact Me</a></li>
        </ul>
      </div>
    </nav>
  </header>
  <main>
    <!--FIRST SECTION START -->
    <section class="firstSection">
      <div class="leftSection">
        Hi, My name is <span class="purple">Sourav</span>
        <div>and I am a passionate</div>

        <span id="element"></span>
      </div>
      <div class="rightSection">
        <img src="bp.png" alt="">
      </div>
    </section>
    <!--FIRST SECTION END -->


    <!--SECOND SECTION STRAT-->
    <hr>
    <Section class="secondSection">
      <span class="text-grey">What I have done far</span>
      <h1>Work Experience</h1>
      <!--ai khane sob nijer experience lekha thakbe [<div class="vertical"></div> ]  modhhe ak ak kore  -->
      <div class="box">
        <div class="vertical">

        </div>
        <div class="vertical"></div>
        <div class="vertical"></div>
        <div class="vertical"></div>
      </div>



    </Section>
  </main>

  <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
  <!--Set up and start animation -->

  <script>
    var typed = new Typed('#element', {
      strings: ['Web Developr', 'Graphic Designer', 'Video Editor'],
      typeSpeed: 50,
    });

  </script>
</body>
<!--171 nombor line a ja ja lekha thakbe sei jinis gula animetion hobe -->

</html>
