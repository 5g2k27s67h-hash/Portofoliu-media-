# Portofoliu-media-
Proiectul meu pentru ora de modul cu domnul Sergiu podoreanu 
<!DOCTYPE html>

<html lang="ro">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Test de verificare – Portofoliu media</title>
<style>
body {
font-family: Arial, sans-serif;
max-width: 850px;
margin: 0 auto;
padding: 25px;
line-height: 1.7;
color: #222;
background: #f4f6fa;
}
h1 {
text-align: center;
color: #563d7c;
}
h2 {
color: #563d7c;
font-size: 20px;
}
.question {
background: white;
padding: 18px;
margin: 18px 0;
border-radius: 10px;
border-left: 5px solid #563d7c;
}
.answer {
margin-top: 10px;
}
header {
text-align: center;
padding: 20px;
background: #e9e1f5;
border-radius: 12px;
}
footer {
text-align: center;
margin-top: 30px;
color: #666;
}
</style>
</head>
<body>

<header>
<h1>PORTOFOLIU MEDIA</h1>
<p><strong>Fișă de laborator – Test de verificare</strong></p>
<p>Liceul Tehnologic „Grigore C. Moisil” Buzău</p>
<p>Producție media · Clasa a XII-a</p>
</header>

<h2>15. Test de verificare – Întrebări și răspunsuri</h2>

<div class="question">
<h2>1. Ce este un depozit și ce conține în plus față de un folder obișnuit de pe calculator?</h2>
<div class="answer">Un depozit (repository) este un spațiu online în care se păstrează fișiere și foldere. În plus față de un folder obișnuit, are o adresă proprie și păstrează istoricul modificărilor și versiunile fișierelor.</div>
</div>

<div class="question">
<h2>2. Ce este un commit? Ce informații înregistrează GitHub la fiecare commit?</h2>
<div class="answer">Un commit reprezintă salvarea modificărilor într-un depozit. GitHub înregistrează modificările, mesajul commitului, data, ora și autorul.</div>
</div>

<div class="question">
<h2>3. Care sunt regulile GitHub pentru parolă și pentru numele de utilizator?</h2>
<div class="answer">Parola trebuie să aibă cel puțin 15 caractere sau cel puțin 8 caractere, dintre care o cifră și o literă mică. Numele de utilizator poate conține litere, cifre și cratime simple, dar nu poate începe sau termina cu o cratimă.</div>
</div>

<div class="question">
<h2>4. Dintre ana-ionescu, -ana-, ana ionescu și ana_ionescu, care sunt acceptate de GitHub? Justifică răspunsul.</h2>
<div class="answer">
<ul>
<li><strong>ana-ionescu</strong> – acceptat.</li>
<li><strong>-ana-</strong> – neacceptat, deoarece începe și se termină cu o cratimă.</li>
<li><strong>ana ionescu</strong> – neacceptat, deoarece conține un spațiu.</li>
<li><strong>ana_ionescu</strong> – neacceptat, deoarece conține caracterul underscore.</li>
</ul>
</div>
</div>

<div class="question">
<h2>5. Ce se face pe calculatorul din laborator la sfârșitul orei și de ce?</h2>
<div class="answer">Se apasă pe fotografia de profil din dreapta sus și se selectează Sign out. Astfel, contul personal nu rămâne conectat pe calculatorul laboratorului.</div>
</div>

<div class="question">
<h2>6. Prin ce diferă un depozit Public de unul Private? Care se alege pentru portofoliu și de ce?</h2>
<div class="answer">Un depozit Public poate fi văzut de oricine, iar unul Private poate fi accesat numai de proprietar și de persoanele autorizate. Pentru portofoliul online se alege Public, astfel încât lucrările să poată fi văzute printr-un link și publicate cu GitHub Pages în condițiile planului gratuit.</div>
</div>

<div class="question">
<h2>7. Rescrie corect numele: „Temă 2 Pliant” și „Pliant FINAL.PDF”.</h2>
<div class="answer">Folder: <strong>tema-02-pliant</strong><br>Fișier: <strong>pliant-final.pdf</strong></div>
</div>

<div class="question">
<h2>8. Care sunt limitele la încărcarea din browser?</h2>
<div class="answer">Un fișier poate avea maximum 25 MB, iar într-o singură operație se pot încărca maximum 100 de fișiere.</div>
</div>

<div class="question">
<h2>9. Afișul a fost corectat. Cum se încarcă varianta nouă și ce se întâmplă cu cea veche?</h2>
<div class="answer">Se intră în folderul temei și se încarcă varianta corectată cu exact același nume, folosind Add file → Upload files. Se apasă Commit changes. Varianta curentă este înlocuită, iar cea veche poate fi consultată în istoric.</div>
</div>

<div class="question">
<h2>10. Scrie un mesaj de commit potrivit pentru înlocuirea fotografiei de pe fața pliantului de la tema 2.</h2>
<div class="answer"><strong>Tema 2 – pliant: înlocuit fotografia de pe față.</strong></div>
</div>

<div class="question">
<h2>11. Utilizatorul maria-stan are depozitul portofoliu-media, cu fișierul pliant.pdf în folderul tema-02-pliant. Scrie adresa depozitului, adresa site-ului și adresa fișierului pe site.</h2>
<div class="answer">
<strong>Depozit:</strong> https://github.com/maria-stan/portofoliu-media<br>
<strong>Site:</strong> https://maria-stan.github.io/portofoliu-media/<br>
<strong>Fișier PDF:</strong> https://maria-stan.github.io/portofoliu-media/tema-02-pliant/pliant.pdf
</div>
</div>

<div class="question">
<h2>12. Care sunt pașii de activare a GitHub Pages? Ce fișier este prima pagină a site-ului?</h2>
<div class="answer">Se intră în Settings → Pages. La Source se alege Deploy from a branch, la Branch se selectează main, iar folderul se setează la /(root). Se apasă Save și se așteaptă publicarea. Prima pagină este index.html, dacă există în rădăcina depozitului.</div>
</div>

<div class="question">
<h2>13. Fragmentul HTML conține patru greșeli. Rescrie-l corect.</h2>
<div class="answer">
<p>Fragment corect:</p>
<pre><code>&lt;h2&gt;Tema 2 – Pliant&lt;/h2&gt;
&lt;img src="tema-02-pliant/pliant-fata.png" alt="Fața pliantului"&gt;
&lt;p&gt;&lt;a href="tema-02-pliant/pliant.pdf"&gt;Deschide pliantul (PDF)&lt;/a&gt;&lt;/p&gt;</code></pre>
<p>Explicație: se închide corect titlul, imaginea folosește calea relativă din depozit, PDF-ul se deschide printr-un link, iar numele folderelor și fișierelor trebuie să corespundă exact celor existente.</p>
</div>
</div>

<div class="question">
<h2>14. Numește trei lucruri care nu se publică într-un depozit public.</h2>
<div class="answer">
<ol>
<li>Parole și coduri de acces.</li>
<li>CNP și copii ale documentelor personale.</li>
<li>Adresa de domiciliu și numărul personal de telefon.</li>
</ol>
</div>
</div>

<footer>
<p>Portofoliu media · Producție media · Clasa a XII-a</p>
<p>Creat cu GitHub Pages</p>
</footer>

</body>
</html>
