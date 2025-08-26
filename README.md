# VIRUSXXX.html
Hallo 
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>System Scan</title>
<style>
  body { font-family: monospace; background: black; color: lime; padding: 20px; }
  #progress { width: 90%; margin: 20px auto; background: #222; border: 1px solid #555; }
  #bar { width: 0%; height: 35px; background: red; transition: width 0.2s linear; }
  #console { margin-top: 20px; height: 300px; overflow-y: auto; border: 1px solid #555; padding: 10px; background: #111; }
  .red { color: red; font-weight: bold; }
</style>
</head>
<body>
<h1>System Scan läuft...</h1>
<div id="progress"><div id="bar"></div></div>
<div id="console"></div>

<script>
let progress = 0;
const bar = document.getElementById('bar');
const consoleDiv = document.getElementById('console');

const fakeFiles = [
  "C:\\Windows\\System32\\kernel32.dll",
  "C:\\Users\\Admin\\Documents\\secret.docx",
  "C:\\Program Files\\App\\data.bin",
  "C:\\Temp\\malware.tmp",
  "D:\\Downloads\\unknown.exe",
  "C:\\Users\\Admin\\Pictures\\image.jpg",
  "C:\\Windows\\Temp\\evil.sys",
  "C:\\Users\\Public\\Videos\\badfile.mp4"
];

const fakeThreats = [
  "Trojaner XYZ entdeckt",
  "Ransomware aktiv",
  "Phishing-Skript erkannt",
  "Gefährliche Datei abc.dll",
  "Unbekanntes Programm blockiert",
  "Kernel Infektion festgestellt",
  "Systemdatei manipuliert"
];

function addConsoleLine(text, cls="") {
  const p = document.createElement("p");
  if(cls) p.className = cls;
  p.innerText = text;
  consoleDiv.appendChild(p);
  consoleDiv.scrollTop = consoleDiv.scrollHeight;
}

function updateScan() {
  if(progress < 100){
    progress += Math.random() * 2 + 0.5; 
    if(progress > 100) progress = 100;
    bar.style.width = progress + "%";

    if(Math.random() < 0.8){
      const file = fakeFiles[Math.floor(Math.random() * fakeFiles.length)];
      addConsoleLine("Scanne Datei: " + file);
    }

    if(Math.random() < 0.2){
      const threat = fakeThreats[Math.floor(Math.random() * fakeThreats.length)];
      addConsoleLine("⚠️ " + threat, "red");
    }

    setTimeout(updateScan, 300);
  } else {
    document.body.innerHTML = `<h1 class="red">⚠️ Virus entdeckt!</h1><p class="red">Gerät wird heruntergefahren...</p>`;
    document.body.style.background = "darkred";
    setTimeout(() => {
      document.body.style.background = "black";
      document.body.innerHTML = `<h1>😂 Alles gut!</h1><p>War nur ein harmloser Prank.</p>`;
    }, 5000);
  }
}

window.onload = updateScan;
</script>
</body>
</html><!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>System Scan</title>
<style>
  body { font-family: monospace; background: black; color: lime; padding: 20px; }
  #progress { width: 90%; margin: 20px auto; background: #222; border: 1px solid #555; }
  #bar { width: 0%; height: 35px; background: red; transition: width 0.2s linear; }
  #console { margin-top: 20px; height: 300px; overflow-y: auto; border: 1px solid #555; padding: 10px; background: #111; }
  .red { color: red; font-weight: bold; }
</style>
</head>
<body>
<h1>System Scan läuft...</h1>
<div id="progress"><div id="bar"></div></div>
<div id="console"></div>

<script>
let progress = 0;
const bar = document.getElementById('bar');
const consoleDiv = document.getElementById('console');

const fakeFiles = [
  "C:\\Windows\\System32\\kernel32.dll",
  "C:\\Users\\Admin\\Documents\\secret.docx",
  "C:\\Program Files\\App\\data.bin",
  "C:\\Temp\\malware.tmp",
  "D:\\Downloads\\unknown.exe",
  "C:\\Users\\Admin\\Pictures\\image.jpg",
  "C:\\Windows\\Temp\\evil.sys",
  "C:\\Users\\Public\\Videos\\badfile.mp4"
];

const fakeThreats = [
  "Trojaner XYZ entdeckt",
  "Ransomware aktiv",
  "Phishing-Skript erkannt",
  "Gefährliche Datei abc.dll",
  "Unbekanntes Programm blockiert",
  "Kernel Infektion festgestellt",
  "Systemdatei manipuliert"
];

