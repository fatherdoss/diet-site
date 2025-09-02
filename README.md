<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Диетолог Екатерина Досова — Похудение без голода</title>

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Базовые стили -->
  <style>
    :root {
      color-scheme: light;
    }
    body { font-family: ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; }
    .badge { @apply px-3 py-1 rounded-full bg-emerald-100 text-emerald-700 text-sm; }
    .card  { @apply rounded-3xl shadow-lg p-6 bg-white; }
    .btn   { @apply inline-flex items-center justify-center rounded-2xl px-6 py-3 text-base font-semibold shadow-lg hover:shadow-xl transition active:scale-[.98]; }
    .btn-primary { @apply bg-emerald-600 text-white; }
    .btn-ghost   { @apply border border-emerald-600/30 text-emerald-700 hover:bg-emerald-50; }
    .container   { @apply max-w-6xl mx-auto px-4 sm:px-6; }
  </style>
</head>
<body class="min-h-screen w-full bg-gradient-to-b from-emerald-50 via-white to-white text-slate-800">

  <script>
    // ✳️ Настройки ссылок
    const WHATSAPP_PHONE = "79002214444"; // номер без +
    const waLink = "https://wa.me/" + WHATSAPP_PHONE + "?text=" + encodeURIComponent("Здравствуйте, хочу похудеть с Вами. Меня зовут ...");
    const instagramLink = "https://www.instagram.com/katyadosss";
  </script>

  <!-- Шапка -->
  <header class="sticky top-0 z-40 backdrop-blur bg-white/80 border-b border-emerald-100">
    <div class="container py-3 flex items-center justify-between">
      <a href="#top" class="font-black text-xl tracking-tight flex items-center gap-2">
        <span class="inline-grid place-items-center w-9 h-9 rounded-2xl bg-emerald-600 text-white">KD</span>
        Диетолог Екатерина Дос
      </a>
      <nav class="hidden md:flex items-center gap-6 font-medium">
        <a href="#program" class="hover:text-emerald-600">Программа</a>
        <a href="#results" class="hover:text-emerald-600">Результаты</a>
        <a href="#pricing" class="hover:text-emerald-600">Тарифы</a>
        <a href="#faq" class="hover:text-emerald-600">FAQ</a>
      </nav>
      <div class="flex items-center gap-3">
        <a class="btn btn-ghost" target="_blank" rel="noopener" id="btn-inst">Instagram</a>
        <a class="btn btn-primary" target="_blank" rel="noopener" id="btn-wa">Написать в WhatsApp</a>
      </div>
    </div>
  </header>

  <!-- Херо -->
  <section id="top" class="container pt-10 sm:pt-16 pb-12">
    <div class="grid lg:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl sm:text-5xl font-black leading-tight">
          Похудение без голода и запретов
          <span class="block text-emerald-600">со мной — лично и заботливо</span>
        </h1>
        <p class="mt-5 text-lg text-slate-600">
          Персональные планы питания и тренировок, которые вписываются в вашу жизнь. Вкусная еда, научный подход и ощутимый результат.
        </p>
        <div class="mt-7 flex flex-wrap gap-3">
          <a class="btn btn-primary" target="_blank" rel="noopener" id="cta-start">Хочу начать</a>
          <a class="btn btn-ghost" href="#program">Как это работает</a>
        </div>
        <div class="mt-8 flex flex-wrap gap-3 text-sm">
          <span class="badge">Личный контроль прогресса</span>
          <span class="badge">Меню под ваши вкусы</span>
          <span class="badge">Эффект с первой недели</span>
        </div>
      </div>

      <div class="relative">
        <img id="hero-img"
     src="https://raw.githubusercontent.com/fatherdoss/diet-site/main/Fitness_02.jpg"
     alt="Фитнес-зал с видом на море"
     class="w-full rounded-3xl shadow-2xl object-cover aspect-[4/3]">

        <div class="absolute -bottom-5 -left-5 bg-white rounded-2xl shadow-xl p-4 hidden sm:flex flex-col gap-1">
          <span class="text-xs uppercase text-slate-500">ОНЛАЙН-СОПРОВОЖДЕНИЕ</span>
          <span class="text-lg font-bold">Старт за 24 часа</span>
        </div>

        <!-- Кнопка загрузки главного фото (необязательно) -->
        <div class="mt-3">
          <label class="inline-block text-sm text-slate-500 cursor-pointer">
            <input type="file" accept="image/*" class="hidden" id="hero-file">
            Заменить главное фото (локально)
          </label>
        </div>
      </div>
    </div>
  </section>

  <!-- Как это работает -->
  <section id="program" class="container py-12 sm:py-16">
    <h2 class="text-3xl sm:text-4xl font-black text-center">Как мы будем худеть</h2>
    <p class="mt-3 text-center text-slate-600 max-w-3xl mx-auto">
      Пошаговый план, который даёт стабильный минус в сантиметрах и килограммах — без срывов и усталости.
    </p>

    <div class="mt-10 grid md:grid-cols-3 gap-6">
      <div class="card">
        <div class="text-emerald-600 text-sm font-bold">Шаг 1</div>
        <div class="mt-2 text-xl font-semibold">Диагностика</div>
        <p class="mt-2 text-slate-600">Собираю данные: привычки, цели, здоровье. Определим комфортный дефицит и режим.</p>
      </div>
      <div class="card">
        <div class="text-emerald-600 text-sm font-bold">Шаг 2</div>
        <div class="mt-2 text-xl font-semibold">Меню + тренировки</div>
        <p class="mt-2 text-slate-600">Вкусный план питания без голода и программа активности под ваш график.</p>
      </div>
      <div class="card">
        <div class="text-emerald-600 text-sm font-bold">Шаг 3</div>
        <div class="mt-2 text-xl font-semibold">Еженедельный контроль</div>
        <p class="mt-2 text-slate-600">Я на связи, корректирую меню, отвечаю на вопросы и поддерживаю. Вы не одни!</p>
      </div>
    </div>
  </section>

  <!-- Галерея -->
  <section id="results" class="container py-12 sm:py-16">
    <h2 class="text-3xl sm:text-4xl font-black text-center">Результаты клиентов</h2>
    <p class="mt-3 text-center text-slate-600 max-w-3xl mx-auto">
      Добавьте сюда свои фото «до/после» — это сильнее любых слов.
    </p>

    <div class="mt-8 grid sm:grid-cols-2 lg:grid-cols-4 gap-5" id="gallery">
      <!-- Можно заменить src на свои ссылки -->
      <img class="w-full rounded-2xl shadow-lg object-cover aspect-square" src="https://images.unsplash.com/photo-1554284126-aa88f22d8b74?q=80&w=1200&auto=format&fit=crop" alt="результат 1">
      <img class="w-full rounded-2xl shadow-lg object-cover aspect-square" src="https://images.unsplash.com/photo-1518112166137-85f9979a43a5?q=80&w=1200&auto=format&fit=crop" alt="результат 2">
      <img class="w-full rounded-2xl shadow-lg object-cover aspect-square" src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?q=80&w=1200&auto=format&fit=crop" alt="результат 3">
      <img class="w-full rounded-2xl shadow-lg object-cover aspect-square" src="https://images.unsplash.com/photo-1514512364185-4c2b1cd2e2d0?q=80&w=1200&auto=format&fit=crop" alt="результат 4">
    </div>

    <!-- Кнопка загрузки своих фото (опционально) -->
    <div class="mt-4 text-center">
      <label class="inline-block text-sm text-slate-500 cursor-pointer">
        <input type="file" accept="image/*" multiple class="hidden" id="gal-files">
        Загрузить свои фото (локально)
      </label>
    </div>

    <div class="mt-8 text-center">
      <a class="btn btn-ghost" target="_blank" rel="noopener" id="cta-result">Хочу такой же результат</a>
    </div>
  </section>

  <!-- Тарифы -->
  <section id="pricing" class="container py-12 sm:py-16">
    <h2 class="text-3xl sm:text-4xl font-black text-center">Тарифы сопровождения</h2>
    <p class="mt-3 text-center text-slate-600 max-w-3xl mx-auto">
      Выберите формат: я всегда на связи и под вас подстроюсь.
    </p>

    <div class="mt-10 grid md:grid-cols-3 gap-6">
      <div class="card">
        <div class="flex items-baseline justify-between gap-2">
          <div class="text-xl font-bold">Старт 2 недели</div>
          <div class="text-emerald-700 font-semibold">฿3,900 / 2 недели</div>
        </div>
        <ul class="mt-4 space-y-2 text-slate-700">
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Аудит рациона и целей</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Меню на 14 дней</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Чеки и замеры 1 раз/нед</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Поддержка в WhatsApp</li>
        </ul>
        <div class="mt-6">
          <a class="btn btn-primary" target="_blank" rel="noopener" id="p1">Начать</a>
        </div>
      </div>

      <div class="card ring-2 ring-emerald-500">
        <div class="flex items-baseline justify-between gap-2">
          <div class="text-xl font-bold">Месяц сопровождения</div>
          <div class="text-emerald-700 font-semibold">฿6,900 / месяц</div>
        </div>
        <ul class="mt-4 space-y-2 text-slate-700">
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Меню с заменами и рецептами</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Программа тренировок</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Еженедельные корректировки</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Ответы 6/7 дней</li>
        </ul>
        <div class="mt-6">
          <a class="btn btn-primary" target="_blank" rel="noopener" id="p2">Иду в форму</a>
        </div>
      </div>

      <div class="card">
        <div class="flex items-baseline justify-between gap-2">
          <div class="text-xl font-bold">VIP 1:1</div>
          <div class="text-emerald-700 font-semibold">Индивидуально</div>
        </div>
        <ul class="mt-4 space-y-2 text-slate-700">
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Полный консьерж-сервис</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Ежедневный контроль</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Разбор анализов</li>
          <li class="flex gap-2"><span class="mt-1 h-2 w-2 rounded-full bg-emerald-500"></span> Личные встречи (по запросу)</li>
        </ul>
        <div class="mt-6">
          <a class="btn btn-primary" target="_blank" rel="noopener" id="p3">Обсудить детали</a>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq" class="container py-12 sm:py-16">
    <h2 class="text-3xl sm:text-4xl font-black text-center">Частые вопросы</h2>
    <div class="mt-8 grid md:grid-cols-2 gap-6">
      <div class="card">
        <div class="font-semibold text-lg">Буду ли я голодать?</div>
        <p class="mt-2 text-slate-600">Нет. План строится на сытных блюдах и грамотном дефиците. Вы едите вкусно и чувствуете энергию.</p>
      </div>
      <div class="card">
        <div class="font-semibold text-lg">Можно ли сладкое?</div>
        <p class="mt-2 text-slate-600">Да, вписываем любимые продукты так, чтобы прогресс сохранялся без срывов.</p>
      </div>
      <div class="card">
        <div class="font-semibold text-lg">Нужны ли тренировки?</div>
        <p class="mt-2 text-slate-600">Активность ускоряет результат. Подберу уровень под вашу подготовку и расписание.</p>
      </div>
      <div class="card">
        <div class="font-semibold text-lg">Как быстро будет результат?</div>
        <p class="mt-2 text-slate-600">Первую динамику увидите уже на 1–2 неделе: минус в объёмах и самочувствии.</p>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="container py-10">
    <div class="relative overflow-hidden rounded-3xl p-8 sm:p-10 bg-gradient-to-r from-emerald-600 to-teal-600 text-white shadow-xl">
      <div class="relative z-10">
        <h3 class="text-2xl sm:text-3xl font-black">Готовы начать путь к лёгкому телу?</h3>
        <p class="mt-2 text-white/90 max-w-2xl">Напишите мне в WhatsApp — отвечу, задам пару вопросов и соберу стартовый план в течение суток.</p>
        <div class="mt-6 flex gap-3">
          <a class="btn bg-white text-emerald-700" target="_blank" rel="noopener" id="cta-wa">Написать в WhatsApp</a>
          <a class="btn btn-ghost border-white/40 hover:bg-white/10" target="_blank" rel="noopener" id="cta-ig">Мой Instagram</a>
        </div>
      </div>
      <div class="absolute -right-16 -top-16 w-64 h-64 rounded-full bg-white/10 blur-2xl"></div>
    </div>
  </section>

  <!-- Подвал -->
  <footer class="border-t border-emerald-100 py-8">
    <div class="container flex flex-col sm:flex-row items-center justify-between gap-3 text-sm text-slate-500">
      <div>© <span id="year"></span> Екатерина Досова · Диетолог</div>
      <div class="flex items-center gap-4">
        <a target="_blank" rel="noopener" class="hover:text-emerald-600" id="foot-ig">Instagram @katyadosss</a>
        <a target="_blank" rel="noopener" class="hover:text-emerald-600" id="foot-wa">WhatsApp</a>
      </div>
    </div>
  </footer>

  <!-- Плавающая WhatsApp-кнопка -->
  <a target="_blank" rel="noopener"
     class="fixed bottom-5 right-5 sm:bottom-8 sm:right-8 rounded-full shadow-2xl p-4 bg-emerald-600 hover:bg-emerald-700 text-white"
     aria-label="Написать в WhatsApp" title="Написать в WhatsApp" id="float-wa">
     <!-- иконка -->
     <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-6 h-6 fill-current"><path d="M380.9 97.1C339-3.9 231.8-33.1 141.4 23 88.1 56.1 54.4 113.3 48.2 178.7c-6.8 73.2 20.2 143.5 73 196.3 52.8 52.8 123.1 79.8 196.3 73 65.4-6.2 122.6-39.9 155.7-93.2 56.1-90.4 26.9-197.6-74.1-239.5zM224 438.7c-48.1 0-95.2-18.8-131.3-54.9-34.5-34.5-53.7-79.3-54.9-127.1-1.2-47.8 15.5-92.6 47-128.2 32.5-36.8 77-57.7 124.6-57.7 48.1 0 95.2 18.8 131.3 54.9 36.1 36.1 54.9 83.2 54.9 131.3 0 47.6-18.3 92.1-54.9 128.2-36.1 36.1-83.2 54.9-131.3 54.9z"/></svg>
  </a>

  <!-- Логика ссылок и локальная замена фото -->
  <script>
    // Подставляем ссылки
    const setHref = (id, url) => { const el = document.getElementById(id); if (el) el.href = url; };

    setHref("btn-inst", instagramLink);
    setHref("btn-wa", waLink);
    setHref("cta-start", waLink);
    setHref("cta-result", waLink);
    setHref("p1", waLink);
    setHref("p2", waLink);
    setHref("p3", waLink);
    setHref("cta-wa", waLink);
    setHref("cta-ig", instagramLink);
    setHref("foot-ig", instagramLink);
    setHref("foot-wa", waLink);
    setHref("float-wa", waLink);

    // Год в подвале
    document.getElementById("year").textContent = new Date().getFullYear();

    // Замена главного фото локально
    const heroFile = document.getElementById("hero-file");
    const heroImg = document.getElementById("hero-img");
    if (heroFile && heroImg) {
      heroFile.addEventListener("change", (e) => {
        const f = e.target.files && e.target.files[0];
        if (!f) return;
        const r = new FileReader();
        r.onload = (ev) => { heroImg.src = ev.target.result; };
        r.readAsDataURL(f);
      });
    }

    // Замена галереи локально
    const galInput = document.getElementById("gal-files");
    const gallery = document.getElementById("gallery");
    if (galInput && gallery) {
      galInput.addEventListener("change", (e) => {
        const files = Array.from(e.target.files || []);
        if (!files.length) return;
        gallery.innerHTML = "";
        files.slice(0, 6).forEach((f) => {
          const r = new FileReader();
          r.onload = (ev) => {
            const img = document.createElement("img");
            img.src = ev.target.result;
            img.alt = "результат";
            img.className = "w-full rounded-2xl shadow-lg object-cover aspect-square";
            gallery.appendChild(img);
          };
          r.readAsDataURL(f);
        });
      });
    }
  </script>
</body>
</html>
