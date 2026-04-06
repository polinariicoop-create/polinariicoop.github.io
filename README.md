# polinariicoop.github.io
[offer (1).txt](https://github.com/user-attachments/files/26515099/offer.1.txt)
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>5 навыков человека нового времени — Лекция 30 апреля</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; background: #f7f6f2; color: #1a1a1a; line-height: 1.6; }

  .container { max-width: 720px; margin: 0 auto; padding: 0 1.25rem; }

  /* HERO */
  .hero { background: #1a1a2e; color: #f0ede6; padding: 3.5rem 1.25rem 3rem; text-align: center; }
  .hero-eyebrow { font-size: 11px; font-weight: 600; letter-spacing: .12em; text-transform: uppercase; color: #9b97e8; margin-bottom: 1.25rem; }
  .hero-title { font-size: clamp(22px, 5vw, 32px); font-weight: 600; line-height: 1.35; margin-bottom: 1rem; max-width: 600px; margin-left: auto; margin-right: auto; }
  .hero-sub { font-size: 15px; color: #b8b4cc; line-height: 1.7; max-width: 520px; margin: 0 auto 2rem; }
  .hero-date { display: inline-block; background: rgba(155,151,232,.15); border: 1px solid rgba(155,151,232,.3); border-radius: 6px; padding: .45rem 1rem; font-size: 13px; color: #c4c0e0; margin-bottom: 1.75rem; }
  .btn-primary { display: inline-block; background: #6c63d4; color: #fff; font-size: 15px; font-weight: 600; padding: .85rem 2.25rem; border-radius: 8px; text-decoration: none; transition: background .2s; cursor: pointer; border: none; }
  .btn-primary:hover { background: #5a52b8; }
  .btn-note { font-size: 12px; color: #7a7690; margin-top: .6rem; }

  /* SECTIONS */
  section { padding: 3rem 1.25rem; }
  section:nth-child(even) { background: #fff; }
  .section-label { font-size: 10px; font-weight: 700; letter-spacing: .1em; text-transform: uppercase; color: #9b97e8; margin-bottom: .6rem; }
  h2 { font-size: clamp(18px, 4vw, 24px); font-weight: 600; color: #1a1a2e; line-height: 1.35; margin-bottom: 1.25rem; }

  /* PAIN */
  .pain-list { list-style: none; margin-bottom: 1.5rem; }
  .pain-list li { font-size: 14px; color: #444; padding: .55rem 0 .55rem 1.25rem; border-bottom: .5px solid #ebe8e0; position: relative; }
  .pain-list li::before { content: "—"; position: absolute; left: 0; color: #9b97e8; }
  .pain-final { font-size: 16px; font-weight: 600; color: #1a1a2e; background: #f0efe8; border-left: 3px solid #6c63d4; border-radius: 0 8px 8px 0; padding: .85rem 1.1rem; }

  /* QUOTE */
  .quote-section { background: #1a1a2e !important; color: #f0ede6; text-align: center; }
  .quote-section h2 { color: #f0ede6; }
  .big-quote { font-size: clamp(16px, 3.5vw, 22px); font-weight: 600; color: #c4c0e0; line-height: 1.5; max-width: 560px; margin: 0 auto 1.5rem; font-style: italic; }
  .quote-body { font-size: 14px; color: #8c88a8; line-height: 1.8; max-width: 520px; margin: 0 auto; }

  /* CARDS GRID */
  .cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: .75rem; margin-top: .5rem; }
  .card { background: #f7f6f2; border: .5px solid #e0ddd4; border-radius: 10px; padding: 1rem 1.1rem; }
  .card-title { font-size: 13px; font-weight: 600; color: #1a1a2e; margin-bottom: .4rem; }
  .card-body { font-size: 12px; color: #666; line-height: 1.6; }
  section:nth-child(even) .card { background: #f7f6f2; }
  section:nth-child(odd) .card { background: #fff; }

  /* PROGRAM */
  .program-item { border: .5px solid #e0ddd4; border-radius: 10px; margin-bottom: .6rem; overflow: hidden; }
  .program-header { display: flex; align-items: center; gap: .75rem; padding: .9rem 1.1rem; cursor: pointer; background: #fff; transition: background .15s; }
  .program-header:hover { background: #f7f6f2; }
  .prog-num { font-size: 10px; font-weight: 700; letter-spacing: .08em; text-transform: uppercase; color: #9b97e8; min-width: 48px; }
  .prog-title { font-size: 14px; font-weight: 600; color: #1a1a2e; flex: 1; }
  .prog-arrow { font-size: 12px; color: #aaa; transition: transform .2s; }
  .program-body { display: none; padding: 0 1.1rem .9rem 1.1rem; background: #fff; }
  .program-body.open { display: block; }
  .program-header.open .prog-arrow { transform: rotate(90deg); }
  .prog-list { list-style: none; }
  .prog-list li { font-size: 13px; color: #555; padding: .3rem 0 .3rem 1rem; position: relative; border-bottom: .5px solid #f0ede6; }
  .prog-list li:last-child { border-bottom: none; }
  .prog-list li::before { content: "—"; position: absolute; left: 0; color: #c4c0e0; }

  /* FOR WHO */
  .for-list { list-style: none; }
  .for-list li { font-size: 14px; color: #444; padding: .65rem 0 .65rem 1.5rem; border-bottom: .5px solid #ebe8e0; position: relative; }
  .for-list li::before { content: "✓"; position: absolute; left: 0; color: #6c63d4; font-weight: 700; }

  /* ECONOMY */
  .econ-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(155px, 1fr)); gap: .65rem; margin: 1rem 0; }
  .econ-card { background: #fff; border: .5px solid #e0ddd4; border-radius: 10px; padding: .85rem 1rem; }
  .econ-what { font-size: 11px; color: #888; margin-bottom: 3px; }
  .econ-price { font-size: 15px; font-weight: 700; color: #1a1a2e; }
  .econ-note { font-size: 11px; color: #999; margin-top: 3px; line-height: 1.4; }
  .vs-row { display: flex; align-items: stretch; gap: .75rem; margin: 1.25rem 0; }
  .vs-left { flex: 1; background: #f7f6f2; border-radius: 10px; padding: .85rem 1rem; }
  .vs-mid { display: flex; align-items: center; font-size: 13px; font-weight: 700; color: #bbb; }
  .vs-right { flex: 1; background: #eeedfe; border-radius: 10px; padding: .85rem 1rem; }
  .vs-lbl { font-size: 10px; text-transform: uppercase; letter-spacing: .07em; color: #aaa; margin-bottom: 3px; }
  .vs-val { font-size: 13px; font-weight: 600; color: #1a1a2e; line-height: 1.4; }
  .vs-val.purple { color: #4a42b0; }
  .econ-note-bottom { font-size: 13px; color: #555; line-height: 1.7; margin-top: .75rem; }

  /* FORMAT */
  .format-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: .65rem; margin-top: .75rem; }
  .format-card { background: #f7f6f2; border-radius: 10px; padding: .8rem 1rem; }
  .format-icon { font-size: 18px; margin-bottom: .3rem; }
  .format-val { font-size: 13px; font-weight: 600; color: #1a1a2e; }
  .format-lbl { font-size: 11px; color: #888; margin-top: 2px; }

  /* TARIFFS */
  .tariffs { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1rem; margin-top: 1rem; }
  .tariff { border: 1.5px solid #e0ddd4; border-radius: 14px; padding: 1.5rem 1.4rem; background: #fff; position: relative; }
  .tariff.featured { border-color: #6c63d4; background: #1a1a2e; color: #f0ede6; }
  .tariff-badge { position: absolute; top: -13px; left: 50%; transform: translateX(-50%); background: #6c63d4; color: #fff; font-size: 11px; font-weight: 700; letter-spacing: .07em; text-transform: uppercase; padding: 3px 14px; border-radius: 20px; white-space: nowrap; }
  .tariff-name { font-size: 11px; font-weight: 700; letter-spacing: .1em; text-transform: uppercase; color: #9b97e8; margin-bottom: .5rem; }
  .tariff.featured .tariff-name { color: #9b97e8; }
  .tariff-title { font-size: 17px; font-weight: 700; color: #1a1a2e; margin-bottom: .75rem; line-height: 1.3; }
  .tariff.featured .tariff-title { color: #f0ede6; }
  .tariff-price { font-size: 28px; font-weight: 800; color: #1a1a2e; margin-bottom: .2rem; }
  .tariff.featured .tariff-price { color: #c4c0e0; }
  .tariff-price-note { font-size: 12px; color: #999; margin-bottom: 1.1rem; }
  .tariff.featured .tariff-price-note { color: #7a7690; }
  .tariff-list { list-style: none; margin-bottom: 1.25rem; }
  .tariff-list li { font-size: 13px; color: #444; padding: .45rem 0 .45rem 1.3rem; border-bottom: .5px solid #f0ede6; position: relative; line-height: 1.5; }
  .tariff.featured .tariff-list li { color: #c4c0e0; border-bottom-color: rgba(255,255,255,.08); }
  .tariff-list li:last-child { border-bottom: none; }
  .tariff-list li::before { content: "✓"; position: absolute; left: 0; color: #6c63d4; font-weight: 700; font-size: 12px; }
  .tariff.featured .tariff-list li::before { color: #9b97e8; }
  .tariff-btn { display: block; text-align: center; padding: .8rem; border-radius: 8px; font-size: 14px; font-weight: 700; cursor: pointer; border: none; text-decoration: none; transition: all .2s; }
  .tariff-btn.light { background: #eeedfe; color: #4a42b0; }
  .tariff-btn.light:hover { background: #dddcfc; }
  .tariff-btn.dark { background: #6c63d4; color: #fff; }
  .tariff-btn.dark:hover { background: #5a52b8; }
  .tariff-extra { font-size: 12px; color: #999; text-align: center; margin-top: .5rem; }
  .tariff.featured .tariff-extra { color: #6a6580; }

  /* FOOTER CTA */
  .footer-cta { background: #1a1a2e; color: #f0ede6; padding: 3rem 1.25rem; text-align: center; }
  .footer-cta h2 { color: #f0ede6; margin-bottom: .5rem; }
  .footer-sub { font-size: 14px; color: #8c88a8; margin-bottom: 2rem; }

  @media (max-width: 480px) {
    .vs-row { flex-direction: column; }
    .vs-mid { justify-content: center; padding: .25rem 0; }
  }
</style>
</head>
<body>

<!-- HERO -->
<div class="hero">
  <div class="container">
    <div class="hero-eyebrow">Живая лекция</div>
    <h1 class="hero-title">Мир изменился. Старые правила больше не работают. А большинство людей всё ещё живут по ним.</h1>
    <p class="hero-sub">Живая лекция о том, как не остаться за бортом — и построить устойчивую жизнь в новой реальности.</p>
    <div class="hero-date">📅 30 апреля 2025 · 19:00 по Москве</div><br>
    <a href="#tariffs" class="btn-primary">Выбрать тариф и купить место</a>
    <p class="btn-note">Запись остаётся навсегда · доступ сразу после оплаты</p>
  </div>
</div>

<!-- ПРОБЛЕМА -->
<section>
  <div class="container">
    <div class="section-label">Боль</div>
    <h2>Тебе знакомо это ощущение?</h2>
    <ul class="pain-list">
      <li>Много делаю — нет результата</li>
      <li>Много знаю — не действую</li>
      <li>Тревога фоном: что-то не так, но непонятно что</li>
      <li>Пробовала менять внешнее: переезд, работу, окружение — не помогло</li>
      <li>Время идёт, ясности нет</li>
      <li>Страх остаться не у дел в новом мире</li>
    </ul>
    <div class="pain-final">Это не слабость и не лень. Это отсутствие системы для нового времени.</div>
  </div>
</section>

<!-- ЦИТАТА -->
<section class="quote-section">
  <div class="container">
    <p class="big-quote">«Если ты не управляешь собой — тобой управляют. Государство. Корпорации. Алгоритмы.»</p>
    <p class="quote-body">Мир проходит смену эпох. Посткапитализм, цифровизация, нестабильность рынков — это не временный кризис, это новая норма. Внешних опор больше нет: государство, образование, стабильная карьера перестали гарантировать безопасность. В этой реальности опора — только внутри.</p>
  </div>
</section>

<!-- АКТУАЛЬНОСТЬ -->
<section>
  <div class="container">
    <div class="section-label">Почему сейчас</div>
    <h2>Почему это важно именно сейчас</h2>
    <div class="cards">
      <div class="card">
        <div class="card-title">Новая норма, а не кризис</div>
        <div class="card-body">2020-е — смена эпохи. Те, кто освоит навыки адаптации сейчас, окажутся в другой позиции через 2–3 года. Те, кто ждёт стабильности снаружи — продолжат терять время и деньги.</div>
      </div>
      <div class="card">
        <div class="card-title">Алгоритмы управляют теми, кто не управляет собой</div>
        <div class="card-body">Корпорации монетизируют внимание. Алгоритмы формируют картину мира. Единственная защита — развитое мышление и психологическая устойчивость.</div>
      </div>
      <div class="card">
        <div class="card-title">Знания без системы не работают</div>
        <div class="card-body">Информации больше, чем когда-либо. Но уровень тревоги и прокрастинации — рекордный. Проблема не в знаниях — в отсутствии внутренней системы. Лекция даёт именно её.</div>
      </div>
    </div>
  </div>
</section>

<!-- ПРОГРАММА -->
<section>
  <div class="container">
    <div class="section-label">Содержание</div>
    <h2>Программа лекции</h2>
    <p style="font-size:14px;color:#666;margin-bottom:1.25rem">Лекция строится как исследование — от того, как был устроен мир раньше, к тому, что происходит сейчас и что конкретно делать. С биологией мозга, разбором ложных стратегий и практиками под каждый навык.</p>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 1</span>
        <span class="prog-title">Что изменилось и почему старые правила не работают</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Как был устроен успех раньше и какие стратегии давали результат</li>
          <li>Что такое посткапитализм и как он меняет правила игры</li>
          <li>Крах внешних опор: государство, образование, партнёр</li>
          <li>Почему переезд и «больше зарабатывать» дают лишь временный эффект</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 2</span>
        <span class="prog-title">Почему нам так сложно меняться — биология, а не слабая воля</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Как устроен мозг и почему он сопротивляется изменениям</li>
          <li>Откуда берутся зависимости и почему мы застреваем в старых сценариях</li>
          <li>Почему много знаний — но нет действий</li>
          <li>Что происходит с психикой в условиях информационной перегрузки</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 3</span>
        <span class="prog-title">Навык 1 — Мышление</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Как воспринимать реальность и создавать смыслы</li>
          <li>Критическое и системное мышление как база</li>
          <li>Как принимать решения в условиях неопределённости</li>
          <li>Практика: инструмент для проверки убеждений</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 4</span>
        <span class="prog-title">Навык 2 — Психология</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Работа с эмоциями без подавления и разрушения</li>
          <li>Внутренние сценарии, которые управляют твоими выборами</li>
          <li>Эмоциональный интеллект как инструмент</li>
          <li>Практика: как выдерживать себя в тревоге и стрессе</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 5</span>
        <span class="prog-title">Навык 3 — Телесность</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Тело как партнёр, а не проект по улучшению</li>
          <li>Связь физического состояния и качества решений</li>
          <li>Уровень энергии и почему ты устаёшь раньше времени</li>
          <li>Практика: слышать тело до сигналов SOS</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 6</span>
        <span class="prog-title">Навык 4 — Адаптация</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Гибкость как главное конкурентное преимущество нового времени</li>
          <li>Как действовать в неопределённости без паралича</li>
          <li>Почему «ждать стабильности» — проигрышная стратегия</li>
          <li>Практика: алгоритм быстрой адаптации к новым условиям</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Блок 7</span>
        <span class="prog-title">Навык 5 — Воля</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Воля — это система, а не сила характера</li>
          <li>Как доводить до результата без надрыва и выгорания</li>
          <li>Почему «просто начать» не работает — и что работает вместо</li>
          <li>Практика: как выстроить действия, которые дают результат</li>
        </ul>
      </div>
    </div>

    <div class="program-item">
      <div class="program-header" onclick="toggle(this)">
        <span class="prog-num">Финал</span>
        <span class="prog-title">Человек нового времени — сборка системы</span>
        <span class="prog-arrow">▶</span>
      </div>
      <div class="program-body">
        <ul class="prog-list">
          <li>Как все 5 навыков работают вместе как единая система</li>
          <li>Как адаптировать это под свою жизнь и ситуацию</li>
          <li>Q&A: живой разбор вопросов участников</li>
          <li>Что делать сразу после лекции</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- ДЛЯ КОГО -->
<section>
  <div class="container">
    <div class="section-label">Для кого</div>
    <h2>Эта лекция для тебя, если</h2>
    <ul class="for-list">
      <li>Чувствуешь тревогу от нестабильности и хочешь систему, а не успокоительные слова</li>
      <li>Много делаешь, но нет результата — и не понимаешь, где разрыв</li>
      <li>Хочешь финансовой стабильности и реализованности — и понимаешь, что снаружи это не найти</li>
      <li>Устала тратить деньги на курсы и марафоны без системного сдвига</li>
      <li>Хочешь один раз разобраться в основах — и перестать блуждать</li>
    </ul>
  </div>
</section>

<!-- ЭКОНОМИЯ -->
<section>
  <div class="container">
    <div class="section-label">Ценность</div>
    <h2>Сколько стоит не иметь этих знаний</h2>
    <div class="econ-grid">
      <div class="econ-card">
        <div class="econ-what">Психолог</div>
        <div class="econ-price">от 3 000 ₽</div>
        <div class="econ-note">за сессию · годы работы без целостной картины</div>
      </div>
      <div class="econ-card">
        <div class="econ-what">Марафоны и курсы</div>
        <div class="econ-price">5 000–30 000 ₽</div>
        <div class="econ-note">мотивация на 2 недели без системного сдвига</div>
      </div>
      <div class="econ-card">
        <div class="econ-what">Коучинг</div>
        <div class="econ-price">15 000–50 000 ₽</div>
        <div class="econ-note">за пакет · часто без понимания «почему»</div>
      </div>
      <div class="econ-card">
        <div class="econ-what">Переезд / смена работы</div>
        <div class="econ-price">сотни тысяч</div>
        <div class="econ-note">месяцы потерь без изменения внутренней системы</div>
      </div>
    </div>
    <div class="vs-row">
      <div class="vs-left">
        <div class="vs-lbl">Без этих знаний</div>
        <div class="vs-val">Годы проб и ошибок · десятки тысяч рублей · те же грабли</div>
      </div>
      <div class="vs-mid">VS</div>
      <div class="vs-right">
        <div class="vs-lbl">С лекцией</div>
        <div class="vs-val purple">от 2 480 ₽ · система за 1 вечер · применяешь сразу</div>
      </div>
    </div>
    <p class="econ-note-bottom">Лекция не заменяет терапию — но даёт то, чего там часто нет: целостную картину нового мира и понимание, куда направить усилия. Это экономит деньги, время и энергию — потому что ты перестаёшь тратить их на стратегии, которые уже не работают.</p>
  </div>
</section>

<!-- ТАРИФЫ -->
<section id="tariffs">
  <div class="container">
    <div class="section-label">Тарифы</div>
    <h2>Выбери свой формат</h2>
    <div class="tariffs">

      <!-- ТАРИФ 1 -->
      <div class="tariff">
        <div class="tariff-name">Тариф 1</div>
        <div class="tariff-title">Онлайн + запись</div>
        <div class="tariff-price">2 480 ₽</div>
        <div class="tariff-price-note">разовая оплата · доступ навсегда</div>
        <ul class="tariff-list">
          <li>Участие в живом эфире 30 апреля, 19:00 МСК</li>
          <li>Запись лекции навсегда</li>
          <li>Практики по каждому из 5 навыков</li>
          <li>Q&A в конце эфира</li>
          <li>Доступ к записи сразу после оплаты</li>
        </ul>
        <a href="#" class="tariff-btn light">Купить за 2 480 ₽</a>
        <div class="tariff-extra">Запись придёт автоматически, даже если не попадёшь на эфир</div>
      </div>

      <!-- ТАРИФ 2 -->
      <div class="tariff featured">
        <div class="tariff-badge">Максимум результата</div>
        <div class="tariff-name">Тариф 2</div>
        <div class="tariff-title">Лекция + Разбор</div>
        <div class="tariff-price">12 480 ₽</div>
        <div class="tariff-price-note">разовая оплата · всё включено</div>
        <ul class="tariff-list">
          <li>Участие в живом эфире 30 апреля, 19:00 МСК</li>
          <li>Запись лекции навсегда</li>
          <li>Практики по каждому из 5 навыков</li>
          <li>Q&A в конце эфира</li>
          <li><strong style="color:#c4c0e0">Групповой созвон через неделю после лекции</strong> — разбор личных ситуаций адаптации</li>
          <li>Разбор возражений и карьерной реализации</li>
          <li>Формирование личной стратегии под твою ситуацию</li>
        </ul>
        <a href="#" class="tariff-btn dark">Купить за 12 480 ₽</a>
        <div class="tariff-extra">Мест ограничено — для глубокой работы в группе</div>
      </div>

    </div>
  </div>
</section>

<!-- ФОРМАТ -->
<section>
  <div class="container">
    <div class="section-label">Формат</div>
    <h2>Как проходит лекция</h2>
    <div class="format-grid">
      <div class="format-card">
        <div class="format-icon">🎥</div>
        <div class="format-val">Живой эфир</div>
        <div class="format-lbl">30 апреля · 19:00 МСК</div>
      </div>
      <div class="format-card">
        <div class="format-icon">📹</div>
        <div class="format-val">Запись навсегда</div>
        <div class="format-lbl">Доступ сразу после оплаты</div>
      </div>
      <div class="format-card">
        <div class="format-icon">✍️</div>
        <div class="format-val">Практики</div>
        <div class="format-lbl">По каждому из 5 навыков</div>
      </div>
      <div class="format-card">
        <div class="format-icon">💬</div>
        <div class="format-val">Q&A в конце</div>
        <div class="format-lbl">Живой разбор вопросов</div>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER CTA -->
<div class="footer-cta">
  <div class="container">
    <h2>Ты не можешь изменить жизнь,<br>если не меняешь себя как систему</h2>
    <p class="footer-sub">30 апреля · 19:00 по Москве · запись навсегда</p>
    <a href="#tariffs" class="btn-primary">Выбрать тариф и занять место</a>
    <p class="btn-note" style="color:#6a6580;margin-top:.75rem">После эфира цена на запись вырастет</p>
  </div>
</div>

<script>
function toggle(header) {
  const body = header.nextElementSibling;
  const isOpen = body.classList.contains('open');
  document.querySelectorAll('.program-body.open').forEach(b => b.classList.remove('open'));
  document.querySelectorAll('.program-header.open').forEach(h => h.classList.remove('open'));
  if (!isOpen) {
    body.classList.add('open');
    header.classList.add('open');
  }
}
</script>

</body>
</html>
