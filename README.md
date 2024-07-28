# pri_strona
24/07/24 build
28/07/24 build


@import url('https://fonts.googleapis.com/css2?family=Ropa+Sans:ital,wght@0,400;0,700;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Titillium+Web:wght@400;600;700&display=swap');

* {
  scroll-behavior: smooth;
  font-family: 'Titillium Web', sans-serif;
  margin: 0;
  padding: 0;
  max-width: 100%;
  }
  body {
  background-color: white;
  /*  height: 3000px; Ensure the body has a set height */
  box-sizing: border-box;
  scroll-snap-type: y mandatory;
  -ms-scroll-snap-points-y: 100vh;
  }
  .dogory{
  opacity: 0;
  pointer-events: none;
  }
  .dogory.scrollowany{
  opacity: 100;
  pointer-events: auto;
  }
  .material-symbols-outlined {
  font-variation-settings:
  'FILL' 0,
  'wght' 400,
  'GRAD' 0,
  'opsz' 20;
  }
  .navbar {
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  font-style: italic;
  background-color: transparent;
  border-bottom: 2px solid rgba(105, 105, 105, 0);
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  top: 0;
  width: 100%; /* Ensure width takes the full viewport width */
  transition: 0.5s;
  font-size: 20px;
  }
  .navbar a {
  text-decoration: underline;
  color: snow;
  text-align: center;
  padding: 8px 12px;
  }
  .navbar a:hover {
  color: lightgray;
  text-shadow: 1px 1px 1px rgba(0, 31, 63, 0.8);
  }
  .navbar.scrollowany {
  border-bottom-left-radius: 17px;
  border-bottom-right-radius: 13px;
  background-color: #FDFBFC;
  border-bottom: 1px solid rgba(105, 105, 105, 0.25);
  font-size: 16px; /* Slightly smaller font size when scrolled */
  }
  .navbar.scrollowany a {
  color: dimgray;
  }
  .navbar.scrollowany a:hover {
  color: black;
  text-shadow: 1px 1px 1px dimgray;
  }
  .navbar a.active {
  color: #6c459e;
  }

#top{
scroll-snap-align: start;
background-image: url(AdobeStock_78473109_Preview.jpeg);
background-attachment: inherit;
background-size: cover;
max-width: 100%;
width: 100%;
height: 100vh;
display: table-cell;
align-items: center;
vertical-align: middle;
justify-content: center;
text-align: center;
font-weight: 700;
color: white;
margin: auto;
}
.tytul{
font-family: Ropa Sans, serif;
font-weight: bolder;
font-size: calc(2vw + 2lh);
}

/* Links container */
.links {
display: flex;
justify-content: space-between;
min-width: 40%;
}

/* Subtitle styling */
.podtytul {
font-family: Ropa Sans, serif;
font-size: calc(1vw + 1lh);
font-weight: normal;
padding: 0.5%;
}

/* Description styling */
.opis {
font-weight: lighter;
font-size: calc(1vw + 0.30lh);
padding: 5%;
}

#about {
scroll-snap-align: start;
background-image: url('AdobeStock_30640999_Preview.jpg');
background-attachment: inherit;
background-size: cover;
width: 100%;
height: 100vh;
display: flex;
flex-direction: column;
align-items: flex-start;
justify-content: flex-start;
text-align: left;
font-weight: 600;
font-size: 7vh;
color: #000000;
margin: auto;
padding: 5%;
}
.header{
font-size: calc(0.25vw + 0.25lh);
color: #2B2E63;
text-decoration: underline;
text-decoration-color: #798DC5;
/*    text-shadow: 2px 2px 2px  RGB(70, 157, 206, 0.30);*/
}
.abouttext{
font-weight: lighter;
font-size: 2.5vh;
max-width: 50%;
padding-top: 20px;
}
#work{
scroll-snap-align: start;
background-image: url('AdobeStock_236276543_Preview.jpeg');
background-attachment: inherit;
background-size: cover;
width: 100%;
height: 100vh;
display: flex;
flex-direction: column;
align-items: flex-start;
justify-content: flex-start;
text-align: left;
font-weight: 600;
font-size: 7vh;
color: #000000;
margin: auto;
padding: 5%;
}
#workabout{
max-width: 100%;
}
#listawork{
padding-left: 5%;
}
li+li{
margin-top: 1%;
}
#szczegoly{
font-size: 1.5vh;
}
#realizacje{
scroll-snap-align: start;
/*background-image: url('AdobeStock_236276543_Preview.jpeg');
background-attachment: inherit;
background-size: cover;*/
width: 100%;
height: 100vh;
display: flex;
flex-direction: column;
align-items: flex-start;
justify-content: flex-start;
text-align: left;
font-weight: 600;
font-size: 7vh;
color: #000000;
margin: auto;
padding: 5%;
}