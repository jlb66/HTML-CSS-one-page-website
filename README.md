# HTML-CSS-one-page-website
Space Station themed HTML/CSS One Page Website
<!DOCTYPE html>
<html>
<head>
<The Voyager Space Station | Resort>
</head>
<body>
  <ul>
    <a href="#home"></a>
    <li>HOME</li><a href="#gallery"></a>
    <li>GALLERY</li><a href="#contact"></a>
    <li>RESERVATIONS</li>
  </ul>
  <p>The Voyager Space Station</p>
  <p>Explore the wonders of space aboard these fascinating wonders of mankind</p>
  <h1>Reservations</h1>
  <h2>Your adventure is just around the moon. Reserve your flight today!</h2>
  <p>Please provide us with your basic contact information.</p>
  <p>Terms and Conditions</p>
  <p><a href="https://theconversation.com/space-tourism-20-years-in-the-making-is-finally-ready-for-launch-159606?utm_medium=email&amp;utm_campaign=Saturday%20Newsletter%20%20May%201%202021%20-%201935718946&amp;utm_content=Saturday%20Newsletter%20%20May%201%202021%20-%201935718946+CID_1b0ff8a2f642c814f88f78e554e224a8&amp;utm_source=campaign_monitor_us&amp;utm_term=Space%20tourism%20%2020%20years%20in%20the%20making%20%20is%20finally%20ready%20for%20launch">From Humble Beginnings...</a></p><a href="#home">www.theVoyagerSpaceStation.space</a> &nbsp;|&nbsp; © 2021
</body>
</html>
/*---------------------------------------------------
    MENU SELECTION
---------------------------------------------------*/
.menu {
  color: #f00;
  font: bold 12px/18px sans-serif;
  text-align: center;
  display: inline;
  margin: 0% auto;
  padding: 0;
  list-style: none;
  text-decoration: none;
}

.menu li {
  color: #000;
  background-color: rgba(255, 255, 255, 1);
  display: inline-block;
  margin: 0% auto;
  position: relative;
  padding: 15px 4%;
  border: 1px solid #9d9fa2;
  box-shadow: 2px 2px 10px 0 rgba(173, 133, 133, 0.4);
  border-radius: 6px;
  /* background-color: #052136; */
  cursor: pointer;
  transition-property: background;
  transition-duration: 0.4s;
  transition-delay: 0s;
  transition-timing-function: ease-in-out;
}

.menu li:hover {
  color: #f00;
  background-color: rgba(100, 65, 0, 0.4);
}

/*===================================================
    GALLERY SECTION ANIMATION
===================================================*/

.photo {
  position: relative;
  line-height: 0;
  margin-bottom: 2em;
  overflow: hidden;
  border-radius: 8px;
  padding: 1px;
  border: 1px solid #021a40;
  background-color: #ff0;
  box-shadow: 2px 2px 10px 0 rgba(0, 0, 0, 0.6);
}

.photo-container {
  text-align: center;
  margin: 15px auto;
  width: 300px;
  height: 169px;
}

.photo-container img {
  max-width: 100%;
  width: 300px;
  height: 169px;
}

.photo-overlay {
  color: #fff;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding-left: 20px;
  padding-right: 20px;
  justify-content: center; /* For centering text inside the .photo-overlay */
  align-items: center;
  background: rgba(0, 0, 0, 0.5);
}

.white-head {
  color: #c9bdaa;
  margin-top: 5%;
}

/*===================================================
    Photo Overlay Transitions
===================================================*/
.photo-overlay {
  opacity: 0;
  transition: opacity 0.5s;
  border-radius: 10px;
  cursor: pointer;
}

.photo-overlay:hover {
  opacity: 1;
}

.photo img {
  transition: transform 3.5s;
  transform-origin: 50% 50%;
}

.photo:hover img {
  transform: scale(1.5);
}
  
