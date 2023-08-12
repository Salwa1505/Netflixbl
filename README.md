# Netflixbl
Netflix clone using html and css

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <div class="header">
        <nav>
            <img src="logo.png" class="logo">
            <div>
                <button class="language-btn">English <img src="down-icon.png"></button>
                <button>Sign in</button>
            </div>
        </nav>
        <div class="header-content">
            <h1>Unlimited movies, TV shows and more.</h1>
            <h3>Watch anywhere. Cancel anytime.</h3>
            <p>Ready to watch? Enter your email to create or restart your membership.</p>
            <form class="email-signup">
                <input type="email" placeholder="Email address" required>
                <button type="submit">Get Staeted</button>
            </form>

        </div>

    </div>
    
    <div class="features">
        <div class="row">
           
            <div class="text-col">
                <h2>Enjoy on your TV.</h2>
                <p>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
            </div>
            <div class="img-col">
                <img src="feature-1.png">
            </div>
        </div>
        <div class="row">
            <div class="img-col">
                <img src="feature-2.png">
            </div>
           
            <div class="text-col">
                <h2>Download your shows to watch offline.</h2>
                <p>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
            </div>
            
        </div>
        <div class="row">
           
            <div class="text-col">
                <h2>Watch everywhere</h2>
                <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
            </div>
            <div class="img-col">
                <img src="feature-3.png">
            </div>
        </div>
        <div class="row">
            <div class="img-col">
                <img src="feature-4.png">
            </div>
           
            <div class="text-col">
                <h2>Create profiles for kids</h2>
                <p>Send children on adventures with their favourite characters in a space made just for them—free with your membership.</p>
            </div>
            
        </div>
        <div class="faq">
            <h2>Frequently Asked Question</h2>
            <ul class="accordion">
                <li>
                    <input type="radio" name="accordion" id="first">
                    <label for="first">what is Netflix</label>
                    <div class="content">
                        <p>Netflix is a streaming service that offers a wide variety of award-winning TV shows, movies, anime, documentaries and more – on thousands of internet-connected devices.

                            You can watch as much as you want, whenever you want, without a single ad – all for one low monthly price. There's always something new to discover, and new TV shows and movies are added every week!</p>
                    </div>
                </li>
                <li>
                    <input type="radio" name="accordion" id="second">
                    <label for="second">How much does Netflix cost</label>
                    <div class="content">
                        <p>Watch Netflix on your smartphone, tablet, Smart TV, laptop, or streaming device, all for one fixed monthly fee. Plans range from ₹ 149 to ₹ 649 a month. No extra costs, no contracts.</p>
                    </div>
                </li>
                <li>
                    <input type="radio" name="accordion" id="third">
                    <label for="third">where can i watch</label>
                    <div class="content">
                        <p>Watch anywhere, anytime. Sign in with your Netflix account to watch instantly on the web at netflix.com from your personal computer or on any internet-connected device that offers the Netflix app, including smart TVs, smartphones, tablets, streaming media players and game consoles.

                        You can also download your favourite shows with the iOS, Android, or Windows 10 app. Use downloads to watch while you're on the go and without an internet connection. Take Netflix with you anywhere.</p>
                    </div>
                </li>
                <li>
                    <input type="radio" name="accordion" id="fourth">
                    <label for="fourth">how do i cancel</label>
                    <div class="content">
                        <p>Netflix is flexible. There are no annoying contracts and no commitments. You can easily cancel your account online in two clicks. There are no cancellation fees – start or stop your account anytime.</p>
                    </div>
                </li>
                <li>
                    <input type="radio" name="accordion" id="fifth">
                    <label for="fifth">what can i watch on Netflix</label>
                    <div class="content">
                        <p>Netflix has an extensive library of feature films, documentaries, TV shows, anime, award-winning Netflix originals, and more. Watch as much as you want, anytime you want.</p>
                    </div>
                </li>
                <li>
                    <input type="radio" name="accordion" id="sixth">
                    <label for="sixth">is Netflix good for kids?</label>
                    <div class="content">
                        <p>The Netflix Kids experience is included in your membership to give parents control while kids enjoy family-friendly TV shows and films in their own space.

                            Kids profiles come with PIN-protected parental controls that let you restrict the maturity rating of content kids can watch and block specific titles you don’t want kids to see.</p>
                    </div>
                </li>

            </ul>
            <small>Ready to watch? Enter your email to create or restart your membership.
            </small>
            <form class="email-signup">
                <input type="email" placeholder="Email address" required>
                <button type="submit">Get Staeted</button>
            </form>
            
        </div>
   
        
    </div>
    <div class="footer">
        <h2>Question? call 000-000-000-000 </h2>
        <div class="row">
            <div class="col">
                <a href="#">FAQ</a>
                <a href="#">Investor realation</a>
                <a href="#">privacy</a>
                <a href="#">speed test</a>
            </div>
            <div class="col">
                <a href="#">help center</a>
                <a href="#">jobs</a>
                <a href="#">cockies perfoemance</a>
                <a href="#">Legal notices</a>
            </div>
            <div class="col">
                <a href="#">account</a>
                <a href="#">ways to watch</a>
                <a href="#">corporate information</a>
                <a href="#">only on Netflix</a>
            </div>
            <div class="col">
                <a href="#">media center</a>
                <a href="#">terms of usage</a>
                <a href="#">content us</a>
            </div>
        </div>
        <button class="language-btn">English <img src="down-icon.png"></button>
        <p class="copyraight-txt">Netflix India</p>        
    </div>
    