function addConsoleLine(text, cls="") {
  const p = document.createElement("p");
  if(cls) p.className = cls;
  p.innerText = text;
  consoleDiv.appendChild(p);
  consoleDiv.scrollTop = consoleDiv.scrollHeight;
}

function updateScan() {
  if(progress < 100){
    progress += Math.random() * 2 + 0.5; 
    if(progress > 100) progress = 100;
    bar.style.width = progress + "%";

    if(Math.random() < 0.8){
      const file = fakeFiles[Math.floor(Math.random() * fakeFiles.length)];
      addConsoleLine("Scanne Datei: " + file);
    }

    if(Math.random() < 0.2){
      const threat = fakeThreats[Math.floor(Math.random() * fakeThreats.length)];
      addConsoleLine("⚠️ " + threat, "red");
    }

    setTimeout(updateScan, 300);
  } else {
    document.body.innerHTML = `<h1 class="red">⚠️ Virus entdeckt!</h1><p class="red">Gerät wird heruntergefahren...</p>`;
    document.body.style.background = "darkred";
    setTimeout(() => {
      document.body.style.background = "black";
      document.body.innerHTML = `<h1>😂 Alles gut!</h1><p>War nur ein harmloser Prank.</p>`;
    }, 5000);
  }
}

window.onload = updateScan;
</script>
</body>
</html><!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<title>System Scan</title>
<style>
  body { font-family: monospace; background: black; color: lime; padding: 20px; }
  #progress { width: 90%; margin: 20px auto; background: #222; border: 1px solid #555; }
  #bar { width: 0%; height: 35px; background: red; transition: width 0.2s linear; }
  #console { margin-top: 20px; height: 300px; overflow-y: auto; border: 1px solid #555; padding: 10px; background: #111; }
  .red { color: red; font-weight: bold; }
</style>
</head>
<body>
<h1>System Scan läuft...</h1>
<div id="progress"><div id="bar"></div></div>
<div id="console"></div>

<script>
let progress = 0;
const bar = document.getElementById('bar');
const consoleDiv = document.getElementById('console');

const fakeFiles = [
  "C:\\Windows\\System32\\kernel32.dll",
  "C:\\Users\\Admin\\Documents\\secret.docx",
  "C:\\Program Files\\App\\data.bin",
  "C:\\Temp\\malware.tmp",
  "D:\\Downloads\\unknown.exe",
  "C:\\Users\\Admin\\Pictures\\image.jpg",
  "C:\\Windows\\Temp\\evil.sys",
  "C:\\Users\\Public\\Videos\\badfile.mp4"
];

const fakeThreats = [
  "Trojaner XYZ entdeckt",
  "Ransomware aktiv",
  "Phishing-Skript erkannt",
  "Gefährliche Datei abc.dll",
  "Unbekanntes Programm blockiert",
  "Kernel Infektion festgestellt",
  "Systemdatei manipuliert"
];

function addConsoleLine(text, cls="") {
  const p = document.createElement("p");
  if(cls) p.className = cls;
  p.innerText = text;
  consoleDiv.appendChild(p);
  consoleDiv.scrollTop = consoleDiv.scrollHeight;
}

function updateScan() {
  if(progress < 100){
    progress += Math.random() * 2 + 0.5; 
    if(progress > 100) progress = 100;
    bar.style.width = progress + "%";

    if(Math.random() < 0.8){
      const file = fakeFiles[Math.floor(Math.random() * fakeFiles.length)];
      addConsoleLine("Scanne Datei: " + file);
    }

    if(Math.random() < 0.2){
      const threat = fakeThreats[Math.floor(Math.random() * fakeThreats.length)];
      addConsoleLine("⚠️ " + threat, "red");
    }

    setTimeout(updateScan, 300);
  } else {
    document.body.innerHTML = `<h1 class="red">⚠️ Virus entdeckt!</h1><p class="red">Gerät wird heruntergefahren...</p>`;
    document.body.style.background = "darkred";
    setTimeout(() => {
      document.body.style.background = "black";
      document.body.innerHTML = `<h1>😂 Alles gut!</h1><p>War nur ein harmloser Prank.</p>`;
    }, 5000);
  }
}

window.onload = updateScan;
</script>
</body>
</html>
