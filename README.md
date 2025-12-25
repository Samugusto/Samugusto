
<html lang="pt-BR" style="--bg-overlay: rgba(10,12,20,0.45); --bg-image: url(&quot;https://i.pinimg.com/1200x/8e/5a/8c/8e5a8c0f73ba8aab34908cebc0483681.jpg&quot;);"><head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Samuca</title>
  <link rel="shortcut icon" href="https://i.pinimg.com/736x/f5/eb/3e/f5eb3ef00e367e8385f2d1bc1e6234df.jpg">


  <style>
       :root{
      --accent:#ffffff;
      --muted:#aaa;
      --card-bg:rgba(255,255,255,0.06);
      --glass:rgba(255,255,255,0.06);
      --radius:10px;
      --bg-image:url('https://i.pinimg.com/1200x/8e/5a/8c/8e5a8c0f73ba8aab34908cebc0483681.jpg');
      --bg-overlay:rgba(10,12,20,0.45);
      --max-width:1100px;
    }

    *{box-sizing:border-box;margin:0;padding:0}
    html,body{height:100%}
    body{
      font-family: "Poppins", system-ui, sans-serif;
      background-image:linear-gradient(var(--bg-overlay), var(--bg-overlay)), var(--bg-image);
      background-size:cover;background-position:center;
      color:#e6eef8;
      padding:40px 20px;
      display:flex;align-items:center;justify-content:center;
      overflow-x:hidden;
      transition: background-image 1s ease, background-color 0.5s ease;
    }

    .wrap{width:100%;max-width:var(--max-width);animation:fadeIn 1s ease;}

    @keyframes fadeIn {
      from {opacity:0; transform:translateY(30px);}
      to {opacity:1; transform:translateY(0);}
    }

    .card{
      backdrop-filter:blur(10px) saturate(140%);
      background:linear-gradient(180deg, rgba(255,255,255,0.04), rgba(255,255,255,0.02));
      border-radius:16px;
      padding:30px;
      box-shadow:0 8px 30px rgba(2,6,23,0.6);
      transition:transform 0.3s ease;
    }
    .card:hover{transform:scale(1.01);}

    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:20px;}

    .profile{display:flex;align-items:center;gap:18px;}
    .avatar{
      width:90px;height:90px;border-radius:50%;overflow:hidden;
      border:3px solid rgba(255,255,255,0.1);
      transition:transform 0.3s ease, border-color 0.4s;
    }
    .avatar:hover{transform:rotate(0deg) scale(1.2);border-color:var(--accent);}
    .avatar img{width:100%;height:100%;object-fit:cover;}

    .profile h1{font-size:22px;font-weight:700;}
    .profile p{color:var(--muted);font-size:14px;}

    nav{display:flex;gap:12px;}
    .tab{
      background:transparent;border:0;padding:8px 14px;border-radius:12px;
      color:inherit;cursor:pointer;font-weight:600;
      transition:all .3s ease;position:relative;overflow:hidden;
    }
    .tab::before{
      content:'';position:absolute;bottom:0;left:0;width:0;height:2px;background:var(--accent);
      transition:width .3s ease;
    }
    .tab:hover::before{width:100%;}
    .tab[aria-current="true"]{
      background:linear-gradient(90deg,var(--accent),#c9c0c0);
      color:#000;box-shadow:0 0 10px rgba(255,255,255,0.4);
    }

    .content{display:grid;gap:18px;margin-top:10px;}

    .card-item{
      background:var(--card-bg);
      padding:20px;border-radius:var(--radius);
      display:flex;flex-direction:column;gap:10px;
      border:1px solid rgba(255,255,255,0.05);
      transition:transform .3s ease, box-shadow .3s ease;
    }
    .card-item:hover{transform:translateY(-5px);box-shadow:0 5px 20px rgba(255,255,255,0.1);}

    .about{display:flex;flex-direction:column;gap:12px;font-size:15px;color:#e7eefc;margin:10px;}
    .about p strong{color:#fff;}

    .jogo-item img, .musica-item img{
      border-radius:10px;transition:transform 0.3s ease;
    }
    .jogo-item img:hover, .musica-item img:hover{
      transform:scale(1.1);
    }

    .musica-item {
      display:flex;align-items:center;gap:15px;
      background:rgba(255,255,255,0.07);
      padding:10px;border-radius:8px;
      border:1px solid rgba(255,255,255,0.1);
    }
    .musica-item strong{font-size:14px;}

    footer{margin-top:20px;text-align:center;color:#888;font-size:13px;opacity:0.8;}

    .hidden{display:none}
    .fade{transition:opacity .4s ease;}

    /* pequenas animações */
    .sparkle {
      position:absolute;
      width:5px;height:5px;
      background:white;border-radius:50%;
      pointer-events:none;
      opacity:0.8;
      animation: sparkle 1s linear forwards;
    }
    @keyframes sparkle {
      from{transform:scale(1) translateY(0);opacity:1;}
      to{transform:scale(0) translateY(-30px);opacity:0;}
    }
    .imagem2 img{
      border-radius:10px;transition:transform 0.3s ease;
    }
    .imagem2 img:hover{
      transform:scale(1.1);
    }
    .redes img{
      border-radius:10px;transition:transform 0.8s ease;
    }
    .redes img:hover{
      transform:scale(1.1);
    }
    .voltar-btn {background: rgba(255, 255, 255, 0.158);border: 1px solid rgba(255, 255, 255, 0.2);color: #e6eef8;padding: 6px 12px;border-radius: 6px;font-size: 12px;cursor: pointer;margin-top: 10px;align-self: 300px; text-align:center; transition: background 0.2s ease;}.voltar-btn:hover {background: rgba(255, 255, 255, 0.2);} 
    .about{display:flex;flex-direction:column;gap:10px;font-size:15px;color:#e7eefc;margin:10px;}
    .tab2{background:transparent;border:0;padding:8px 12px;border-radius:10px;color:inherit;cursor:pointer;font-weight:600;}.tab2[aria-current="true"]{background:linear-gradient(90deg,var(--accent),#c9c0c0);color:#000000}
  </style>
<style type="text/css" id="operaUserStyle"></style></head>
<body>
  <div class="wrap">
    <div class="card">
      <header>
        <div class="profile">
          <div class="avatar" title="Créditos á Lana_Belem">
            <a href="https://www.tiktok.com/@lana_belem" target="_blank">
            <img src="https://i.imgur.com/wtxFeOj.gif" alt="Minha foto de perfil"></a>
          </div>
          <div class="name">
            <h1>Sam</h1>
            <p>Estudante • Tô aí :)</p>
          </div>
        </div>

        <nav role="tablist" aria-label="Navegação do portfolio">
          <button class="tab" role="tab" data-target="portfolio" aria-current="true">Menu</button>
          <button class="tab" role="tab" data-target="sobremim">Sobre mim</button>
          <button class="tab" role="tab" data-target="sobremim2">Interesses</button>
          <button class="tab" role="tab" data-target="contact">Contato</button>
          <button class="tab hidden" id="secret-tab" role="tab" data-target="secret">???</button>
        </nav>
      </header>

      <main class="content">
        <section id="secret" class="fade hidden" style="opacity: 0;">
  <div class="about">
    <p>Parabéns! Você encontrou o segredo secreto. Aqui está uma surpresa especial: uma imagem aleatória de gatinho porque por que não? 😺</p>
    <img src="https://placekitten.com/300/200" alt="Surpresa secreta" width="300" height="200">
  </div>
</section>
        <section id="portfolio" class="fade" style="opacity: 1;">
          <div class="grid">
            <article class="card-item">
              <h3>Opá Bem-vindo(a)</h3>
              <img src="https://www.demirramon.com/gen/undertale_text_box.gif?text=fique%20a%20vontade%20a%20ver%20mais%20sobremim%20e%20meus%20interesses&amp;box=deltarune&amp;character=deltarune-ralsei&amp;expression=happy&amp;size=2&amp;t=1758672129" width="700" height="200">
          </article></div>
        </section>

        <section id="sobremim" class="fade hidden" style="opacity: 0;">
          <div class="about">

            <p>Opa! sou <strong>Samuel</strong>, estudo e mexo um pouco com HTML, CSS e PYTHON!, gosto de jogar, ouvir músicas e adoro fazer exercicios físicos um deles sendo academia. aliás tenho 17 anos</p>
            <p>Habilidades: HTML, CSS, PY, criatividade, fé e persistência.</p>
            <p>Interesses: design, jogos, computador, música, programação</p>
          </div>
        </section>

        <!-- Nova aba Interesses -->
        <section id="sobremim2" class="fade hidden" style="opacity: 0;">
          <div class="about">
            <div id="interesses-main">
              <p>aqui vou mostrar meus interesses (tem mais mas to com preguiça de programar para ficar bonito):</p>
              <div class="jogo-item">
              <p><img src="https://i.gifer.com/origin/86/860f84d479e12dbf65659ef0fcdd3596_w200.gif" width="100" height="100" style="vertical-align: middle;" class="imagem"><strong>Dying Light</strong>
              <img src="https://media.tenor.com/j6piu5bth90AAAAM/death-stranding-sam-bridges.gif" width="100" height="100" style="vertical-align: middle;" class="imagem1"><strong>Death Strading</strong>
              <img src="https://cdna.artstation.com/p/assets/images/images/026/415/402/original/moutaz-k-maudy-combined.gif?1588715248" width="100" height="100" style="vertical-align: middle;" class="imagem2"><strong>Hollow Knight</strong>
              <img src="https://media.tenor.com/bBz_-8o1LgIAAAAM/arthur-morgan-red-dead-redemption2.gif" width="100" height="100" style="vertical-align: middle;" class="imagem3"><strong>Red Dead Redemption 2</strong><br>
              <img src="https://i.pinimg.com/originals/d7/0e/fa/d70efaad1c3e772a00b2a92d033b1031.gif" width="100" height="100" style="vertical-align: middle;" class="imagem4"><strong>Cyberpunk</strong>
              <img src="https://i.pinimg.com/originals/cc/13/2f/cc132fe3152ce74fcbe00980c5300b9a.gif" width="100" height="100" style="vertical-align: middle;" class="imagem5"><strong>Deltarune</strong>
              <img src="https://preview.redd.it/days-gone-gifs-v0-1cjkc5hb15ve1.gif?width=540&amp;auto=webp&amp;s=817857bc6915164f8ce4e3c04f05a025ac47277b" width="100" height="100" style="vertical-align: middle;" class="imagem6"><strong>Days Gone</strong>
              <img src="https://media.tenor.com/urjuz7BmW3wAAAAM/dedsec.gif" width="100" height="100" style="vertical-align: middle;" class="imagem7"><strong>Watch Dogs</strong></p>
              </div>
            </div>
            <button class="tab2" id="btn-mais" role="tab2">Mais..</button>
            <section id="musicas" class="hidden fade" style="opacity: 0;">
              <div class="about">
                <p>Aqui estão algumas músicas que eu gosto! (Você pode editar esta lista adicionando mais itens ou links para Spotify/YouTube.)</p>
                <div class="musicas-list">
                  <div class="musica-item">
                    <a href="https://open.spotify.com/intl-pt/track/0NjW4SKY3gbfl2orl1p8hr" target="_blank">
                    <img src="https://cdn-images.dzcdn.net/images/cover/243cc17e7688cb2f9739120ae4eb9912/1900x1900-000000-80-0-0.jpg" width="100" height="100"></a><strong>IFHY - Tyler, The Creator </strong><a href="https://open.spotify.com/intl-pt/track/0NjW4SKY3gbfl2orl1p8hr" target="_blank">(Ouvir no Spotify)</a>
                    <a href="https://open.spotify.com/intl-pt/track/3SPfACAarZmNEF45erapCY?si=b9dbf8d567474ff9" target="_blank">
                      <img src="https://i.scdn.co/image/ab67616d0000b2733138f891f3075c9c5d944037" width="100" height="100"></a><strong> Neu Roses (Transgressor's Song) - Daniel</strong><a href="https://open.spotify.com/intl-pt/track/3SPfACAarZmNEF45erapCY?si=b9dbf8d567474ff9" target="_blank">(Ouvir no Spotify)</a>
                  </div>
                  <div class="musica-item">
                    <a href="https://open.spotify.com/intl-pt/track/7KO4XNfwEKhTbSGo3O6qX5?si=fada673fce90401f" target="_blank">
                    <img src="https://i.scdn.co/image/ab67616d0000b273280a001e43c93792dd1e27c7" width="100" height="100"></a><strong>If You Know What's Right - her's</strong><a href="https://open.spotify.com/intl-pt/track/3xqWiKFFYF9Pv7H1nNoZFd" target="_blank">(Ouvir no Spotify)</a>
                    <a href="https://open.spotify.com/intl-pt/track/7tlbZCr7a3BLXCSlwvWMCA?si=1a28d3a2bdd64d22" target="_blank">
                    <img src="https://m.media-amazon.com/images/I/41xXzav9sWL._UXNaN_FMjpg_QL85_.jpg" width="100" height="100"></a><strong>The Love i Lost - Flouride</strong><a href="https://open.spotify.com/intl-pt/track/7tlbZCr7a3BLXCSlwvWMCA?si=1a28d3a2bdd64d22" target="_blank">(Ouvir no Spotify)</a>
                  </div>
                  <div class="musica-item">
                    <a href="https://open.spotify.com/intl-pt/track/2aaCNg42RA74s0EmHTBqS7" target="_blank">
                    <img src="https://i.scdn.co/image/ab67616d0000b273b395acedffa5fa8e7696aea2" width="100" height="100"></a><strong>No Other Heart - Mac Demarco</strong><a href="https://open.spotify.com/intl-pt/track/2aaCNg42RA74s0EmHTBqS7" target="_blank">(Ouvir no Spotify)</a>
                    <a href="https://open.spotify.com/intl-pt/track/4KGGeE7RJsgLNZmnxGFlOj?si=649fd9a3a0964104" target="_blank">
                    <img src="https://i.scdn.co/image/ab67616d0000b2739ef071aa762f75842e0eb15f" width="100" height="100"></a><strong>Falling Behind - Laufey </strong><a href="https://open.spotify.com/intl-pt/track/4KGGeE7RJsgLNZmnxGFlOj?si=649fd9a3a0964104" target="_blank">(Ouvir no Spotify)</a>
                  </div>
                  <a href="https://www.tiktok.com/@really_username" target="_blank">
                  <div class="imagem2">
                  <img src="https://i.imgur.com/9H9clNW.gif" width="150" height="140" style="border-radius: 6px; margin-top: 30px; margin-left: 390px;">
                  </div>
                  </a>
                  <p style="margin-left: 330px;">queria adicionar mais 
                    mas não cabe..</p>
                  <!-- Adicione mais itens aqui conforme necessário -->
                </div>
                <button class="voltar-btn" id="btn-voltar">Voltar</button>
              </div>
            </section>
          </div>

        </section>

        <section id="contact" class="fade hidden" style="opacity: 0;">
          <div style="display:flex;flex-direction:column;gap:10px;">
            <p style="color:var(--muted)">acho que você já tem uma das minhas redes sociais que é o <strong>Discord</strong></p>
            <div class="redes">
            <p style="color:var(--muted)"><a href="https://steamcommunity.com/profiles/76561199001302778/" target="_blank"><img src="https://cdn.freebiesupply.com/images/large/2x/steam-logo-black-transparent.png" width="30" height="30" style="margin-right: 20px;"></a><a href="https://github.com/Samugusto" target="_blank"><img src="https://cdn.freebiesupply.com/logos/large/2x/github-icon-1-logo-black-and-white.png" height="30" width="30" style="margin-right: 20px;"></a><a href="https://www.tiktok.com/@samusouca" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Tiktok_icon.svg/1024px-Tiktok_icon.svg.png" width="30" height="30"></a></p>
            </div>
          </div>
        </section>
      </main>

      <footer>
        feito a mão e uma ajudinha de IA...
      </footer>
    </div>
  </div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const btnMais = document.getElementById('btn-mais');
  const btnVoltar = document.getElementById('btn-voltar');
  const interessesMain = document.getElementById('interesses-main');
  const musicasSection = document.getElementById('musicas');

  // valores de fundo (troque as URLs se quiser)
  const originalOverlay = 'rgba(10,12,20,0.45)';
  const originalBg = 'url("https://i.pinimg.com/1200x/8e/5a/8c/8e5a8c0f73ba8aab34908cebc0483681.jpg")';
  const musicOverlay = 'rgba(10,12,20,0.45)';
  const musicBg = 'url("https://static.wikia.nocookie.net/enajoelg/images/e/e3/OverworldTemptationStairway.png/revision/latest?cb=20210521174752")';

  function closeMusicAndRestoreBg() {
    if (musicasSection && !musicasSection.classList.contains('hidden')) {
      musicasSection.classList.add('hidden');
      musicasSection.style.opacity = 0;
    }
    if (interessesMain) interessesMain.classList.remove('hidden');
    if (btnMais) btnMais.classList.remove('hidden');

    document.documentElement.style.setProperty('--bg-overlay', originalOverlay);
    document.documentElement.style.setProperty('--bg-image', originalBg);
  }

  // handler das abas — agora fecha a seção de músicas ao trocar de aba
  document.querySelectorAll('.tab').forEach(btn=>{
    btn.addEventListener('click', e=>{
      const target = btn.dataset.target;

      // fecha músicas e restaura bg antes de trocar de aba
      closeMusicAndRestoreBg();

      document.querySelectorAll('.tab').forEach(t=>t.removeAttribute('aria-current'));
      btn.setAttribute('aria-current','true');
      ['portfolio','sobremim','sobremim2','contact'].forEach(id=>{
        const el = document.getElementById(id);
        if(!el) return;
        if(id===target){ el.classList.remove('hidden'); el.style.opacity=1 }
        else { el.classList.add('hidden'); el.style.opacity=0 }
      });
    });
  });

  // botão "Mais.." (abre seção músicas e altera bg)
  if (btnMais) {
    btnMais.addEventListener('click', function() {
      interessesMain.classList.add('hidden');
      btnMais.classList.add('hidden');

      document.documentElement.style.setProperty('--bg-overlay', musicOverlay);
      document.documentElement.style.setProperty('--bg-image', musicBg);

      musicasSection.classList.remove('hidden');
      musicasSection.style.opacity = 1;
    });
  }

  // botão "Voltar" usa a mesma função de fechamento
  if (btnVoltar) {
    btnVoltar.addEventListener('click', function() {
      closeMusicAndRestoreBg();
    });
  }
});
// Adicione isso no início do script, após const btnMais, etc.
const visitedTabs = new Set();  // Conjunto para rastrear abas visitadas
const mainTabs = ['portfolio', 'sobremim', 'sobremim2', 'contact'];  // Lista das abas principais
const secretTabButton = document.getElementById('secret-tab');
const secretSection = document.getElementById('secret');

// Modifique o evento de clique das tabs para rastrear visitas
document.querySelectorAll('.tab').forEach(btn => {
  btn.addEventListener('click', e => {
    const target = btn.dataset.target;
    
    if (mainTabs.includes(target)) {
      visitedTabs.add(target);  // Adiciona a aba visitada ao conjunto
      checkAllTabsVisited();  // Verifica se todas foram visitadas
    }
    
    // O resto do seu código original aqui (fecha músicas, etc.)
    const originalOverlay = 'rgba(10,12,20,0.45)';
    const originalBg = 'url("https://i.pinimg.com/1200x/8e/5a/8c/8e5a8c0f73ba8aab34908cebc0483681.jpg")';
    
    function closeMusicAndRestoreBg() {
      // Seu código original para fechar músicas
    }
    
    closeMusicAndRestoreBg();
    
    document.querySelectorAll('.tab').forEach(t => t.removeAttribute('aria-current'));
    btn.setAttribute('aria-current', 'true');
    ['portfolio', 'sobremim', 'sobremim2', 'contact', 'secret'].forEach(id => {  // Inclui 'secret' agora
      const el = document.getElementById(id);
      if (el) {
        if (id === target) {
          el.classList.remove('hidden');
          el.style.opacity = 1;
        } else {
          el.classList.add('hidden');
          el.style.opacity = 0;
        }
      }
    });
  });
});

// Função para verificar se todas as abas principais foram visitadas
function checkAllTabsVisited() {
  if (visitedTabs.size === mainTabs.length) {
    // Todas as abas foram visitadas, desoculta a aba secreta
    if (secretTabButton) secretTabButton.classList.remove('hidden');
    // Opcional: Você pode adicionar uma notificação ou animação aqui
  }
}
</script>


</body></html>