======================= GENERTIC STYLES
====================================================*/html { font-family:
sans-serif; font-size: 62.5%; -webkit-tap-highlight-color: rgba(0, 0, 0,
0); -webkit-text-size-adjust: 100%; -ms-text-size-adjust: 100%;} body {
font-size: 14px; margin: 0; font-family: "Helvetica Neue", Helvetica,
Arial, sans-serif; line-height: 1.42857143; color: #333; background-color:
#fff;} footer,nav { display: block;} h1,h1,h3,h4,h5,h6 { font-family: "Open
Sans", sans-serif;} h1 { line-height: 50px; font-weight: 900; font-size:
30px; text-transform: uppercase; text-align: center; color: #e91c1c;
text-shadow: 2px 2px 3px rgba(0, 0, 0, 0.5);} h1::after { /* This is the
underline */ display: block; content: ""; height: 2px; width: 150px;
background: #e91c1c; margin: 5px auto 40px; box-shadow: 5px 2px 3px rgba(0,
0, 0, 0.5);} h2 { line-height: 50px; color: #e91c1c;} h3 { line-height:
30px; padding-bottom: 20px;} h4 { padding-top: 25px; line-height: 40px;
padding-bottom: 0px; font-size: 22px; font-weight: 900;} p { font-weight:
300; line-height: 30px; padding-bottom: 15px;} .text-center { text-align:
center;} .heading-padding { padding-bottom: 40px;} section { padding-top:
50px; margin-top: 50px;} .navbar { height: 105px; max-height: 340px;
display: block;} .container { padding-right: 15px; padding-left: 15px;
margin-right: auto; margin-left: auto;} .container-fluid { padding-right:
15px; padding-left: 15px; margin-right: auto; margin-left: auto;} .row {
margin-right: -15px; margin-left: -15px;}
.clearfix:after,.container:after,.navbar:after { clear: both; display:
table; content: " ";} .wrap { height: 100%; width: 100%; position:
absolute; /* This ensures that the images cannot render outside of their
container without forcing any scrollbars*/ overflow: hidden; top: 0; left:
0; text-align: center;} .menu-container { max-height: 340px; margin: 0%
auto; content: " "; /* top: 0; left: 0; */ /* position: absolute; */ /*to
the top of the screen */ width: 100%; position: fixed; z-index: 100;
/*background-color: rgba(255, 255, 255, 0.5);*/}
/*================================================== HOME SECTION STYLES
================================================*/#home { background:
url(../SSW_Images/homeBackground.jpg) no-repeat; background-attachment:
fixed; -webkit-background-size: cover; -moz-background-size: cover;
-o-background-size: cover; background-size: cover; width: 100%; display:
block; height: auto; padding-top: 350px; /*This is spacer before the Main
Title logo */ padding-bottom: 500px; /* This is spacer after the Mian Title
logo */ color: #fff;} .head-main { text-shadow: 2px 4px 5px rgba(0, 0, 0,
0.9); font-variant: small-caps; color: #fff; letter-spacing: 5pt;
word-spacing: 21pt; font-size: 4.5em; text-align: left; font-family:
Impact, sans-serif; line-height: 2; font-weight: 900; border: 5px double
#fff; padding: 10px;} .head-sub-main { font-size: 23px; font-weight: 500;
padding: 50px 20px 10px 20px; text-transform: uppercase;} .head-last {
font-size: 10px; font-weight: 900; padding: 5px 20px 20px 20px; border: 1px
dotted #fff; padding: 5px;}
/*-------------------------------------------------------- CONTACT STYLES
-------------------------------------------------------*/.flex-container {
display: -webkit-flex; display: flex; flex-wrap: wrap; padding: 10px;
border-radius: 8px; margin: 0px auto; background-color: rgba(100, 65, 0,
0.3); box-shadow: 2px 2px 10px 0 rgba(0, 0, 0, 0.5);} #contact {
background-color: #f5f3f3;} .reservation { width: 60%; padding: 10px;
border-radius: 8px; margin: 0px auto; background-color: rgba(100, 65, 0,
0.3); box-shadow: -1px -1px 1px 0 rgba(0, 0, 0, 0.1), 1px 2px 10px rgba(0,
0, 0, 0.5);} .reservation h2 { width: 70%; text-align: center; margin: 0
auto; color: #13161b; font-weight: 500; font-size: 1.3em; letter-spacing:
0pt; word-spacing: 0pt;} .reservation h2 span { width: 70%; text-align:
center; margin: 0 auto; color: #13161b; font-weight: 900; font-size: 1.5em;
font-variant: small-caps; letter-spacing: 0.4pt; word-spacing: 0.3pt;}
.reservation p { color: #13161b; width: 50%; margin: 0 auto;} .reservation
form { font-size: 15px; outline: none; font-weight: 600; color: #8d8e8f;
padding: 12px 12px; width: 70%; border: 1px solid #808080; margin: 2% auto;
border-radius: 7px; background: rgb(227, 222, 222); box-shadow: 2px 3px 3px
0px rgba(0, 0, 0, 0.3); font-family: "Raleway", sans-serif;} .reservation
input[type="text"] { font-size: 15px; outline: none; font-weight: 600;
color: #8d8e8f; padding: 2% 1% 2% 7%; width: 80%; border-top: 1px solid
#090b0d; border-right: 2px solid #424549; border-bottom: 2px solid #424549;
border-left: 1px solid #090b0d; margin: 10px 1em; border-radius: 7px;
background: #13161b; box-shadow: inset 0px 3px 0px 0px rgba(5, 5, 5, 0.15);
font-family: "Raleway", sans-serif;} .reservation input [type="text"]:hover
{ box-shadow: 0 0 10px rgba(100, 65, 0, 0.8);} .form-spacer { padding: 30px
39px;} .terms { margin-top: 13%; margin: 30px 1px 0 0; padding-left: 52px;
font-size: 14px; line-height: 5px; color: #000; cursor: pointer;
font-family: "Raleway", sans-serif; font-weight: 600; position: relative;
display: inline; float: right;} .terms:hover { color: orange;
text-decoration: underline;} .submit input [type="submit"] { color:
rgb(225, 225, 225); cursor: pointer; border: none; font-weight: 900;
outline: none; text-align: center; font-family: "Raleway", sans-serif;
margin: 0px 3%; padding: 7px 0px; width: 25%; font-size: 18px; transition:
border-color 0.3s color 0.3s background-color 0.3s; border-radius: 7px;
background-color: #797a7b; box-shadow: 1px 1px 4px 0 rgba(0, 0, 0, 0.3);}
.submit input[type="submit"]:hover { color: #000; background-color:
#8d8e8f; box-shadow: inset 1px 2px 15px 0 rgba(0, 0, 0, 0.5);}
/*======================================================= FOOTER
STYLES=====================================================*/.footer {
background-color: rgba(100, 65, 0, 0.3); color: #000; text-shadow: 2px 2px
8px 0 (0, 0, 0, 0.4); padding: 20px 50px 20px 50px; text-align:
right;}#footer1 { text-align:
left;}/*======================================================= @MEDIA
QUERIES =======================================================@media all
and (max-width: 640px) and (min-width: 381px) { .head-main { font-size:
20px; }}@media all and (max-width: 381px) and (min-width: 200px) {
.head-main { font-size: 24px; }}@media (min-width: 768px) { .container {
width: 750px; }}@media (min-width: 992px) { .container { width: 970px;
}}@media (min-wdith: 1200px) { .container { width: 1170px; }}*/

--000000000000dafb6b05e90d8873
Content-Type: text/html; charset="UTF-8"
Content-Transfer-Encoding: quoted-printable

<div dir=3D"auto">=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D GENERTIC STYLES =3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D*/html { font-family: sans-serif; font-=
size: 62.5%; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); -webkit-text-si=
ze-adjust: 100%; -ms-text-size-adjust: 100%;} body { font-size: 14px; margi=
n: 0; font-family: &quot;Helvetica Neue&quot;, Helvetica, Arial, sans-serif=
; line-height: 1.42857143; color: #333; background-color: #fff;} footer,nav=
 { display: block;} h1,h1,h3,h4,h5,h6 { font-family: &quot;Open Sans&quot;,=
 sans-serif;} h1 { line-height: 50px; font-weight: 900; font-size: 30px; te=
xt-transform: uppercase; text-align: center; color: #e91c1c; text-shadow: 2=
px 2px 3px rgba(0, 0, 0, 0.5);} h1::after { /* This is the underline */ dis=
play: block; content: &quot;&quot;; height: 2px; width: 150px; background: =
#e91c1c; margin: 5px auto 40px; box-shadow: 5px 2px 3px rgba(0, 0, 0, 0.5);=
} h2 { line-height: 50px; color: #e91c1c;} h3 { line-height: 30px; padding-=
bottom: 20px;} h4 { padding-top: 25px; line-height: 40px; padding-bottom: 0=
px; font-size: 22px; font-weight: 900;} p { font-weight: 300; line-height: =
30px; padding-bottom: 15px;} .text-center { text-align: center;} .heading-p=
adding { padding-bottom: 40px;} section { padding-top: 50px; margin-top: 50=
px;} .navbar { height: 105px; max-height: 340px; display: block;} .containe=
r { padding-right: 15px; padding-left: 15px; margin-right: auto; margin-lef=
t: auto;} .container-fluid { padding-right: 15px; padding-left: 15px; margi=
n-right: auto; margin-left: auto;} .row { margin-right: -15px; margin-left:=
 -15px;} .clearfix:after,.container:after,.navbar:after { clear: both; disp=
lay: table; content: &quot; &quot;;} .wrap { height: 100%; width: 100%; pos=
ition: absolute; /* This ensures that the images cannot render outside of t=
heir container without forcing any scrollbars*/ overflow: hidden; top: 0; l=
eft: 0; text-align: center;} .menu-container { max-height: 340px; margin: 0=
% auto; content: &quot; &quot;; /* top: 0; left: 0; */ /* position: absolut=
e; */ /*to the top of the screen */ width: 100%; position: fixed; z-index: =
100; /*background-color: rgba(255, 255, 255, 0.5);*/} /*=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D HOME SECTION STYL=
ES =3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D*/#=
home { background: url(../SSW_Images/homeBackground.jpg) no-repeat; backgro=
und-attachment: fixed; -webkit-background-size: cover; -moz-background-size=
: cover; -o-background-size: cover; background-size: cover; width: 100%; di=
splay: block; height: auto; padding-top: 350px; /*This is spacer before the=
 Main Title logo */ padding-bottom: 500px; /* This is spacer after the Mian=
 Title logo */ color: #fff;} .head-main { text-shadow: 2px 4px 5px rgba(0, =
0, 0, 0.9); font-variant: small-caps; color: #fff; letter-spacing: 5pt; wor=
d-spacing: 21pt; font-size: 4.5em; text-align: left; font-family: Impact, s=
ans-serif; line-height: 2; font-weight: 900; border: 5px double #fff; paddi=
ng: 10px;} .head-sub-main { font-size: 23px; font-weight: 500; padding: 50p=
x 20px 10px 20px; text-transform: uppercase;} .head-last { font-size: 10px;=
 font-weight: 900; padding: 5px 20px 20px 20px; border: 1px dotted #fff; pa=
dding: 5px;} /*-------------------------------------------------------- CON=
TACT STYLES -------------------------------------------------------*/.flex-=
container { display: -webkit-flex; display: flex; flex-wrap: wrap; padding:=
 10px; border-radius: 8px; margin: 0px auto; background-color: rgba(100, 65=
, 0, 0.3); box-shadow: 2px 2px 10px 0 rgba(0, 0, 0, 0.5);} #contact { backg=
round-color: #f5f3f3;} .reservation { width: 60%; padding: 10px; border-rad=
ius: 8px; margin: 0px auto; background-color: rgba(100, 65, 0, 0.3); box-sh=
adow: -1px -1px 1px 0 rgba(0, 0, 0, 0.1), 1px 2px 10px rgba(0, 0, 0, 0.5);}=
 .reservation h2 { width: 70%; text-align: center; margin: 0 auto; color: #=
13161b; font-weight: 500; font-size: 1.3em; letter-spacing: 0pt; word-spaci=
ng: 0pt;} .reservation h2 span { width: 70%; text-align: center; margin: 0 =
auto; color: #13161b; font-weight: 900; font-size: 1.5em; font-variant: sma=
ll-caps; letter-spacing: 0.4pt; word-spacing: 0.3pt;} .reservation p { colo=
r: #13161b; width: 50%; margin: 0 auto;} .reservation form { font-size: 15p=
x; outline: none; font-weight: 600; color: #8d8e8f; padding: 12px 12px; wid=
th: 70%; border: 1px solid #808080; margin: 2% auto; border-radius: 7px; ba=
ckground: rgb(227, 222, 222); box-shadow: 2px 3px 3px 0px rgba(0, 0, 0, 0.3=
); font-family: &quot;Raleway&quot;, sans-serif;} .reservation input[type=
=3D&quot;text&quot;] { font-size: 15px; outline: none; font-weight: 600; co=
lor: #8d8e8f; padding: 2% 1% 2% 7%; width: 80%; border-top: 1px solid #090b=
0d; border-right: 2px solid #424549; border-bottom: 2px solid #424549; bord=
er-left: 1px solid #090b0d; margin: 10px 1em; border-radius: 7px; backgroun=
d: #13161b; box-shadow: inset 0px 3px 0px 0px rgba(5, 5, 5, 0.15); font-fam=
ily: &quot;Raleway&quot;, sans-serif;} .reservation input [type=3D&quot;tex=
t&quot;]:hover { box-shadow: 0 0 10px rgba(100, 65, 0, 0.8);} .form-spacer =
{ padding: 30px 39px;} .terms { margin-top: 13%; margin: 30px 1px 0 0; padd=
ing-left: 52px; font-size: 14px; line-height: 5px; color: #000; cursor: poi=
nter; font-family: &quot;Raleway&quot;, sans-serif; font-weight: 600; posit=
ion: relative; display: inline; float: right;} .terms:hover { color: orange=
; text-decoration: underline;} .submit input [type=3D&quot;submit&quot;] { =
color: rgb(225, 225, 225); cursor: pointer; border: none; font-weight: 900;=
 outline: none; text-align: center; font-family: &quot;Raleway&quot;, sans-=
serif; margin: 0px 3%; padding: 7px 0px; width: 25%; font-size: 18px; trans=
ition: border-color 0.3s color 0.3s background-color 0.3s; border-radius: 7=
px; background-color: #797a7b; box-shadow: 1px 1px 4px 0 rgba(0, 0, 0, 0.3)=
;} .submit input[type=3D&quot;submit&quot;]:hover { color: #000; background=
-color: #8d8e8f; box-shadow: inset 1px 2px 15px 0 rgba(0, 0, 0, 0.5);} /*=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D FOOTER STYLES=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D*/.footer { background-color: rgba(1=
00, 65, 0, 0.3); color: #000; text-shadow: 2px 2px 8px 0 (0, 0, 0, 0.4); pa=
dding: 20px 50px 20px 50px; text-align: right;}#footer1 { text-align: left;=
}/*=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D @MEDIA QUERIES =3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D@media all and (max-widt=
h: 640px) and (min-width: 381px) { .head-main { font-size: 20px; }}@media a=
ll and (max-width: 381px) and (min-width: 200px) { .head-main { font-size: =
24px; }}@media (min-width: 768px) { .container { width: 750px; }}@media (mi=
n-width: 992px) { .container { width: 970px; }}@media (min-wdith: 1200px) {=
 .container { width: 1170px; }}*/=C2=A0</div>


    MENU SELECTION
