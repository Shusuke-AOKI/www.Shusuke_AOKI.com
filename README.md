# www.Shusuke_AOKI.com
Just for fun
<!DOCTYPE html>
<html lang="en">
<head>    
    <meta charset="UTF-8">    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
    <title>Shusuke AOKI</title>    
    <link rel="stylesheet" href="style.css">
</head>
<body>    
    <h1>Shusuke</h1>
    <div class="image-container">
        <img src="Shusuke.jpg" alt="Shusuke Image" class="responsive-image">
        <img src="Doraemon_13rd.jpg" alt="Doraemon Image" class="responsive-image">
    </div>   
    <h1>My YouTube Link</h1>    
    <a href="https://www.youtube.com/watch?v=XqlK3lzmcLA">Watch this video</a>
</body>


/* style.css */
body {
    background-color: lightblue;
    text-align: center;
}

h1 {
    color: navy;
    text-align: center;
}

.image-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px; /* 画像の間隔を調整 */
}

.responsive-image {
    width: 300px;
    height: 300px;
    object-fit: cover; /* 画像が枠にフィットするように調整 */
