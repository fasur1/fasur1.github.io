

<!DOCTYPE html>
<html>
<head>
  <meta name="keywords" content="cani, dogsitter, pensione cani, prezzi bassi, dogsitter senzapreavviso">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<title>il tuo dogsitter d'emergenza</title>

<style>
/* stili  */
@import url('https://fonts.googleapis.com/css2?family=MuseoModerno:wght@300&family=Roboto:wght@300;400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Muli:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Muli&display=swap');

/* stili */

body{margin: 0}



/*..............................................*/


.paragrafo1{  font-family: 'Roboto', sans-serif;
word-spacing: 3px;

}

.paragrafo2{ }

*{box-sizing: border-box;}



.row::after {
  content: "";
  clear: both;
  display: table;
}


[class*="col-"] {
  float: left;
  padding: 15px;
}

html {
  font-family: "Lucida Sans", sans-serif;
}

ul.nav{list-style-type: none;
  background-image: linear-gradient(to bottom left , rgba(58, 235, 52), rgba( 143, 235, 52)); color: black;
  ;
   overflow: hidden;
   top: 0;
   margin: 0;padding: 0;
    position: fixed;
   width: 100%;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.5); z-index: 2;
}
li.nav{float: left}
li a.nav{text-decoration: none;
  text-align: center;
  color: black;
  padding: 14px 25px ;
  display: block; font-size: 20px; font-family: 'Muli', sans-serif; z-index: 2
}
li a.nav:hover{background-color: rgba(168, 167, 163, 0.4);}

@media screen and (max-width: 700px) {
  li.nav, ul.nav {
    display: none;
  }
}


@media screen and (min-width: 700px) {
  nav {
    display: none;
  }
}



#menuToggle
{
  display: block;
  position: relative;
  top: 50px;
  left: 50px;

  z-index: 1;

  -webkit-user-select: none;
  user-select: none;
}

#menuToggle a
{
  text-decoration: none;
  color: #232323;

  transition: color 0.3s ease;
}

#menuToggle a:hover
{
  color: tomato;
}


#menuToggle input
{
  display: block;
  width: 40px;
  height: 32px;
  position: absolute;
  top: -7px;
  left: -5px;

  cursor: pointer;

  opacity: 0; /* hide this */
  z-index: 2; /* and place it over the hamburger */

  -webkit-touch-callout: none;
}

/*
 * Just a quick hamburger
 */
#menuToggle span
{
  display: block;
  width: 45px;
  height: 5px;
  margin-bottom: 5px;
  position: relative;

  background: rgba(58, 235, 52);
  border-radius: 3px;

  z-index: 1;

  transform-origin: 4px 0px;

  transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
              background 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
              opacity 0.55s ease;
}

#menuToggle span:first-child
{
  transform-origin: 0% 0%;
}

#menuToggle span:nth-last-child(2)
{
  transform-origin: 0% 100%;
}

/*
 * Transform all the slices of hamburger
 * into a crossmark.
 */
#menuToggle input:checked ~ span
{
  opacity: 1;
  transform: rotate(45deg) translate(-2px, -1px);
  color: rgba(58, 235, 52);
}

/*
 * But let's hide the middle one.
 */
#menuToggle input:checked ~ span:nth-last-child(3)
{
  opacity: 0;
  transform: rotate(0deg) scale(0.2, 0.2);
}

/*
 * Ohyeah and the last one should go the other direction
 */
#menuToggle input:checked ~ span:nth-last-child(2)
{
  transform: rotate(-45deg) translate(0, -1px);
}

/*
 * Make this absolute positioned
 * at the top left of the screen
 */
#menu
{
  position: absolute;
  width: 300px;
  margin: -100px 0 0 -50px;
  padding: 50px;
  padding-top: 125px;

  background: #ededed;
  list-style-type: none;
  -webkit-font-smoothing: antialiased;
  /* to stop flickering of text in safari */

  transform-origin: 0% 0%;
  transform: translate(-100%, 0);

  transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0);
}

#menu li
{
  padding: 10px 0;
  font-size: 22px;
}

/*
 * And let's slide it in from the left
 */
#menuToggle input:checked ~ ul
{
  transform: none;
}

/* INIZIO SPARIZIONE*/


.barramob{width: 100%; text-align: center; background: yellow; margin: 0; position: sticky}


/* For mobile phones: */
[class*="col-"] {
  width: 100%;
}

