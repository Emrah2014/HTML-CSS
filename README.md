# HTML-CSS
This is a HTML & CSS assignment

index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Figma to HTML & CSS 1</title>
    <link rel="stylesheet" href="/styles.css">
</head>
<body>
    <div class="app">
        <div class="heading-section">
            <h4 class="section-title">
                Enter the world of all fashion trends
            </h4>
            <p class="section-description">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Venenatis scelerisque at quam congue posuere libero in sit quam. Consequat, scelerisque non tincidunt sit lectus senectus.
            </p>
        </div>
        <div class="features-list-section">
            <div class="feature-row-top">
                <div class="feature-column">
                    <img src="images/Cover Image.png" alt="Cover Image">
                </div>
            </div>
        </div>
    </div>    
</body>
</html>

styles.css
* {
margin: 0;
padding: 0;
box-sizing: border-box;
}

.app {
width: 100vw;
height: 100vh;
background-color: #fff;
display: flex;
flex-direction: column;
justify-content: center;
gap: 48px;
}

.heading-section{
    max-width: 1110px;
    max-height: 5px;
    margin-top: 64px;
    margin: auto;
}
.section-title {
    font-family:"Inter", sans-serif;
    font-size: 40px;
    font-weight: 800;
    line-height: 54px;
    text-align: left;
    max-width: 540px;
    max-height: 108px;
    margin-top: 10px;
}

.section-description {
    font-family:"Inter", sans-serif;
    font-size: 20px;
    font-weight: 400;
    line-height: 32px;
    text-align: left;
    max-width: 540px;
    max-height: 128px;
    margin-left: 570px;
    margin-top: -100px;
}

.feature-column {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-bottom: 64px;
}
