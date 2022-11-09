# ZomatocloneusingHTMLandCSS
#This is an basic zomato clone using HTML and CSS .If you know the HTML and CSS basics then it is an easy code for understanding for  more see the files
#The below is an HTML  
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="zomato.css">
    <link rel="icon" href="/Users/chandukiliveti/Library/Mobile Documents/com~apple~TextEdit/Documents/frontend/zomatoicon.png">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zomato</title>
</head>
<body>
    <header>
        <div class="nav">
            <div class="h-4">
            <h4> Get the App</h4>
            </div>
         
            <ul class="nav-bar">
                <li>Investor Relations</li>
                <li>Add restaurant</li>
                <li>Log in</li>
                <li>Sign up</li>
                </ul>
        </div>
        <div class="headd">
             <img class="logo" src="https://b.zmtcdn.com/web_assets/8313a97515fcb0447d2d77c276532a511583262271.png" alt="logo">
                <h3>Discover the best food & drinks in Hyderabad</h3>
            <div class="search">
                <img class="location" src="https://w7.pngwing.com/pngs/457/630/png-transparent-location-logo-location-computer-icons-symbol-location-miscellaneous-angle-heart.png" height="20px"width="18px">
                <p>Hyderabad</p> 
                <img class="searchsymbol"src="data:image/png;base64,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" height="20px" width="20px">
                <input type="text" placeholder="Search for Restaurant, cuisine or a dish">

                </div>
            </div>
            <div class="header-image">
            <img src="https://b.zmtcdn.com/web_assets/81f3ff974d82520780078ba1cfbd453a1583259680.png" alt="Zomatoimage">
            </div>
        </header>
        <section class="sec1">
            <div class="box">
                <div class="whitetext"> <span>Order Online
                <br><p>Stay home order to your door step</p>
                </span></div>
                <img src="img1.png">
            </div>
            <div class="box">
                <div class="whitetext"> <span>Dining
                <br><p>view the city's favourite dining venues</p>
                </span></div>
                <img src="diningimg.png">
            </div>

            <div class="box">
                <div class="whitetext"> <span>Nightlife and Clubs
                <br><p>Explore the city's top nightlife outlets</p>
                </span></div>
                <img src="nightlifeimg.png">
            </div>
        </section>
        <section class="sec2">
            <div>
                <h1>Collections</h1>
                <div class="sec2_text">
                <p class="sec_line"> Explore curated lists of top restaurants, cafes, pubs, and bars in Hyderabad, based on trends</p>
                <span class="sec2_P">All Collection in Hyderabad ▸ </span></div>
            <div>
                
            <div class="sec3">

             <div class="box1">
                <div> <span>Picturesque Cafes <br> 17 places ▸</span></div>
                <img src="https://b.zmtcdn.com/data/collections/b90996d69bfe8d8c7e36d3a56893df74_1657000323.jpg" alt="imageloading">   
             </div>   

                <div class="box1"> 
                    <div><span>LegendaryPlaces  <br> 24 places ▸</span> </div>
                    <img class="image" src="https://b.zmtcdn.com/data/collections/49a6f1f89106fa09c5c287ed6a7511af_1656936838.jpg">
                </div>

                <div class="box1">
                    <div> <span>Themed Dining <br> 7 places ▸</span></div>
                    <img class="image" src="https://b.zmtcdn.com/data/collections/8441060fb631af6f91509f32ab6a7f98_1656933763.jpg">
                </div>

                <div class="box1">
                    <div> Family Time<br> <span>19 places ▸</span></div>
                    <img class="image" src="imagesec3.png">
                </div>
            </div>


            <h2 class="h2text">Popular localities in and around <strong>Hyderabad</strong></h2>
            <div class="sec-4">

                <div class="box-2">
                <div>Jubilee Hills<br><span> 275 places</span> > </div>
                </div>


                <div class="box-2">
                    <div>Gachi bowli<br> <span>472 places</span> > </div>
                </div>


                <div class="box-2">
                    <div>Banjara Hills<br> <span>472 places</span> > </div>
                </div>
                <div class="box-2">
                    <div>Hitech City<br><span>224 places</span> > </div>
                </div>

                <div class="box-2">
                    <div>Madhapur<br><span> 523 places</span> > </div>
                </div>

                <div class="box-2">
                    <div>Kondapur<br><span> 325 places</span> > </div>
                </div>

                <div class="box-2">
                    <div>Kukatpally<br><span> 892 places</span> > </div>
                </div>

                
                <div class="box-2">
                    <div>Banjara Hills<br> <span>472 places</span> > </div>
                </div>


                <div class="box-2">
                    <div>Begumpet <br><span> 162 places</span> > </div>
                </div>

                
                <div class="box-2">
                    <div>Himayath Nagar<br><span> 172 places</span> > </div>
                </div>
                <div class="box-2">
                    <div>Banjara Hills<br> <span>472 places</span> > </div>
                </div>
                <div class="box-2">
                    <div>Banjara Hills<br> <span>324 places</span> > </div>
                </div>

            </div>

            


        </section>

        <section class="sec3">
            <div>
                <img class="mobileimg" src="mobileimg.png">
            </div>

            <div>
                <span>India</span>
                <span>English</span>
            </div>

         <div>

            <div class=" headingtext">
                <h2>Get the Zomato app</h2>
                <p>We will send you a link, open it on your phone to download the app</p>
            </div>

            <div>
                <div class="flex radiobtn">
                <input type="radio" name="radio" checked >
                <label for="email">Email</label>
                <input class="btn2" type="radio" name="radio">
                <label for="phone">Phone</label>
                </div>


                <div class="flex btn">
                <textarea rows="3" cols="40"></textarea>
                <button>Share App Link</button>
                </div>

                <h6>Download app from</h6>
                <div class="flex imageslink">
                    <img src="playstore.png">
                    <img src="appstore.png">
                </div>

            </div>

        </section>
        <section class="sec4">
            <div><h1>Explore options near me</h1></div>
            <div class="box3">Popular cuisines near me </div>
            <div class="box3">Popular restaurant types near me  </div>
            <div class="box3">Top Restaurant Chains </div>
            <div class="box3">Cities We Deliver To </div>
        </section>