@media only screen and (min-width: 600px) {
  /* For tablets: */
  .col-s-1 {width: 8.33%;}
  .col-s-2 {width: 16.66%;}
  .col-s-3 {width: 25%;}
  .col-s-4 {width: 33.33%;}
  .col-s-5 {width: 41.66%;}
  .col-s-6 {width: 50%;}
  .col-s-7 {width: 58.33%;}
  .col-s-8 {width: 66.66%;}
  .col-s-9 {width: 75%;}
  .col-s-10 {width: 83.33%;}
  .col-s-11 {width: 91.66%;}
  .col-s-12 {width: 100%;}
}
@media only screen and (min-width: 768px) {
  /* For desktop: */
  .col-1 {width: 8.33%;}
  .col-2 {width: 16.66%;}
  .col-3 {width: 25%;}
  .col-4 {width: 33.33%;}
  .col-5 {width: 41.66%;}
  .col-6 {width: 50%;}
  .col-7 {width: 58.33%;}
  .col-8 {width: 66.66%;}
  .col-9 {width: 75%;}
  .col-10 {width: 83.33%;}
  .col-11 {width: 91.66%;}
  .col-12 {width: 100%;}
}

.paragrafo{text-align: center;}

.banner{
  background-image: linear-gradient(to bottom left , rgba(112, 240, 84), green); margin-top: 70px
 }



</style>
</head>
<body>

  <!-- Simulate a smartphone / tablet -->

  <!-- Top Navigation Menu -->
  <!--    Made by Erik Terwan    -->
  <!--   24th of November 2015   -->
  <!--        MIT License        -->
  <nav role="navigation">
    <div id="menuToggle">
      <!--
      A fake / hidden checkbox is used as click reciever,
      so you can use the :checked selector on it.
      -->
      <input type="checkbox" />

      <!--
      Some spans to act as a hamburger.

      They are acting like a real hamburger,
      not that McDonalds stuff.
      -->
      <span></span>
      <span></span>
      <span></span>

      <!--
      Too bad the menu has to be inside of the button
      but hey, it's pure CSS magic.
      -->
      <ul id="menu">
        <a href="#"><li>home</li></a>
        <a href="paesi.html"><li>paesi</li></a>
        <a href="politici.html"><li>politici</li></a>
        <a href="#"><li>buffoni della settimana</li></a>
        <a href="#"><li>virtuosi della settimana</li></a>

        <a href="https://erikterwan.com/" target="_blank"><li>Show me more</li></a>
      </ul>
    </div>
  </nav>

<ul class="nav">
    <li class="nav"><a class="nav" href="https://www.amazon.com" target="">Home</a></li>
    <li class="nav"><a href="cani.html" class="nav">gatti</a></li>
    <li class="nav"><a href="contatti.html" class="nav">contatti</a></li>
    <li class="nav"><a href="prezzi.html" class="nav">prezzi</a></li>

  </ul>
<br>
<div class="row">
</div>
  <div class="col-3 col-s-3 banner">

  </div>

  <div class="col-6 col-s-9 paragrafo1">
    <p style="color: rgb(4, 145, 91);"><hr color="red"><h1>the song "everything is awesome" from lego movie and a basic tutorial to create a dictatorship</h1></p> <hr color="red">

    <h2 style="color: rgb(4, 145, 91); padding:4px">little info:</h2>
    <p> the song says: "Everything is cool when you're part of a team" it's true and nice to be part of a team, because it makes you feel less alone and isolated but also because it gives us completeness, especially if the team is very big. in fact the more the group is numerous and the easier it will be to induce its participants, and this is the principle on which organizations such as ISIS or Nazism are governed. It is nice to feel part of something greater than oneself. the phenomenon is also noted in schools where some children become (or try) to join a group of bullies in order not to be bullied themselves. this principle works on subjects without personality.   </p>


<a name="b">    <h2  style="color: rgb(4, 145, 91);">thesis:</h2></a>
<p>this is not surprising given that the world the film is set in is a global
  dictatorship masked by the fact that they are all a great team. being part of a team is the first step in establishing a dictatorship, as the second is finding a common enemy; However! without the good working of the first pass the second one cannot be used. let's break down: what I call a "nerdy bully" usually the bully is a self-confident little shit, physically strong and all (watch some american teen movies and you'll understand) but usually in his group, yes why the bully is never alone, there is a loser who has most likely been bullied in the past,
  and this failure joins the bunch of bastards; that at first they
   will bully (but with ) the nerdy bully will inevitably try to bully some idiots, if successful he would join the group of bullies as a member and will no longer be bullied, but if he fails most likely ) will be excluded from any group and will not even be able to join others and will fill the role of the type hated by all. how should it fail? by smoothing the prey, bullies have a natural talent, because bullies are born, not made. now you know how to become a bully or a dictator.</p>
    <p></p>
    <hr color="blue">

<a name="c">    <h2  style="color: rgb(4, 145, 91);">punchlines:</h2></a>
<p style="background: rgba(232, 232, 135)">
you're wondering (you probably didn't) how I linked a child's song to dictatorships and
  squadism? well and since I don't have many friends here ... I almost found a regime </p>

</div>


<div class="col-3 col-s-12" >
</div>


</body>
</html>
