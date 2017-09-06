# Boss-Website

Created a website for 1HUDDLE CEO & founder, Sam Caucci. 1HUDDLE is an enteprise-based B2B mobile training platform that allows users to train anytime, anywhere. Its mission is to empower the people that power teams across the globe. Clients for 1HUDDLE include, ESPN, the Golden State Warriors, Audible, Denver International Airport, and so many more. 

<!DOCTYPE html>
<html>

<head>

<link href='https://fonts.googleapis.com/css?family=Raleway' rel='stylesheet'>

<style>
#header_container{
  background-color: white;
  background-size:cover;
  padding-top: 20px;
  padding-bottom: 20px;
}
#header_text{
  color: black;
  text-align: right;
  font-family: 'Raleway';
  font-size: 40px;
  font-weight: 900;
  padding-right: 30px;
  font-stretch: expanded;
}
#imagesbackground {
  background-color: #D3D3D3;
  margin-top:0;
  margin-bottom:0;
  padding: 0;
  margin: 0 0;
}
#block{
  display: block;
}
#news-logos{
  text-align: center !important;
}
#background_sam{
  background-image: url(http://1huddle.co/images/team/sam2.png);
  background-size:cover;
}
#overlay{
  background-color: rgba(0,0,0,0.8);
}
#sam{
  padding-left: 100px;
  width: 300px;
  height: 300px;
}
#bio {
  color: white;
  font-family:  'Raleway';
  font-size: 16px;
  font-weight:normal;
  font-stretch: condensed;
}
@media only screen and (max-width: 2000px){
  #child_div{
    padding-top: 90px;
    padding-bottom: 80px;
  }
}
@media only screen and (max-width:1300px){
  #child_div{
    padding-top: 40px;
    padding-bottom: 40px;
  }
}
.icon{
  padding-left:10px;
  padding-right:10px;
  padding-top: 10px;
}
#video{
  padding-top: 50px;
  padding-bottom: 50px;
  text-align:center;
}
#InTheNews{
  padding-top: 20px;
  text-align:center;
  font: 900 48px/48px 'Raleway', sans-serif;
  font-family:  'Raleway';
}
@media only screen and (max-width:2000px){
  .space{
    width: 200px;
  }
}
@media only screen and (max-width:1300px){
  .space{
    width: 50px;
  }
}
footer{
  text-align:center;
  color:white;
  background-color:black;
  padding-top: 30px;
  padding-bottom: 30px;
  font-family:'Raleway';
  font-weight: 400;
}
#icon_holder{
  padding-left:100px;
  display:block;
  text-align:center;
}
a{
  color:white;
}
li.news-logo{
  display:inline-block;
  padding-right: 40px;
  padding-left: 40px;
}
</style>

  <div id = "header_container">
    <div id = "header_text">
      Sam Caucci
    </div>
  </div>

</head>


<body>

<div id = "background_sam">

  <div id = "overlay">
    <div id = "child_div">
      <table>
        <tr>
          <td>
              <table>
                <tr>

                  <td>
                    <img id = "sam" src = "http://1huddle.co/images/team/sam.png">
                  </td>
                </tr>

                <tr>

                  <td>
                    <div id = "icon_holder">
                        <a href = "https://www.linkedin.com/in/samcaucci/"> <img class = "icon" src = "http://student.elon.edu/edomeck/project4/linked.png" width = "50" height = "50"> </a>
                        <a href = "https://www.amazon.com/Not-Our-Job-Destroyed-Generation-ebook/dp/B0170MKDJS"> <img class = "icon" src = "https://www.wileyindia.com/pub/static/frontend/Magento/luma/en_US/images/Amazon-Button.png" width = "50" height = "50"> </a>
                    </div>
                  </td>

                </tr>
              </table>
          <td class = "space"> </td>
          <td>  <p id = "bio"> Sam Caucci has managed and trained sales and leadership teams for publicly held, private sector and franchised companies across the globe.

          </br> </br>In 2010, Sam founded 1HUDDLE, a work-force training & consulting firm. With work delivered across North America, Europe and Asia, 1HUDDLE has impacted people across organizations in a wide array of sectors, with clients that include professional sports teams, pro athlete training facilities, hospitality, retail, government, college/university programs, and more. Applying an innovative approach to better staff training, Sam oversaw the creation of The Training Game, a game based training platform that is transforming the way organizations develop their people.

                </br> </br>He has been featured on CNN, Fox News, Fox Business, The Wall Street Journal, Bloomberg, ESPN & The Huffington Post.

                </br> </br>He works in New York City.
              </p> </td>
          <td class = "space"> </td>
        </tr>
      </table>
    </div>

      <div id = "imagesbackground">
        <div id = "block">
            <ul id = "news-logos">
                   <li class = "news-logo"><img src = "http://1huddle.co/images/clients/foxnews.png" alt = "Fox News" width = "155" height = "117"></li>
                   <li class = "news-logo"><img src = "http://1huddle.co/images/clients/cnn.png" alt = "CNN" width = "155" height = "117">  </li>
                   <li class = "news-logo"><img src = "http://1huddle.co/images/clients/forbes.png" alt = "Forbes" width = "155" height = "117"> </li>
                   <li class = "news-logo"><img src = "http://1huddle.co/images/clients/bloomberg.png" alt = "Bloomberg" width = "155" height = "117"> </li>
                   <li class = "news-logo"><img src = "http://1huddle.co/images/clients/wsj.png" alt = "Wall Street Journal" width = "155" height = "117"> </li>
             </ul>
        </div>
      </div>
    </div>

</div>

<div>
  <div id = "InTheNews">
    IN THE NEWS
  </div>

  <div id = "video">
    <iframe src="https://player.vimeo.com/video/228872552" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
  </div>
</div>

</body>

<footer>

  Copyright 2017 - All Rights Reserved </br>
  <a href = "http://google.com"> Privacy Policy </a>

</footer>

</html>
