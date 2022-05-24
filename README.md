# jdq-site
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>jdqlife</title>
    <style>
      h1,
      h2 {
        margin: 1% auto;
        padding: 10px auto;
        max-width: 100%;
        text-align: center;
        color: #27306b;
      }
      body {
        background: #fff;
        margin: auto;
        text-align: center;
        max-width: 100%;
        font-family: Arial, Helvetica, sans-serif;
      }
      nav {
        text-align: center;
        padding: 20px;
      }
      ul {
        display: inline;
        list-style: none;
        padding: 0px auto;
        margin: 0px auto;
        padding-inline-start: 0px;
      }

      li {
        text-transform: uppercase;
        font-weight: bold;
        display: inline;
        text-align: center;
        margin: 0px 20px;
        padding: 10px 30px;
        color: azure;
        background: linear-gradient(-45deg, #c86501, #fbb400, #ff831e);
        background-size: 400%, 400%;
        position: relative;
        animation: change 10s ease-in-out infinite;
        border-width: 5px;
        border-radius: 40px;
        box-shadow: 2px 2px 4px rgb(200, 101, 1, 0.4);
      }

      @keyframes change {
        /* NAV BAR ANIMATION GRADIENT */
        0% {
          background-position: 0 50%;
        }
        50% {
          background-position: 100% 50%;
        }

        100% {
          background-position: 0 50%;
        }
      }

      img {
        border-style: unset;
        border-bottom: 60px solid #e7e7eb;
        border-top: 20px solid #e7e7eb;
        border-left: 20px solid #e7e7eb;
        border-right: 20px solid #e7e7eb;
        margin: 10px 15px;
        box-shadow: 2px 2px 2px rgb(0, 0, 0, 0.4);
      }

      footer {
        background: linear-gradient(-45deg, #c86501, #fbb400, #ff831e);
        background-size: 400%, 400%;
        position: relative;
        animation: change 10s ease-in-out infinite;
        max-width: 100%;
        position: absolute;
        left: 0%;
        right: 0%;
      }

      .wrapper {
        /* FLEX SECTIONS*/
        display: flex;
        margin: auto;
        justify-content: space-evenly;
      }

      .left {
        /* LANDING PAGE*/
        text-align: center;
      }

      .right {
        padding-top: 10px;
        text-align: right;
      }

      /* NAV BAR */
      .navmobile {
        
        display: flex;
        text-align: center;
      }
      .boxone {
        flex: 33.3%;
      }
      .boxtwo {
        flex: 33.3%;
      }

      .boxthree {
        flex: 33.3%;
      }
      .logo {
        flex: 90%;
        text-align: center;
      }
      .shopicon {
        padding-top: 10px;
        text-align: left;
        flex: 10%;
      }

      .logo {
        padding-left: 7%;
      }

      /* M&V*/
      .left2 {
        flex: 1;
        text-align: left;
        padding: 0% 10px;
      }

      .right2 {
        flex: 1;
        padding-top: 100px;
      }

      @media only screen and (max-width: 1050px) {
        .shopicon {
          display: none;
        }

        .logo {
          padding-left: 0%;
        }
        .wrapper {
          display: block;
          box-sizing: border-box;
        }

        .aligncenter {
          text-align: center;
        }

        .highlight {
          text-align: center;
        }

        .navmobile {
          box-sizing: border-box;
          padding: 3px;
          font-size: 12px;
          color: #100b6f;
        }

        .left2 {
          order: 2;
        }

        .right2 {
          order: 1;
        }
      }

      .highlight {
        font-size: 30px;
        color: #100b6f;
        line-height: 1.5;
        padding-right: 20px;
      }

      .wordStyle {
        font-size: 25px;
        color: #100b6f;
        line-height: 1.5;
        padding: auto;
      }

      .noborder {
        border: none;
        border-radius: none;
        box-shadow: none;
      }

      .wrap {
        /*CONTENT FLEX */
        display: flex;
        margin: auto;
      }

      .first {
        flex: 33.3%;
        text-align: center;
      }

      .second {
        flex: 33.3%;
        text-align: center;
      }

      .third {
        flex: 33.3%;
        text-align: center;
      }


      /* footer */
      .navbottom {
        border: 2px solid #27306b;
        background: #100b6f;
        box-shadow: none;
        
      }
      .footerList {
        background: none;
        border: none;
        padding: 5px 20px;
        box-shadow: none;
        border-style: none;
        margin: 0%;
      }

      /*hyperlinks */
      a {
        text-decoration: none;
        color: #fff;
      }

      .linkchange {
        color: #27306b;
        text-decoration:wavy;
        font-style: italic;
      }
    </style>
  </head>

  <body>
    <header>
      <!--  THIS IS THE NAV SECTION -->
      <section class="wrap">
        <h1 class="logo">
          <img
            src="../jdqsite/img/jdqlogoblue.png"
            width="400px"
            height="95px"
            class="noborder"
          />
        </h1>
        <p>
          <a href="https://www.jdqjustdontquit.com/" target="_blank">
            <img
              src="../jdqsite/icons/shopicon.png"
              width="65px"
              height="65px"
              class="noborder shopicon"
            />
          </a>
        </p>
      </section>

      <nav>
        <ul class="navmobile">
          <li class="boxone"><a href="#knowMe">Know me</a></li>
          <li class="boxtwo"><a href="#aboutUs">About JDQ<a href="knowMe"></a></li>
          <li class="boxthree">
            <a href="https://www.jdqjustdontquit.com/" target="_blank"
              >Shop Now</a
            >
          </li>
        </ul>
      </nav>
    </header>

    <!--THIS IS THE LANDING PAGE SECTION-->
    <div class="wrapper" id="knowMe">
      <section class="left">
        <img
          src="../jdqsite/img/landingphoto.png"
          class="noborder"
          width="395px"
          height="450px"
        />
      </section>
      <section class="right">
        
        <p class="highlight">
          <em style="font-size: 40px;">Thanks for joining the movement!</em> </br> My name is Jorge David Quinones Rios. I am an
          online content creator, illustration artist, & entrepreneur. Within
          my content creations on my <strong> <a href= "https://www.youtube.com/c/YABOYJDQ" class="linkchange">Youtube channel</a></strong> you will find many videos
          of my interviews with online content creators who dedicate their time to
          catching online child pedophiles & online child predators to expose
          their crimes with the intent of getting them arrrested or at the very
          least raising awareness in their community.
        </p>
      </section>
    </div>
    <br />
    <br />
    <hr />
    <!--MISSION AND VISION SECTION-->
    <div class="wordStyle wrapper backimage" id="aboutUs">
      <section class="left2">
        <h2>VISION</h2>
        <p class="aligncenter">
          By reaching as many people as we can & have them be part of this
          movement <br />
          we will be extending the brand’s mindset to all those who need to be
          reminded how important, capable and purposeful they are.
        </p>

        <h2>MISSION</h2>
        <p class="aligncenter">
          This brand does not aim to sell any products, that is not our intent.
          The mission is to start a movement where people from different walks of
          life who have gone through different struggles, dark pasts, and apparent
          obstacles whether it be mental, emotional, social, can find a family
          where they are worth more than they can imagine. Wearing
          our brand is a reminder to ourselves and those who surround us that although we have gone through
          the fire, it has only helped forge us into indestructible diamonds
          that no matter what we have faced, are facing or will face we will not crumble, we will only be made stronger, shine brighter and reflect hope,
         perservance and resiliance.
        </p>
      </section>

      <section class="right2">
        <img
          src="../jdqsite/img/Justdontquiticonorange.png"
          width="650"
          height="650px"
          class="noborder"
        />
      </section>
    </div>

    <br />
    <br />
    <hr />
    <!--CONTENT SECTION-->
    <div class="wrapper">
      <section class="first">
        <a
          href="https://www.jdqjustdontquit.com/listing/biglogowhite-official-jdq-hood?product=46&variation=2742&size=423"
        target="_blank">
          <img
            class
            src="../jdqsite/img/photo1.1.JPG"
            width="400px"
            height="450px"
          />
        </a>
      </section>

      <section class="second">
        <a
          href="https://www.jdqjustdontquit.com/listing/respect-the-rise-and-shine?product=212&variation=5818&size=1167"
        target="_blank">
          <img src="../jdqsite/img/photo2.2.JPG" width="400px" height="450px" />
        </a>
      </section>

      <section class="third">
        <a
          href="https://www.jdqjustdontquit.com/listing/official-jdq-just-dont-quit-wh?product=212&variation=5823&size=1167"
        target="_blank">
          <img src="../jdqsite/img/photo3.3.JPG" width="390px" height="450px" />
        </a>
      </section>
    </div>

  <!--NAVBOTTOM-->
      <nav>
        <ul class="navmobile">
          <li class="boxone navbottom"><a href="#knowMe">Know me</a></li>
          <li class="boxtwo navbottom"><a href="#aboutUs">About JDQ<a href="knowMe"></a></li>
          <li class="boxthree navbottom">
            <a href="https://www.jdqjustdontquit.com/" target="_blank"
              >Shop Now</a
            >
          </li>
        </ul>
      </nav>

    <!--FOOTER-->
  </body>
  <footer>
    <p class="wordStyle">
      Diamonds are created under pressure, hold on<br /><strong
        >JOIN THE MOVEMENT</strong
      >
    </p>

    <ul>
      <li class="footerList">
        <a href="https://www.facebook.com/JDQJUSTDONTQUIT" target="_blank">
        <img
          src="../jdqsite/icons/fbicon.png"
          width="45px"
          height="45px"
          class="noborder"
        />
        </a>
      </li>
      <li class="footerList">
        <a href="https://www.instagram.com/jdqjustdontquit/" target="_blank">
        <img
          src="../jdqsite/icons/instaicon.png"
          width="45px"
          height="45px"
          class="noborder"
        />
        </a>
      </li>
    </ul>
    <p></p>
    <p style="color: #fff">Coded By <strong> <a href="https://linktr.ee/dailiq" target="_blank"> Dailian Quinones</a></strong></p>
  </footer>
</html>