<section class="footer">
<div class="sec7">

    <div class="first-1">

        <div> <img src="zomatofooter.png" alt="zomatoimg"></div>

            <div class="first">

             <div>
                <span>
                    India
                </span>
             </div>

             <div>
                <span>
                    English
                </span>
             </div>
        </div>

    </div>
        <div class="second-phase">
            <div class="fot-first">
                <h4>ABOUT ZOMATO</h4>
                <a href="#"> Who We Are</a><br>
                <a href="#">Blog</a><br>
                <a href="#"> Work With Us</a><br>
                <a href="#"> Investor Relations</a><br>
                <a href="#"> Report Fraud</a><br>
                <a href="#">Contact Us</a>
            </div>

                
                <div class="second">
                    <h4>ZOMAVERSE</h4>
                    <a href="#"> Zomato</a>
                    <a href="#"> Feeding India </a>
                    <a href="#"> Work With Us</a><br>
                    <a href="#"> Hyperpure</a><br>
                    <a href="#"> Zomaland</a><br>
                </div>

                <div class="third">
                    <h4>FOR RESTAURANT</h4>
                    <a href="#"> Partner with us</a>
                    <a href="#"> Apps For You</a>
                </div>

                <div class="fourth">
                    <h4>FOR ENTERPRISES</h4>
                    <a href="#"> Zomato For Work</a>
                </div>

                <div class="fifth">
                    <h4>LEARN MORE</h4>
                    <a href="#"> privacy</a>
                    <a href="#"> security</a><br>
                    <a href="#"> Terms</a>
                    <a href="#"> Sitemap</a>
                </div>

                <div class="six">
                    <div>
                    <h4>App Links</h4>
                    <a href="#"> <i class="fa-brands fa-facebook"></i></a>
                    <a href="#"> <i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"> <i class="fa-brands fa-linkedin"></i></a>
                    </div>
                    <div>
                    <img class=" imageslink" src="appstore.png">
                    <img class=" imageslink" src="playstore.png">
                    </div>
                </div>
        </div>
    </div>
                  
                
