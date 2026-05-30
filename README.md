[atlas_digital_landing_page_v2.html](https://github.com/user-attachments/files/28414654/atlas_digital_landing_page_v2.html)

<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  .lp { max-width: 900px; margin: 0 auto; padding: 0 1rem; font-family: var(--font-sans); color: var(--color-text-primary); }
  .btn-primary {
    background: #185FA5; color: #fff; border: none;
    padding: 14px 32px; border-radius: var(--border-radius-md);
    font-size: 15px; font-weight: 500; cursor: pointer;
    display: inline-block; text-decoration: none; transition: background 0.2s;
  }
  .btn-primary:hover { background: #0C447C; }
  .btn-outline {
    background: transparent; color: #185FA5; border: 1.5px solid #185FA5;
    padding: 12px 28px; border-radius: var(--border-radius-md);
    font-size: 15px; font-weight: 500; cursor: pointer;
    display: inline-block; text-decoration: none; transition: all 0.2s;
  }
  .btn-outline:hover { background: #E6F1FB; }
  section { padding: 3rem 0; }
  .badge { background: #E6F1FB; color: #0C447C; font-size: 12px; font-weight: 500; padding: 4px 12px; border-radius: 99px; display: inline-block; margin-bottom: 1rem; letter-spacing: 0.04em; }
  h1 { font-size: clamp(28px, 5vw, 42px); font-weight: 500; line-height: 1.2; }
  h2 { font-size: clamp(22px, 3.5vw, 30px); font-weight: 500; }
  h3 { font-size: 18px; font-weight: 500; }
  p { font-size: 15px; line-height: 1.7; color: var(--color-text-secondary); }
  .card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1.5rem; }
  .grid-3 { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.25rem; }
  .grid-2 { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.25rem; }
  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 0; }
  .icon-circle { width: 44px; height: 44px; border-radius: 50%; background: #E6F1FB; display: flex; align-items: center; justify-content: center; margin-bottom: 1rem; flex-shrink: 0; }
  .icon-circle i { font-size: 20px; color: #185FA5; }
  .plan-popular { border: 2px solid #185FA5; position: relative; }
  .plan-price { font-size: 32px; font-weight: 500; color: var(--color-text-primary); }
  .plan-price span { font-size: 15px; color: var(--color-text-secondary); }
  .check-list { list-style: none; padding: 0; margin: 1rem 0; }
  .check-list li { display: flex; align-items: flex-start; gap: 8px; font-size: 14px; color: var(--color-text-secondary); padding: 5px 0; }
  .check-list li i { color: #1D9E75; font-size: 16px; margin-top: 2px; flex-shrink: 0; }
  .nav { display: flex; align-items: center; justify-content: space-between; padding: 1.25rem 0; }
  .hero-sub { font-size: 17px; margin: 1.25rem 0 2rem; color: var(--color-text-secondary); max-width: 520px; }
  .hero-btns { display: flex; flex-wrap: wrap; gap: 12px; }
  .stat-row { display: flex; flex-wrap: wrap; gap: 2rem; margin-top: 2.5rem; padding-top: 2rem; border-top: 0.5px solid var(--color-border-tertiary); }
  .stat-num { font-size: 24px; font-weight: 500; color: #185FA5; }
  .stat-label { font-size: 13px; color: var(--color-text-secondary); }
  .section-header { margin-bottom: 2.5rem; }
  .section-header p { max-width: 520px; margin-top: 0.5rem; }
  .cta-box { background: #0C447C; border-radius: var(--border-radius-lg); padding: 3rem 2rem; text-align: center; }
  .cta-box h2 { color: #E6F1FB; }
  .cta-box p { color: #85B7EB; margin: 1rem auto; max-width: 480px; }
  .contact-btn {
    display: inline-flex; align-items: center; gap: 8px;
    padding: 13px 24px; border-radius: var(--border-radius-md);
    font-size: 15px; font-weight: 500; text-decoration: none;
    transition: all 0.2s; border: none; cursor: pointer;
  }
  .contact-btn i { font-size: 18px; }
  .btn-whatsapp { background: #25D366; color: #fff; }
  .btn-whatsapp:hover { background: #1da851; }
  .btn-email { background: #fff; color: #0C447C; }
  .btn-email:hover { background: #E6F1FB; }
  .btn-instagram { background: transparent; color: #B5D4F4; border: 1.5px solid #378ADD; }
  .btn-instagram:hover { background: #0C447C; }
  .footer { padding: 2rem 0; display: flex; flex-wrap: wrap; gap: 1rem; align-items: center; justify-content: space-between; }
  .footer-copy { font-size: 13px; color: var(--color-text-secondary); }
  .footer-links { display: flex; gap: 1.25rem; }
  .footer-links a { font-size: 13px; color: var(--color-text-secondary); text-decoration: none; }
  .footer-links a:hover { color: #185FA5; }
  .monthly-card { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 2rem; display: flex; flex-wrap: wrap; gap: 1.5rem; align-items: center; }
  .monthly-badge { background: #E1F5EE; color: #0F6E56; font-size: 12px; font-weight: 500; padding: 4px 12px; border-radius: 99px; display: inline-block; margin-bottom: 0.5rem; }
  .logo-img { height: 48px; width: auto; object-fit: contain; }
</style>

<h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">Landing page da Atlas Digital — criação de sites profissionais</h2>

<div class="lp">

  <nav class="nav">
    <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAgGBgcGBQgHBwcJCQgKDBQNDAsLDBkSEw8UHRofHh0aHBwgJC4nICIsIxwcKDcpLDAxNDQ0Hyc5PTgyPC4zNDL/2wBDAQkJCQwLDBgNDRgyIRwhMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjIyMjL/wAARCAEsASwDASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD5/ooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigD/9k=" 
         alt="Atlas Digital logo" class="logo-img"
         onerror="this.style.display='none';document.getElementById('logo-text').style.display='flex'">
    <span id="logo-text" style="display:none;align-items:center;gap:8px;font-size:20px;font-weight:500;color:var(--color-text-primary);">
      <i class="ti ti-globe" style="color:#185FA5;font-size:24px;" aria-hidden="true"></i>Atlas Digital
    </span>
    <a class="btn-primary" href="https://wa.me/5588994342633" target="_blank" style="padding:10px 20px;font-size:14px;">Solicitar orçamento</a>
  </nav>

  <hr class="divider">

  <section>
    <span class="badge"><i class="ti ti-sparkles" style="font-size:12px;vertical-align:-1px;margin-right:4px" aria-hidden="true"></i>Criação de sites profissionais</span>
    <h1>Seu negócio merece<br>uma presença digital<br><span style="color:#185FA5;">de alto nível</span></h1>
    <p class="hero-sub">Da ideia ao ar: desenvolvemos sites personalizados para empresas e empreendedores que querem crescer online. Planos acessíveis, resultados profissionais.</p>
    <div class="hero-btns">
      <a class="btn-primary" href="#planos" onclick="document.getElementById('planos').scrollIntoView({behavior:'smooth'});return false;">Ver planos e preços</a>
      <a class="btn-outline" href="#como-funciona" onclick="document.getElementById('como-funciona').scrollIntoView({behavior:'smooth'});return false;">Como funciona</a>
    </div>
    <div class="stat-row">
      <div>
        <div class="stat-num">100%</div>
        <div class="stat-label">Responsivo (mobile + desktop)</div>
      </div>
      <div>
        <div class="stat-num" style="font-size:18px;">A partir de R$ 250</div>
        <div class="stat-label">Plano de entrada</div>
      </div>
      <div>
        <div class="stat-num">R$ 30/mês</div>
        <div class="stat-label">Suporte e manutenção</div>
      </div>
    </div>
  </section>

  <hr class="divider">

  <section id="como-funciona">
    <div class="section-header">
      <span class="badge">Processo simples</span>
      <h2>Como funciona</h2>
      <p>Do briefing à entrega, um processo claro e sem complicação.</p>
    </div>
    <div class="grid-3">
      <div class="card">
        <div class="icon-circle"><i class="ti ti-messages" aria-hidden="true"></i></div>
        <h3>1. Briefing</h3>
        <p style="margin-top:8px;">Você nos conta sobre seu negócio, objetivos e referências. Entendemos tudo que você precisa.</p>
      </div>
      <div class="card">
        <div class="icon-circle"><i class="ti ti-layout" aria-hidden="true"></i></div>
        <h3>2. Desenvolvimento</h3>
        <p style="margin-top:8px;">Criamos o seu site com design profissional, adaptado para celular e computador, com foco na sua identidade.</p>
      </div>
      <div class="card">
        <div class="icon-circle"><i class="ti ti-rocket" aria-hidden="true"></i></div>
        <h3>3. Entrega e suporte</h3>
        <p style="margin-top:8px;">Seu site vai ao ar. Você pode contar com nosso plano mensal para ajustes, atualizações e melhorias contínuas.</p>
      </div>
    </div>
  </section>

  <hr class="divider">

  <section id="planos">
    <div class="section-header">
      <span class="badge">Planos e preços</span>
      <h2>Escolha o plano ideal</h2>
      <p>Preços transparentes. O valor final varia conforme o número e a complexidade das páginas.</p>
    </div>
    <div class="grid-2">
      <div class="card">
        <div class="badge" style="background:#EAF3DE;color:#3B6D11;">Entrada</div>
        <h3 style="margin-bottom:4px;">Site Essencial</h3>
        <p style="font-size:13px;">Ideal para quem está começando online</p>
        <div class="plan-price" style="margin:1rem 0;">R$ 250 <span>/ único</span></div>
        <ul class="check-list">
          <li><i class="ti ti-check" aria-hidden="true"></i>Site de 1 a 2 páginas</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Design responsivo (mobile + web)</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Conteúdo fornecido pelo cliente</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Hospedagem incluída (sem domínio próprio)</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Entrega rápida</li>
        </ul>
        <a class="btn-outline" href="https://wa.me/5588994342633" target="_blank" style="width:100%;text-align:center;display:block;">Solicitar</a>
      </div>
      <div class="card plan-popular">
        <span style="position:absolute;top:-13px;left:50%;transform:translateX(-50%);background:#185FA5;color:#fff;font-size:12px;font-weight:500;padding:4px 14px;border-radius:99px;white-space:nowrap;">Mais popular</span>
        <div class="badge" style="margin-top:8px;">Personalizado</div>
        <h3 style="margin-bottom:4px;">Site Completo</h3>
        <p style="font-size:13px;">Para negócios que precisam de mais páginas</p>
        <div class="plan-price" style="margin:1rem 0;">Sob consulta</div>
        <ul class="check-list">
          <li><i class="ti ti-check" aria-hidden="true"></i>Múltiplas páginas (portfólio, blog, loja, etc.)</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Design exclusivo e personalizado</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Responsivo (mobile + web)</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Funcionalidades específicas por página</li>
          <li><i class="ti ti-check" aria-hidden="true"></i>Preço definido após briefing</li>
        </ul>
        <a class="btn-primary" href="https://wa.me/5588994342633" target="_blank" style="width:100%;text-align:center;display:block;">Solicitar orçamento</a>
      </div>
    </div>
    <div class="monthly-card" style="margin-top:1.5rem;">
      <div style="flex:1;min-width:200px;">
        <span class="monthly-badge"><i class="ti ti-refresh" style="font-size:12px;vertical-align:-1px;margin-right:4px" aria-hidden="true"></i>Plano mensal</span>
        <h3>Manutenção e suporte contínuo</h3>
        <p style="margin-top:0.5rem;font-size:14px;">Para quem já tem site conosco e quer manter tudo sempre atualizado — alterações de texto, correção de erros, ajustes visuais e mais. Sujeito a descontos em próximas ofertas.</p>
      </div>
      <div style="text-align:center;flex-shrink:0;">
        <div style="font-size:32px;font-weight:500;color:#185FA5;">R$ 30</div>
        <div style="font-size:13px;color:var(--color-text-secondary);">por mês</div>
        <a class="btn-outline" href="https://wa.me/5588994342633" target="_blank" style="margin-top:12px;display:block;text-align:center;">Assinar plano</a>
      </div>
    </div>
  </section>

  <hr class="divider">

  <section>
    <div class="section-header">
      <span class="badge">Diferenciais</span>
      <h2>Por que escolher a Atlas Digital?</h2>
    </div>
    <div class="grid-3">
      <div class="card">
        <div class="icon-circle"><i class="ti ti-device-mobile" aria-hidden="true"></i></div>
        <h3>100% responsivo</h3>
        <p style="margin-top:8px;">Todos os sites funcionam perfeitamente em celulares, tablets e computadores.</p>
      </div>
      <div class="card">
        <div class="icon-circle"><i class="ti ti-currency-dollar" aria-hidden="true"></i></div>
        <h3>Preço justo</h3>
        <p style="margin-top:8px;">Planos acessíveis para pequenos negócios e empreendedores, sem abrir mão da qualidade.</p>
      </div>
      <div class="card">
        <div class="icon-circle"><i class="ti ti-headset" aria-hidden="true"></i></div>
        <h3>Suporte próximo</h3>
        <p style="margin-top:8px;">Atendimento direto com o criador do projeto. Sem burocracia, sem intermediários.</p>
      </div>
    </div>
  </section>

  <hr class="divider">

  <section id="contato">
    <div class="cta-box">
      <span style="background:#185FA5;color:#B5D4F4;font-size:12px;font-weight:500;padding:4px 14px;border-radius:99px;display:inline-block;margin-bottom:1rem;">Fale com a gente</span>
      <h2>Pronto para ter seu site?</h2>
      <p>Entre em contato pelo canal de sua preferência. Resposta rápida, atendimento humano.</p>
      <div style="display:flex;flex-wrap:wrap;gap:12px;justify-content:center;margin-top:1.5rem;">
        <a class="contact-btn btn-whatsapp" href="https://wa.me/5588994342633" target="_blank">
          <i class="ti ti-brand-whatsapp" aria-hidden="true"></i>(88) 9 9434-2633
        </a>
        <a class="contact-btn btn-email" href="mailto:marcos.morais0806@gmail.com">
          <i class="ti ti-mail" aria-hidden="true"></i>marcos.morais0806@gmail.com
        </a>
        <a class="contact-btn btn-instagram" href="https://instagram.com/o.atlasdigital" target="_blank">
          <i class="ti ti-brand-instagram" aria-hidden="true"></i>@o.atlasdigital
        </a>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="footer-copy">© 2025 Atlas Digital · Desenvolvido por Mr.</div>
    <div class="footer-links">
      <a href="#planos" onclick="document.getElementById('planos').scrollIntoView({behavior:'smooth'});return false;">Planos</a>
      <a href="#como-funciona" onclick="document.getElementById('como-funciona').scrollIntoView({behavior:'smooth'});return false;">Como funciona</a>
      <a href="#contato" onclick="document.getElementById('contato').scrollIntoView({behavior:'smooth'});return false;">Contato</a>
      <a href="https://instagram.com/o.atlasdigital" target="_blank">Instagram</a>
    </div>
  </footer>

</div>
