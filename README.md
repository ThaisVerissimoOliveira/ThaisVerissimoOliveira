<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Thais Verissimo — README</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#9aa6b2;--accent:#7c3aed}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:linear-gradient(180deg,#071029 0%, #071a2a 60%); color:#e6eef6; padding:48px}
    .container{max-width:900px;margin:0 auto}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:14px;background:linear-gradient(135deg,var(--accent),#2563eb);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:white}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .card{background:rgba(255,255,255,0.03);padding:20px;border-radius:12px;margin-top:20px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    h2{margin-top:0}
    ul.badges{display:flex;gap:8px;flex-wrap:wrap;padding:0;list-style:none;margin:12px 0}
    .badge{padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.03);border:1px solid rgba(255,255,255,0.02);font-size:13px;color:var(--muted)}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
    pre{background:#021124;padding:12px;border-radius:8px;overflow:auto;color:#dbeafe}
    a{color:var(--accent);text-decoration:none}
    footer{margin-top:20px;color:var(--muted);font-size:13px}
    @media (max-width:720px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">TV</div>
      <div>
        <h1>Thais Verissimo</h1>
        <p class="lead">Estudante e desenvolvedora — C / C++ | Estruturas de Dados | SQL | UX/UI</p>
        <div style="margin-top:10px">
          <a href="#projects" class="badge">Projetos</a>
          <a href="#tech" class="badge">Tecnologias</a>
          <a href="#contact" class="badge">Contato</a>
        </div>
      </div>
    </header>

    <section class="card" id="about">
      <h2>Sobre mim</h2>
      <p>Sou estudante e desenvolvedora em formação. Trabalho com lógicas e estruturas de dados (listas encadeadas, árvores AVL e rubro-negras), manipulação de arquivos CSV em C++, consultas SQL complexas e também tenho experiência com prototipação e UX/UI.</p>
      <p>Sou organizada e gosto de documentar bem meus projetos — casos de uso, requisitos e diagramas fazem parte do meu fluxo. Também tenho um cachorro carinhoso que aparece em muitos commits (brincadeira 😄).</p>
    </section>

    <section class="card" id="tech">
      <h2>Tecnologias & Ferramentas</h2>
      <ul class="badges">
        <li class="badge">C</li>
        <li class="badge">C++</li>
        <li class="badge">SQL</li>
        <li class="badge">HTML & CSS</li>
        <li class="badge">Bootstrap</li>
        <li class="badge">Git & GitHub</li>
        <li class="badge">Figma</li>
      </ul>
    </section>

    <section class="card" id="projects">
      <h2>Projetos em destaque</h2>
      <div class="grid">
        <div>
          <h3>Gerenciamento de alunos (C++)</h3>
          <p>Leitura de CSV, inserção em lista duplamente encadeada, validação de CPF e matrícula duplicada, ordenação e buscas.</p>
        </div>
        <div>
          <h3>Árvores AVL & Rubro-Negra (C)</h3>
          <p>Implementação completa com inserção, remoção e balanceamentos — projeto acadêmico com documentação e apresentação.</p>
        </div>
        <div>
          <h3>Sistema de Agendamentos — Documentação</h3>
          <p>Documento de requisitos com casos de uso, diagramas de atividade e resumo para slides.</p>
        </div>
        <div>
          <h3>Protótipo UX/UI (Fortes Engenharia)</h3>
          <p>Protótipo de alta fidelidade focado em ações sociais — princípios de usabilidade e visual design.</p>
        </div>
      </div>
    </section>

    <section class="card" id="how-to-use">
      <h2>Como usar este HTML</h2>
      <ol>
        <li>Copie este arquivo e salve como <code>README.html</code> no seu computador.</li>
        <li>Para hospedar: coloque em um repositório e ative o GitHub Pages (Settings → Pages) ou abra localmente no navegador.</li>
        <li>Se quiser que apareça no perfil do GitHub, mantenha também um <code>README.md</code> (Markdown) — o GitHub não renderiza HTML puro como README do perfil.</li>
      </ol>
      <pre><code># Exemplo de commit
git add README.html
git commit -m "Adiciona README em HTML"
git push origin main
</code></pre>
    </section>

    <section class="card" id="contact">
      <h2>Contato</h2>
      <p>Adicione seus contatos abaixo para exibir — eu deixei como placeholders:</p>
      <ul>
        <li>Email: <a href="mailto:seu-email@exemplo.com">seu-email@exemplo.com</a></li>
        <li>LinkedIn: <a href="#">linkedin.com/in/seu-perfil</a></li>
      </ul>
      <p>Se preferir, informe aqui o que quer que eu coloque e eu atualizo para você.</p>
    </section>

    <footer>
      <p>Made with ❤️ — versão HTML do seu README. Se quiser, eu gero também a versão responsiva com imagens/badges extras.</p>
    </footer>
  </div>
</body>
</html>
