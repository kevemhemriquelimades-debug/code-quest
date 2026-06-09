<!DOCTYPE html>
<html>
<head>
<title>Aprender Programação</title>
</head>
<body>

<h1>📚 Aprender Programação</h1>

<button onclick="explicar('print')">🖨️ PRINT</button>
<button onclick="explicar('move')">➡️ MOVE</button>
<button onclick="explicar('repeat')">🔁 REPEAT</button>

<p id="info"></p>

<script>
function explicar(bloco){

if(bloco==='print'){
document.getElementById('info').innerHTML =
'PRINT mostra texto na tela.';
}

if(bloco==='move'){
document.getElementById('info').innerHTML =
'MOVE move um personagem.';
}

if(bloco==='repeat'){
document.getElementById('info').innerHTML =
'REPEAT repete ações.';
}

}
</script>

</body>
</html>

