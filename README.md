<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>No Coin Subway Surfers</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🏆 No Coin Subway Surfers</h1>
    <p>Classements officiels No Coin</p>
</header>

<nav>
    <button onclick="showSection('world')">🌍 Monde</button>
    <button onclick="showSection('france')">🇫🇷 France</button>
    <button onclick="showSection('submit')">📤 Soumettre</button>
</nav>

<div id="world" class="section active">
<h2>🌍 Top Monde</h2>

<table>
<tr>
<th>#</th>
<th>Joueur</th>
<th>Temps</th>
</tr>

<tr><td>1 🥇</td><td>Bilel 🇫🇷</td><td>3h11m54s</td></tr>
<tr><td>2 🥈</td><td>Anatole 🇫🇷</td><td>2h49m45s</td></tr>
<tr><td>3 🥉</td><td>plznxz 🇧🇷</td><td>2h44m58s</td></tr>
<tr><td>4</td><td>Gv 🇧🇷</td><td>2h42m57s</td></tr>
<tr><td>5</td><td>Aquable 🇫🇷</td><td>2h25m15s</td></tr>
<tr><td>6</td><td>HgFinalBoss 🇧🇷</td><td>2h23m16s</td></tr>
<tr><td>7</td><td>Enzo 🇫🇷</td><td>2h13m28s</td></tr>
<tr><td>8</td><td>Dedudo 🇧🇷</td><td>2h12m32s</td></tr>
<tr><td>9</td><td>Blindado 🇧🇷</td><td>2h10m41s</td></tr>
<tr><td>10</td><td>Mzk 🇫🇷</td><td>2h08m32s</td></tr>
<tr><td>11</td><td>Floixxy 🇫🇷</td><td>1h59m04s</td></tr>
<tr><td>12</td><td>Blkzz 🇫🇷</td><td>1h51m18s</td></tr>
<tr><td>13</td><td>D-star 🇨🇳</td><td>1h51m00s</td></tr>
<tr><td>14</td><td>Piroxx 🇫🇷</td><td>1h45m04s</td></tr>
<tr><td>15</td><td>Floqerrr 🇫🇷</td><td>1h44m04s</td></tr>
<tr><td>16</td><td>Wasmo 🇫🇷</td><td>1h42m45s</td></tr>
<tr><td>17</td><td>B' 🇫🇷</td><td>1h38m20s</td></tr>
<tr><td>18</td><td>Tom 🇫🇷</td><td>1h36m00s</td></tr>
<tr><td>19</td><td>alexantj 🇧🇷</td><td>1h35m00s</td></tr>
<tr><td>20</td><td>zkeef 🇫🇷</td><td>1h28m12s</td></tr>

</table>
</div>

<div id="france" class="section">
<h2>🇫🇷 Top France</h2>

<table>
<tr>
<th>#</th>
<th>Joueur</th>
<th>Temps</th>
</tr>

<tr><td>1 🥇</td><td>Bilel</td><td>3h11m54s</td></tr>
<tr><td>2 🥈</td><td>Anatole</td><td>2h49m45s</td></tr>
<tr><td>3 🥉</td><td>Aquable</td><td>2h25m15s</td></tr>
<tr><td>4</td><td>Enzo</td><td>2h13m28s</td></tr>
<tr><td>5</td><td>Mzk</td><td>2h08m32s</td></tr>
<tr><td>6</td><td>Floixxy</td><td>1h59m04s</td></tr>
<tr><td>7</td><td>Blkzz</td><td>1h51m18s</td></tr>
<tr><td>8</td><td>Piroxx</td><td>1h45m04s</td></tr>
<tr><td>9</td><td>Floqerrr</td><td>1h44m03s</td></tr>
<tr><td>10</td><td>Wasmo</td><td>1h42m45s</td></tr>
<tr><td>11</td><td>B'</td><td>1h38m20s</td></tr>
<tr><td>12</td><td>Tom</td><td>1h34m12s</td></tr>
<tr><td>13</td><td>Zkeef</td><td>1h28m12s</td></tr>
<tr><td>14</td><td>Vatos</td><td>1h26m30s</td></tr>
<tr><td>15</td><td>Abdel</td><td>1h22m55s</td></tr>
<tr><td>16</td><td>Astra</td><td>1h20m38s</td></tr>
<tr><td>17</td><td>Liano</td><td>1h20m35s</td></tr>
<tr><td>18</td><td>Light</td><td>1h19m57s</td></tr>
<tr><td>19</td><td>sabitolv</td><td>1h19m52s</td></tr>
<tr><td>20</td><td>Leo.sh</td><td>1h19m09s</td></tr>

</table>
</div>

<div id="submit" class="section">
    <h2>📤 Soumettre un record</h2>

    <form>
        <input type="text" placeholder="Pseudo">
        <input type="text" placeholder="Pays">
        <input type="text" placeholder="Temps">
        <input type="url" placeholder="Lien vidéo">
        <button type="submit">Envoyer</button>
    </form>
</div>

<script>
function showSection(id){

document.querySelectorAll('.section').forEach(section=>{
section.classList.remove('active');
});

document.getElementById(id).classList.add('active');

}
</script>

</body>
</html>
