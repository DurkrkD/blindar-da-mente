<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blindar da Mente</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --gold: #C9A84C;
      --gold-light: #E8D08A;
      --dark: #0D0D12;
      --dark-2: #16161F;
      --dark-3: #1E1E2A;
      --border: rgba(201,168,76,0.25);
      --text: #F0EDE6;
      --muted: #9A9490;
    }

    body {
      min-height: 100vh;
      background: var(--dark);
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'DM Sans', sans-serif;
      padding: 2rem 1rem;
      position: relative;
      overflow-x: hidden;
    }

    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background:
        radial-gradient(ellipse 60% 50% at 50% 0%, rgba(201,168,76,0.07) 0%, transparent 70%),
        radial-gradient(ellipse 40% 30% at 80% 80%, rgba(201,168,76,0.04) 0%, transparent 60%);
      pointer-events: none;
    }

    .card {
      width: 100%;
      max-width: 480px;
      background: var(--dark-2);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 3rem 2.5rem;
      position: relative;
      animation: fadeUp 0.6s ease both;
    }

    .card::before {
      content: '';
      position: absolute;
      top: 0; left: 50%; transform: translateX(-50%);
      width: 60%; height: 1px;
      background: linear-gradient(90deg, transparent, var(--gold), transparent);
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--gold);
      border: 1px solid rgba(201,168,76,0.3);
      border-radius: 100px;
      padding: 4px 14px;
      margin-bottom: 1.25rem;
    }

    .badge::before {
      content: '';
      width: 5px; height: 5px;
      border-radius: 50%;
      background: var(--gold);
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      font-weight: 600;
      color: var(--text);
      line-height: 1.2;
      margin-bottom: 0.5rem;
    }

    h1 span {
      color: var(--gold);
    }

    .subtitle {
      font-size: 14px;
      color: var(--muted);
      line-height: 1.6;
      margin-bottom: 2rem;
    }

    .field {
      margin-bottom: 1.25rem;
    }

    label {
      display: block;
      font-size: 12px;
      font-weight: 500;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      color: var(--muted);
      margin-bottom: 8px;
    }

    input {
      width: 100%;
      background: var(--dark-3);
      border: 1px solid rgba(255,255,255,0.07);
      border-radius: 10px;
      padding: 13px 16px;
      font-family: 'DM Sans', sans-serif;
      font-size: 15px;
      font-weight: 300;
      color: var(--text);
      outline: none;
      transition: border-color 0.2s, box-shadow 0.2s;
    }

    input::placeholder { color: rgba(154,148,144,0.5); }

    input:focus {
      border-color: rgba(201,168,76,0.5);
      box-shadow: 0 0 0 3px rgba(201,168,76,0.08);
    }

    button {
      width: 100%;
      margin-top: 1.75rem;
      padding: 14px;
      border: none;
      border-radius: 10px;
      background: linear-gradient(135deg, #C9A84C 0%, #E8D08A 50%, #C9A84C 100%);
      background-size: 200% 200%;
      background-position: left;
      font-family: 'DM Sans', sans-serif;
      font-size: 15px;
      font-weight: 500;
      color: #0D0D12;
      cursor: pointer;
      transition: background-position 0.4s, transform 0.15s;
      letter-spacing: 0.01em;
    }

    button:hover {
      background-position: right;
      transform: translateY(-1px);
    }

    button:active { transform: translateY(0); }

    .divider {
      height: 1px;
      background: var(--border);
      margin: 2rem 0;
    }

    .result {
      display: none;
      text-align: center;
      animation: fadeUp 0.5s ease both;
    }

    .result.show { display: block; }

    .result-icon {
      width: 52px; height: 52px;
      border-radius: 50%;
      background: rgba(201,168,76,0.12);
      border: 1px solid rgba(201,168,76,0.3);
      display: flex; align-items: center; justify-content: center;
      margin: 0 auto 1.25rem;
      font-size: 22px;
    }

    .result h2 {
      font-family: 'Playfair Display', serif;
      font-size: 1.35rem;
      color: var(--text);
      margin-bottom: 0.5rem;
    }

    .result p {
      font-size: 14px;
      color: var(--muted);
      margin-bottom: 1.5rem;
      line-height: 1.6;
    }

    .link-box {
      background: var(--dark-3);
      border: 1px solid rgba(201,168,76,0.3);
      border-radius: 12px;
      padding: 1rem 1.25rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
    }

    .link-box a {
      color: var(--gold);
      font-size: 14px;
      font-weight: 500;
      text-decoration: none;
      word-break: break-all;
      transition: color 0.2s;
    }

    .link-box a:hover { color: var(--gold-light); }

    .copy-btn {
      flex-shrink: 0;
      width: 34px; height: 34px;
      border-radius: 8px;
      background: rgba(201,168,76,0.1);
      border: 1px solid rgba(201,168,76,0.25);
      color: var(--gold);
      font-size: 15px;
      cursor: pointer;
      display: flex; align-items: center; justify-content: center;
      transition: background 0.2s;
      margin: 0;
      padding: 0;
      width: auto;
      padding: 0 10px;
      font-size: 12px;
      font-family: 'DM Sans', sans-serif;
    }

    .copy-btn:hover { background: rgba(201,168,76,0.2); transform: none; }

    .privacy {
      font-size: 12px;
      color: rgba(154,148,144,0.6);
      text-align: center;
      margin-top: 1.5rem;
      line-height: 1.5;
    }

    .privacy span { color: rgba(201,168,76,0.7); }
  </style>
</head>
<body>

<div class="card">
  <div class="badge">Acesso exclusivo</div>
  <h1>Blindar a<br><span>Sua Mente</span></h1>
  <p class="subtitle">Preencha seus dados abaixo e receba acesso imediato ao conteúdo.</p>

  <div id="form-section">
    <div class="field">
      <label for="nome">Nome completo</label>
      <input type="text" id="nome" placeholder="Como você se chama?" autocomplete="name" />
    </div>
    <div class="field">
      <label for="email">E-mail</label>
      <input type="email" id="email" placeholder="seu@email.com" autocomplete="email" />
    </div>
    <div class="field">
      <label for="whatsapp">WhatsApp / Telefone</label>
      <input type="tel" id="whatsapp" placeholder="(00) 00000-0000" autocomplete="tel" />
    </div>

    <button onclick="handleSubmit()">Quero meu acesso →</button>

    <p class="privacy">🔒 Seus dados estão <span>protegidos</span>. Sem spam, prometemos.</p>
  </div>

  <div class="divider" id="divider" style="display:none;"></div>

  <div class="result" id="result-section">
    <div class="result-icon">✦</div>
    <h2 id="welcome-msg">Pronto, !</h2>
    <p>Aqui está o seu link de acesso exclusivo ao Blindar da Mente:</p>
    <div class="link-box">
      <a href="http://bit.ly/rodablindar" target="_blank" id="site-link">http://bit.ly/rodablindar</a>
      <button class="copy-btn" onclick="copyLink()">Copiar</button>
    </div>
    <p class="privacy" style="margin-top:1rem;">Clique no link acima para acessar o conteúdo 🚀</p>
  </div>
</div>

<script>
  const LINK = "http://bit.ly/rodablindar";

  function handleSubmit() {
    const nome = document.getElementById('nome').value.trim();
    const email = document.getElementById('email').value.trim();
    const whatsapp = document.getElementById('whatsapp').value.trim();

    if (!nome || !email || !whatsapp) {
      alert('Por favor, preencha todos os campos.');
      return;
    }

    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!emailRegex.test(email)) {
      alert('Por favor, insira um e-mail válido.');
      return;
    }

    document.getElementById('form-section').style.display = 'none';
    document.getElementById('divider').style.display = 'none';

    const firstName = nome.split(' ')[0];
    document.getElementById('welcome-msg').textContent = `Pronto, ${firstName}! 🎉`;
    document.getElementById('site-link').href = LINK;
    document.getElementById('site-link').textContent = LINK;

    document.getElementById('result-section').classList.add('show');
  }

  function copyLink() {
    navigator.clipboard.writeText(LINK).then(() => {
      const btn = document.querySelector('.copy-btn');
      btn.textContent = 'Copiado ✓';
      setTimeout(() => btn.textContent = 'Copiar', 2000);
    });
  }

  document.getElementById('whatsapp').addEventListener('input', function () {
    let v = this.value.replace(/\D/g, '').slice(0, 11);
    if (v.length > 2) v = '(' + v.slice(0,2) + ') ' + v.slice(2);
    if (v.length > 10) v = v.slice(0,10) + '-' + v.slice(10);
    this.value = v;
  });
</script>
</body>
</html>