---------------------------------------------------*/
.menu {
  color: #f00;
  font: bold 12px/18px sans-serif;
  text-align: center;
  display: inline;
  margin: 0% auto;
  padding: 0;
  list-style: none;
  text-decoration: none;
}

.menu li {
  color: #000;
  background-color: rgba(255, 255, 255, 1);
  display: inline-block;
  margin: 0% auto;
  position: relative;
  padding: 15px 4%;
  border: 1px solid #9d9fa2;
  box-shadow: 2px 2px 10px 0 rgba(173, 133, 133, 0.4);
  border-radius: 6px;
  /* background-color: #052136; */
  cursor: pointer;
  transition-property: background;
  transition-duration: 0.4s;
  transition-delay: 0s;
  transition-timing-function: ease-in-out;
}

.menu li:hover {
  color: #f00;
  background-color: rgba(100, 65, 0, 0.4);
}

/*=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D
    GALLERY SECTION ANIMATION
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D*/

.photo {
  position: relative;
  line-height: 0;
  margin-bottom: 2em;
  overflow: hidden;
  border-radius: 8px;
  padding: 1px;
  border: 1px solid #021a40;
  background-color: #ff0;
  box-shadow: 2px 2px 10px 0 rgba(0, 0, 0, 0.6);
}

.photo-container {
  text-align: center;
  margin: 15px auto;
  width: 300px;
  height: 169px;
}

