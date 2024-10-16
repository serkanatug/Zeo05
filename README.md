 <style>
        h1 {
            font-size: 36px; /* Başlık boyutunu ayarlayın */
            color: #333; /* Başlık rengi */
            text-align: center; /* Başlık merkezde hizalanır */
            margin: 0; /* Varsayılan margin'i sıfırlar */
        }
        .letter {
            display: inline-block;
            opacity: 0; /* Başlangıçta görünmez */
            transition: opacity 0.5s ease; /* Opaklık geçiş efekti */
        }
    </style>
</head>
<h1 id="greeting"></h1> <!-- Harflerin görüneceği başlık -->

<script>
    const message = "👋 Merhaba, Ben Serkan Atuğ!";
    const greetingElement = document.getElementById("greeting");
    
    let index = 0;

    function displayNextLetter() {
        if (index < message.length) {
            const span = document.createElement("span");
            span.className = "letter";
            span.textContent = message[index];
            greetingElement.appendChild(span);
            
            // Harfi görünür yap
            setTimeout(() => {
                span.style.opacity = 1;
            }, 10); // Harf eklendikten hemen sonra opaklık geçişini başlat
            
            index++;
            setTimeout(displayNextLetter, 300); // 300ms aralıkla harfleri göster
        }
    }

    displayNextLetter(); // İşlemi başlat
</script>
<h3 align="center">Türkiye'den Tutkulu Bir Frontend Geliştirici</h3>

<p align="center">
  <img src="https://media.giphy.com/media/1i6I0rHpM2MNSrY4PH/giphy.gif" alt="Hello" width="200"/>
</p>

<p align="center">
  <em>
    "Kodlama sadece bir iş değil, bir tutku!" 
  </em>
</p>

- 🔭 Şu anda [LavanderProjects](https://github.com/LavanderProjects) üzerinde çalışıyorum.
- 🌱 Şu anda **Python, PHP** öğreniyorum.
- 💬 **HTML, CSS** hakkında sorular sorabilirsiniz.
- 📫 Bana ulaşmak için: [serkanatugxl3547@gmail.com](mailto:serkanatugxl3547@gmail.com)

<h3 align="left">Benimle Bağlantı Kurun:</h3>
<p align="left">
  <a href="https://instagram.com/sserkkan35/" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="serkanatgg35" height="30" width="40" />
  </a>
</p>

<h3 align="left">Kullandığım Diller ve Araçlar:</h3>
<p align="left"> 
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> 
  </a> 
  <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> 
  </a> 
  <a href="https://www.javascript.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> 
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> 
  </a> 
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> 
  </a> 

<a href="https://www.python.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> 
  </a>
</p>


<h3 align="left">Akademik Geçmiş:</h3>
<p align="left">
  <ul>
    <li>Bilişim Teknolojileri,  Selçuk Yaşar Boyacılık Mesleki ve Teknik Anadolu Lisesi.</li>
    <li>Bilgisayar Programcılığı, Afyon Kocatepe Universty</li>
  </ul>
</p>
