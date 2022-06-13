<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none;
    font-family: sans-serif;
    font-size: 14px;
}

body {
    width: 100%;
    min-height: 100vh;
    background-color: rgb(243, 243, 243);
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

.instagram-wrapper {
    display: flex;
    align-items: center;
    justify-content: start;
    width: 60%;
    height: 100vh;
}

.instagram-phone {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50%;
}

.instagram-phone img {
    height: 50rem;
}

.instagram-continue {
    display: flex;
    align-items: center; /* horizontal */
    justify-content: space-around; /* vertical */
    flex-direction: column;
    width: 50%;
    min-height: 34rem;
}

.group {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    background-color: #ffffff;
    width: 100%;
    padding: 1.3rem 0;
    border: 1px solid lightgray;
}

.group:nth-child(1) {
    min-height: 19rem;
}

.instagram-logo {
    height: 3rem;
}

.profile-photo {
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    overflow: hidden;
}

.profile-photo img {
    height: 6rem;
}

.instagram-login {
    background-color: #0095f6;
    color: #ffffff;
    padding: 8px;
    border-radius: 4px;
}

.instagram-logout {
    color: #0095f6;
    margin-top: 1rem;
}

.not-account {
    color: rgb(160, 160, 160);
}

.link-blue {
    color: #0095f6;
}

.get-the-app {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 1.3rem 0;
}

.download {
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    align-items: center;
    padding: 1rem;
}

.app-download {
    height: 3rem;
    width: 10rem;
    background-size: cover;
}

.app-download:nth-child(1) {
    background-image: url('./img/apple-button.png');
}

.app-download:nth-child(2) {
    background-image: url('./img/googleplay-button.png');
}

/* media queries */


@media (max-width: 1024px) {
    .instagram-wrapper {
        width: 90%;
    }
}

@media (max-width: 650px) {
    body {
        background-color: #ffffff;
    }

    .instagram-wrapper {
        width: 90%;
    }

    .instagram-phone {
        display: none;
    }

    .instagram-continue {
        width: 100%;
    }
    
    .group {
        border: 1px solid transparent;
    }
}
  </style>
    <title>Projeto Dio</title>
</head>
<body>
    <div class="instagram-wrapper">
        <div class="instagram-phone">
            <img src="./img/instagram-celular.png" alt="celular">
        </div>
        <div class="instagram-continue">
            <div class="group">
                <img src="./img/instagram-logo.png" class="instagram-logo" alt="instagram logo">
                <div class="profile-photo">
                    <img src="./img/274551476_466358595210833_5125513347978964886_n.jpg" alt="foto de perfil">
                </div>
                <a href="#" class="instagram-login">Continue como Lucasmarques676</a>
                <a href="#" class="instagram-logout">Remover conta</a>
            </div>
            <div class="group">
                <p class="not-account">Não é Lucasmarques676?</p>
                <p class="not-account">
                    <span class="link-blue">Alternar contas</span>
                    ou
                    <span class="link-blue">Inscreva-se</span>
                </p>
            </div>
            <div class="get-the-app">
                <p class="get-app">Baixe o aplicativo</p>
                <div class="download">
                    <a href="#" class="app-download"></a>
                    <a href="#" class="app-download"></a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