.photo-container img {
  max-width: 100%;
  width: 300px;
  height: 169px;
}

.photo-overlay {
  color: #fff;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding-left: 20px;
  padding-right: 20px;
  justify-content: center; /* For centering text inside the .photo-overlay
*/
  align-items: center;
  background: rgba(0, 0, 0, 0.5);
}

.white-head {
  color: #c9bdaa;
  margin-top: 5%;
}

/*=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D
    Photo Overlay Transitions
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D*/
.photo-overlay {
  opacity: 0;
  transition: opacity 0.5s;
  border-radius: 10px;
  cursor: pointer;
}

.photo-overlay:hover {
  opacity: 1;
}

.photo img {
  transition: transform 3.5s;
  transform-origin: 50% 50%;
}

.photo:hover img {
  transform: scale(1.5);
}"
https://jlb66/Basic_HTML_and_CSS/Space_Station_Website/SSW_CSS/animations.css
Basic_HTML_and_CSS/Space_Station_Website/SSW_CSS/animations.css#:~:text=3D/=
*%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2=
D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2=
D%2D%0A%20%20%20%20MENU%20SELECTION%0A%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%=
2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%=
2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D*/%0A.menu,transform%3A%20scale(1.=
5)%3B%0A%7D

--00000000000066e07f05e8bc54cb
Content-Type: text/html; charset="UTF-8"
Content-Transfer-Encoding: quoted-printable

