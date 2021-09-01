# CSS_Clone_Google_serch
Clone of the Google page, applying my knowledge of CSS and HTML.

!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   <link rel="stylesheet" href="css/main.css">
</head>
<body>
    <header>
        <nav>
            <ul class="nav-left-section">
                <li> 
                <a href="">About</a>
            </li>
            <li>
                <a href="">Store</a>
            </li>
            </ul>

            <ul class="nav-right-section">
                <li> 
                    <a href="">Gmail</a>
                </li>
                <li>
                    <a href="">Images</a>
                </li>
                <li class="menu-icon">
                    <a href=""></a>
                </li>
                <li>
                    <a href="">
                        <img src="https://lh3.googleusercontent.com/ogw/ADea4I5ggRubtNpDph1wy0s9Aa1L3h01WUlezqyjvXS3-w=s32-c-mo" alt="">
                    </a>
                </li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="main-logo">
            <img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" alt="">
        </section>
        <section class="main-input">
            <div class="main-input-container">
                <span class= "serch-icon">
                </span>
                <input type="text">
                <a class= "micro-icon" href=""></a>
            </div>
        </section>
 
        <section class="main-buttons">
         <div> 
             <button>Google Search</button>
         </div>
         <div>
             <button>I'm Feeling Lucky</button>
         </div>
         </section>
    </main>
    <footer>
        <ul class="footer-left">
            <li>
                <a href="">Advertising</a>
            </li>
            <li>
                <a href="">Business</a>
            </li>
            <li>
                <a href="">How Search works</a>
            </li>
        </ul>
        <ul class="footer-right">
            <li>
                <a href="">Privacy</a>
            </li>
            <li>
                <a href="">Terms</a>
            </li>
            <li>
                <a href="">Settings</a>
            </li>
        </ul>
    </footer>
</body>
</html>

