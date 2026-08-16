# Vartan-Perla-Wedding
<!DOCTYPE html>
<html>
<head>
    <title>Vartan & Perla</title>

    <style>

        body{
            margin:0;
            background:black;
            color:white;
            font-family:Georgia;
            text-align:center;
        }

        .hero{
            height:100vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
        }

        h1{
            font-size:60px;
        }

        p{
            font-size:24px;
        }

        button{
            padding:15px 30px;
            font-size:18px;
            cursor:pointer;
        }

    </style>

</head>

<body>

<div class="hero">

    <h1>Vartan & Perla</h1>

    <p>October 23rd, 2026</p>

    <p>We invite you to celebrate our wedding</p>

    <button onclick="playMusic()">
      Enter
    </button>

</div>

<audio id="music" loop>

    music.mp3

</audio>

<script>

function playMusic(){

document.getElementById("music").play();

}

</script>

</body>
</html>