<div dir=3D"auto">&quot;/*-------------------------------------------------=
--<br>=C2=A0=C2=A0=C2=A0 MENU SELECTION<br>--------------------------------=
-------------------*/<br>.menu {<br>=C2=A0 color: #f00;<br>=C2=A0 font: bol=
d 12px/18px sans-serif;<br>=C2=A0 text-align: center;<br>=C2=A0 display: in=
line;<br>=C2=A0 margin: 0% auto;<br>=C2=A0 padding: 0;<br>=C2=A0 list-style=
: none;<br>=C2=A0 text-decoration: none;<br>}<br><br>.menu li {<br>=C2=A0 c=
olor: #000;<br>=C2=A0 background-color: rgba(255, 255, 255, 1);<br>=C2=A0 d=
isplay: inline-block;<br>=C2=A0 margin: 0% auto;<br>=C2=A0 position: relati=
ve;<br>=C2=A0 padding: 15px 4%;<br>=C2=A0 border: 1px solid #9d9fa2;<br>=C2=
=A0 box-shadow: 2px 2px 10px 0 rgba(173, 133, 133, 0.4);<br>=C2=A0 border-r=
adius: 6px;<br>=C2=A0 /* background-color: #052136; */<br>=C2=A0 cursor: po=
inter;<br>=C2=A0 transition-property: background;<br>=C2=A0 transition-dura=
tion: 0.4s;<br>=C2=A0 transition-delay: 0s;<br>=C2=A0 transition-timing-fun=
ction: ease-in-out;<br>}<br><br>.menu li:hover {<br>=C2=A0 color: #f00;<br>=
=C2=A0 background-color: rgba(100, 65, 0, 0.4);<br>}<br><br>/*=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D<br>=C2=
=A0=C2=A0=C2=A0 GALLERY SECTION ANIMATION<br>=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D*/<br><br>.photo {<br>=C2=
=A0 position: relative;<br>=C2=A0 line-height: 0;<br>=C2=A0 margin-bottom: =
2em;<br>=C2=A0 overflow: hidden;<br>=C2=A0 border-radius: 8px;<br>=C2=A0 pa=
dding: 1px;<br>=C2=A0 border: 1px solid #021a40;<br>=C2=A0 background-color=
: #ff0;<br>=C2=A0 box-shadow: 2px 2px 10px 0 rgba(0, 0, 0, 0.6);<br>}<br><b=
r>.photo-container {<br>=C2=A0 text-align: center;<br>=C2=A0 margin: 15px a=
uto;<br>=C2=A0 width: 300px;<br>=C2=A0 height: 169px;<br>}<br><br>.photo-co=
ntainer img {<br>=C2=A0 max-width: 100%;<br>=C2=A0 width: 300px;<br>=C2=A0 =
height: 169px;<br>}<br><br>.photo-overlay {<br>=C2=A0 color: #fff;<br>=C2=
=A0 position: absolute;<br>=C2=A0 top: 0;<br>=C2=A0 right: 0;<br>=C2=A0 bot=
tom: 0;<br>=C2=A0 left: 0;<br>=C2=A0 padding-left: 20px;<br>=C2=A0 padding-=
right: 20px;<br>=C2=A0 justify-content: center; /* For centering text insid=
e the .photo-overlay */<br>=C2=A0 align-items: center;<br>=C2=A0 background=
: rgba(0, 0, 0, 0.5);<br>}<br><br>.white-head {<br>=C2=A0 color: #c9bdaa;<b=
r>=C2=A0 margin-top: 5%;<br>}<br><br>/*=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D<br>=C2=A0=C2=A0=C2=A0 Photo Over=
lay Transitions<br>=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=
=3D=3D=3D=3D=3D=3D=3D=3D*/<br>.photo-overlay {<br>=C2=A0 opacity: 0;<br>=C2=
=A0 transition: opacity 0.5s;<br>=C2=A0 border-radius: 10px;<br>=C2=A0 curs=
or: pointer;<br>}<br><br>.photo-overlay:hover {<br>=C2=A0 opacity: 1;<br>}<=
br><br>.photo img {<br>=C2=A0 transition: transform 3.5s;<br>=C2=A0 transfo=
rm-origin: 50% 50%;<br>}<br><br>.photo:hover img {<br>=C2=A0 transform: sca=
le(1.5);<br>}&quot;<br> <a href=3D"https://jlb66
/HTML-CSS-Projects/df-WiProgress/Basic_HTML_and_CSS/Space_Station_Website=
/SSW_CSS/animations.css#:~:text=3D/*%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D=
%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D=
%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%0A%20%20%20%20MENU%20SELECTION%0A%2=
D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2=
D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2=
D*/%0A.menu,transform%3A%20scale(1.5)%3B%0A%7D">https://raw.githubuserconte=
/jlb66/HTML-CSS-Projects/df-WiProgress/Basic_HTML_and_CSS/Space_St=
ation_Website/SSW_CSS/animations.css#:~:text=3D/*%2D%2D%2D%2D%2D%2D%2D%2D%2=
D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2=
D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%0A%20%20%20%20MENU%20S=
ELECTION%0A%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%=
2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%2D%=
2D%2D%2D%2D%2D*/%0A.menu,transform%3A%20scale(1.5)%3B%0A%7D</a>=C2=A0</div>