</section>
        <section class="footer-final">
            <div>
            <hr>
            <p>&copy; By Chandu Kiliveti  you agree to our Terms of Service, Cookie Policy, Privacy Policy and Content Policies. All trademarks are                         properties of their respective owners. 2008-2022 © chandukiliveti™  All rights reserved.</p>
            </div>
        </section>





</body>
</html>
#This is an CSS
*{     font-family: Verdana, Geneva, Tahoma, sans-serif;}
body
{
    margin:0%;
    padding: 0%;
    text-decoration:none;
}

.headd
{
    width:100%;
    height:70vh;
    position:relative;
    overflow:hidden;
    object-fit: cover;
    margin-bottom:5px;

}

.header-image
{
    position:absolute;
    top: -20vh;
    z-index:-1;
}
.nav
{
    display:flex;
    margin: 1vh 10vw;
    justify-content: space-between;
    font-size: 1em;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
    color: white;
   
}

.nav-bar
{
    display: flex;

}
.nav-bar li
{
    font-size: 1em;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    color: white;
    font-weight: lighter;
    list-style:none;
    padding-left: 30px;
}

.headd
{
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-bottom:5px;
    align-items: center;
}
.logo
{
    width:24vw;
    
}
.headd h3
{
    font-size: 2.1em;
    color:whitesmoke;
    font-weight:lighter;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    
}
.search
{
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    border: 400px 5px 400px 5px;
    border-radius:5px;
    margin:5px;
    padding:5px;
    background-color: white;
}
.search input
{
    width:600px;
    font-size: 0.9em;
    font-weight: lighter;
    padding-left:25px;
    color:rgb(156, 156, 156);
    outline: none;
    border:none;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.search p
{
    color:rgb(156, 156, 156);
    font-size: 0.9em;
    padding-left:10px;
    padding-right:10px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.location
{
    color:lightcoral;
    padding-right:10px;
    padding-left:10px;
}
.searchsymbol
{
    padding-left: 10px;
}

.sec1
{
    display: flex;
    justify-content: center;
    margin-top:5px;
}
.box
{
    position:relative;
    width:340px;
    height:210px;
    margin-left:30px;
    border-radius: 15px;
    overflow: hidden;
    background-color: white;
    box-shadow: 0 1px 2px grey;
}
.box img
{
    width:100%;
    height:70%;
    border-radius:5px;
    z-index:-1;
    transition:5s ease;
    transition-delay:4s;

}
.box:hover
{
    transform:scale(1.1);
}
.whitetext
{
    position:absolute;
    bottom:3px;
    align-items: center;
    border:1px gray;
    border-radius:0 0 15px 15px;
    background-color: white;
    font-size: 1rem;
    width:100%;
    height:25%;
    z-index:2;

}
.whitetext span
{
    align-items: center;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 1em;
    font-weight: bolder;
    color:rgb(20, 18, 18);
    letter-spacing: 0.8px;
} 
.whitetext p
{
    align-items: center;
    font-weight: lighter;
    font-size: 1em;
    margin-top:9px;
}
.sec2
{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-left: 30px;
}
.sec2 h1
{
    font-size:2.7rem;
    margin-bottom:5px;
    font-weight: lighter;
}
.sec2_text
{
    display:flex;
    justify-content: space-between;
}
.sec2_P
{
    color:rgb(238, 70, 70);
    margin-left:50px;
}

.box1
{
    width: 335px;
    height:400;
    overflow: hidden;
    position: relative;
    border-radius:  8px;
    
}

.box1 div
{
    position:absolute;
    background:linear-gradient(transparent,black);
    width:82%;
    height: 25%;
    display:flex;
    align-items:flex-end;
    color:white;
    border-radius: 5px;
    bottom:0;
}
.box1 div span:first-child
{
    display:flex;
    color:white;
    padding-left:10px;
    font-size: 1rem;
    padding-bottom: 5px;
}
.box1 img
{
    height: 310px;
    width: 270px;
    border-radius: 5px;

}
.sec3
{
    display: flex;
    margin-top: 30px;
    margin-bottom: 130px;    
}
.h2text
{
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 2.1rem;
    color:rgb(65,64,64);
    font-weight: lighter;
    margin: 50px;
}
.sec-4
{
    display: grid;
    justify-content: center;
    grid-column-gap: 20px;
    grid-row-gap: 30px;
    grid-template-columns: 340px 340px 340px;
    grid-template-rows: auto;
}
.box-2
{
    border:1px solid rgb(235, 233, 233);
    box-shadow: 0 1px 3px whitesmoke;
    width:340px;
    height: 80px;
    overflow:hidden ;
    border-radius:10px;
}
box-2 div
{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin:20px;
    color:black;
    overflow: hidden;
}
.box-2 div span
{
    color:black;
    font-size: 1.2rem;
    display: inline-block;
    text-overflow:ellipsis;
}
.box-2 div span 
{
    color:rgb(112, 105, 105);
    font-weight: lighter;
    font-size: 1rem;
}
.sec3
{
    display: flex;
    justify-content: center;
    margin-left: 30px;
    background-color: rgb(255, 252, 248);
    margin-top: 30px;
}
.mobileimg
{
    border-radius: 5px;
    width:60%;
    height:80%;
    margin-top:60px;
}
.flex
{
    display:flex;
}
.headingtext h2 
{
    font-size: 2.6rem;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
    margin-top: 20px;
    margin-bottom: 25px;
}
.headingtext p
{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
    color:rgb(112, 105, 105);
}
.imageslink img
{  
    height: 40px;
    width: 120px;
    margin-left:20px ;

}
.sec3 h6
{
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-weight: lighter;
    color:rgb(112, 105, 105);
    font-size: 1rem;
    margin-bottom: 15px;

}
.radiobtn
{
    margin-top:25px;
    margin-bottom:10px;
    margin-left:15px;
}
.btn2
{
    margin-left: 40px;
}
input
{
    accent-color: rgb(255,92,92);
}
input [type='radio']
{
    border:0px;
    width:100%;
    height:2em;
}
.btn textarea
{
    border-radius:5px;
    width:80%;
    height:50px;
    margin-bottom: 15px;
}
.btn button
{
    border:rgb(253, 104, 104);
    border-radius :5px;
    width:250px;
    height:60px;
    background-color: rgb(253, 104, 104);
    color:white;
    margin-left:10px;
    margin-bottom:10px;
    overflow:hidden;
    font-size:1rem;
}
.sec4
{
    margin-left: 50px;
    margin-bottom: 50px;
    background-color: rgb(255, 252, 248);

}
.sec4 h1
{
    color:gray;
    font-weight: lighter;
    font-size: 2rem;
    margin-left: 30px;
}

.box3
{
    padding:20px;
    border:1px solid gray;
    border-radius: 5px;
    margin:25px;
    font-size: 1.2rem;
    font-weight: lighter;
    width:70%;
}

.footer
{
    margin-left: 30px;
    background-color: rgb(255, 252, 248);
   
}

.first-1 img
{
    width: 128px;
    height: 35;
}

.first-1
{
    display:flex;
    justify-content: space-between;
    margin-left:30px;
}

.first
{
    display: flex;
    justify-content: space-between;
}
.first span
{
    margin-right:50px;
    border:1px  solid black;
    border-radius:5px;
    font-size:0.9rem;
    padding:10px;
}

.second-phase
{
    display: flex;
    justify-content: space-around;
    margin:30px 0;
}
.second-phase div
{
    width:200px;
}

.second-phase h4
{
    font-weight: lighter;
    color:rgb(22,22,22);
    white-space: nowrap;
}

.second-phase a
{
    display: inline;
    width:200px;
    margin-bottom: 7px;
    text-decoration: none;
    color:gray;
    font-size:0.9rem;
}

.six img
{
    width: 128px;
    height: 35;
}
