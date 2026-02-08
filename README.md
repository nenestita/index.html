<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Xatspace Tita</title>
    <style>
        /* Configuration de la page */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background: #000;
            font-family: 'Trebuchet MS', sans-serif;
            overflow: hidden; /* Empêche le scroll inutile */
        }

        /* L'Overlay qui contient le GIF et cache le header xat */
        .overlay-fix {
            position: fixed;
            top: -150px; /* Remonte pour couvrir le nom/id xat */
            left: 0;
            width: 100%;
            height: calc(100% + 150px);
            background: url('https://xatimg.com/image/MbGcCOEqZkY6.gif') no-repeat center center;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 999999;
        }

        /* Ton cadre violet avec les infos */
        .card {
            width: 550px;
            height: 350px;
            background: rgba(0, 0, 0, 0.85); /* Fond noir semi-transparent */
            border: 2px solid #8a2be2;
            border-radius: 20px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 0 30px rgba(138, 43, 226, 0.6);
            margin-top: 150px; /* Aligne le cadre au centre visuel */
            position: relative;
        }

        /* Style des éléments internes */
        .profile-img { 
            width: 75px; height: 75px; border-radius: 50%; 
            border: 2px solid #8a2be2; margin-top: 15px; 
        }
        
        .name { font-size: 26px; font-weight: bold; color: #8a2be2; margin-top: 15px; }
        
        .desc { font-size: 14px; color: #a366ff; font-weight: bold; margin: 15px 40px; line-height: 1.4; }
        
        .quote { font-size: 18px; color: #8a2be2; font-style: italic; font-weight: bold; margin-bottom: 30px; }
        
        /* Barre d'icônes */
        .icons { 
            background: rgba(26, 0, 51, 0.9); border-radius: 50px; border: 1px solid #8a2be2; 
            width: 320px; margin: 20px auto; padding: 12px;
            display: flex; justify-content: center; gap: 20px;
        }
        
        .icons img { width: 30px; height: 30px; transition: 0.3s; }
        .icons img:hover { transform: scale(1.2); filter: brightness(1.2); }
        
        a { text-decoration: none; }
    </style>
</head>
<body>

<div class="overlay-fix">
    <div class="card">
        <img src="https://xatimg.com/image/jErnhZ84UiT4.png" class="profile-img">
        
        <div class="name">Hi i'm Tita</div>
        
        <div class="desc">You can find me on xat.com/Blog, xat.com/Assistance and xat.com/Chat.</div>
        
        <div class="quote">deen over dunya</div>
        
        <div class="icons">
            <a href="https://forum.xat.com/profile/55475/" target="_blank"><img src="https://xatimg.com/image/88aRECutI7NF.png" alt="Forum"></a>
            <a href="https://www.youtube.com/watch?v=25MmCEpftKo" target="_blank"><img src="https://xatimg.com/image/vrKvF4ppWX7k.png" alt="YouTube"></a>
            <a href="https://www.twitch.tv/nenestita" target="_blank"><img src="https://xatimg.com/image/uNanyd1lgtLe.png" alt="Twitch"></a>
            <a href="https://xat.com/blog" target="_blank"><img src="https://xatimg.com/image/NycXn0QvBMnh.png" alt="Blog"></a>
        </div>
    </div>
</div>

</body>
</html>