</body>
</html>


#css code
*{
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    box-sizing: border-box;
}
body{
    background-color: #000;
    color: #fff;
}
.header{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)), url(background.jpg);
    background-size: cover;
    background-position: center;
    padding: 10px 8%;
    position: relative;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 0;
}
.logo{
    width: 150px;
    cursor: pointer;
}
nav button{
    border: 0;
    outline: 0;
    background: #db0001;
    color: #fff;
    padding: 7px 20px;
    font-size: 12px;
    border-radius: 4px;
    margin-left: 10px;
    cursor: pointer;
}
.language-btn{
    display: inline-flex;
    align-items: center;
    background: transparent;
    border: 1px solid #fff;
    padding: 7px 10px;
}
.language-btn img{
    width: 10px;
    margin-left: 10px;
}
.header-content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    margin-top: 100px;

}
.header-content h1{
    font-size: 60px;
    line-height: 60px;
    font-weight: 600;
    max-width: 650px;
}
.header-content h3{
    font-weight: 400;
    margin-bottom: 20;
    margin-top: 5%;
    
}
.header-content p{
    font-weight: 400;
    margin-bottom: 20;
    margin-top: 1%;
    
}
.email-signup{
    background: #fff;
    border-radius: 4px;
    display: flex;
    align-items: center;
    margin-top: 30px;
    overflow: hidden;
}
.email-signup input{
    flex: 1;
    border: 0;
    outline: 0;
    margin-left: 20px;
}
.email-signup button{
    background: #db0001;
    border: 0;
    outline: 0;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
    padding: 15px 30px;

}

/*--------------features---------------*/
.features{
    padding: 50px 12%;
    font-size: 22px;
}
.row{
    display: flex;
    width: 100%;
    align-items: center;
    padding: 50px 0;
}
.text-col{
    flex-basis: 50%;
    margin-bottom: 20px;
}
.img-col{ flex-basis: 50%;
    margin-bottom: 20px;
}
.img-col img{
    display: block;
    width: 90%;
    margin: auto;
}
.features h2{
    font-size: 50px;
    font-weight: 600;
    margin-bottom: 20;
    
}
/*------------------faq--------------------------*/
.faq{
    padding: 10px 12px;
    text-align: center;
    font-size: 180x;
}
.faq h2{
    font-weight: 800;
    font-size: 40px;
}
.accordion{
    margin: 60px auto;
    width: 100%;
    max-width: 750px;
}
.accordion li{
    list-style: none;
    width: 100%;
    padding: 5px;
}
  .accordion li label{
    display: flex;
    align-items: center;
    padding: 20px;
    font-size: 18px;
    font-weight: 500;
    background: #303030;
    margin-bottom: 2px;
    cursor: pointer;
    position: relative;
}
label::after{
    content: '+';
    font-size: 34px;
    position: absolute;
    right: 20px;
    transition: transform 0.5s;
}
input[type="radio"]{
    display: none;
}
.accordion .content{
    background: #303030;
    text-align: left;
    padding: 0 20px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s, padding 0.5s ;
}
.accordion input[type="radio"]:checked+label+.content{
 max-height: 600px;
padding: 30px 20px;
}
.accordion input[type="radio"]:checked+label::after{
    transform:rotate(135deg) ;
}
.faq .email-signup{
    max-width: 600px;
    margin: 20px auto 60px;
}
/*------------------------------footer-----------------------------*/
.footer{
    padding: 50px 15% 10px;
    border-top: 6px solid #333;
    color: #777;
}
.footer h2{
    font-size: 18px;
    font-weight: 400;
    margin-bottom: 30;
}
.footer .col{
    flex-basis: 25%;
    flex-grow: 1;
    margin-bottom: 20px;
}
.footer .col a{
    display: block;
    text-decoration: none;
    color: #777;
    font-size: 14px;
    margin-bottom: 10px;
}
.footer .row{
    align-items: flex-start;
    padding: 10px;
}
.footer .language-btn{
    color: #fff;
    padding: 10px 20px;
    border-radius: 3px;
}
.copyraight-txt{
    font-size: 14px;
    margin-top: 20px;
    margin-bottom: 10px;
}
