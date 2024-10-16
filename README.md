<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Serkan Atuğ - Geliştirici Profili</title>
    <link rel="stylesheet" href="styles.css">
</head>
  <style>
    * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #2C3E50;
    color: #ECF0F1;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
}

.container {
    text-align: center;
}

.welcome {
    font-size: 3rem;
    letter-spacing: 5px;
    opacity: 0;
    animation: fadeIn 1s forwards;
}

.name, .surname {
    display: inline-block;
    opacity: 0;
    transform: translateY(20px);
    animation: slideIn 0.5s forwards;
}

.name {
    animation-delay: 0.5s; /* Adın daha sonra yazılacak */
}

.surname {
    animation-delay: 1s; /* Soyadın daha sonra yazılacak */
}

.image {
    margin: 20px 0;
}

.quote {
    font-style: italic;
    margin: 20px 0;
}

.info {
    list-style: none;
    padding: 0;
    margin: 20px 0;
}

.social {
    margin: 20px 0;
}

.tools img {
    margin: 0 10px;
}

h3 {
    margin-top: 20px;
    margin-bottom: 10px;
}

ul {
    list-style-type: none;
    margin-top: 10px;
}

@keyframes slideIn {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeIn {
    to {
        opacity: 1;
    }
}

  </style>
<body>
    <div class="container">
        <h1 class="welcome">👋 Merhaba, Ben <span class="name">Serkan</span> <span class="surname">Atuğ!</span></h1>
        <h3>Türkiye'den Tutkulu Bir Frontend Geliştirici</h3>

        <p class="image">
            <img src="https://media.giphy.com/media/1i6I0rHpM2MNSrY4PH/giphy.gif" alt="Hello" width="200"/>
        </p>

        <p class="quote">
            <em>"Kodlama sadece bir iş değil, bir tutku!"</em>
        </p>

        <ul class="info">
            <li>🔭 Şu anda <strong>Python</strong> üzerinde çalışıyorum.</li>
            <li>🌱 Şu anda <strong>Python, PHP</strong> öğreniyorum.</li>
            <li>💬 <strong>HTML, CSS</strong> hakkında sorular sorabilirsiniz.</li>
            <li>📫 Bana ulaşmak için: <a href="mailto:serkanatugxl3547@gmail.com">serkanatugxl3547@gmail.com</a></li>
        </ul>

        <h3 class="connect">Benimle Bağlantı Kurun:</h3>
        <p class="social">
            <a href="https://instagram.com/sserkkan35/" target="_blank">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="serkanatgg35" height="30" width="40"/>
            </a>
        </p>

        <h3>Kullandığım Diller ve Araçlar:</h3>
        <p class="tools">
            <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> 
            </a> 
            <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 
            </a> 
            <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> 
            </a> 
            <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> 
            </a> 
            <a href="https://sass-lang.com" target="_blank" rel="noreferrer">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> 
            </a> 
            <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
                <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> 
            </a>
        </p>

        <h3>Akademik Geçmiş:</h3>
        <ul>
            <li>Bilişim Teknolojileri, Selçuk Yaşar Boyacılık Mesleki ve Teknik Anadolu Lisesi.</li>
            <li><a href="https://aku.edu.tr//" target="_blank">Bilgisayar Programlama, Afyon Kocatepe Üniversitesi</a></li>
        </ul>
    </div>
</body>
</html>
