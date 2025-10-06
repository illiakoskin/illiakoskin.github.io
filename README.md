<!doctype html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Политика конфиденциальности — Автоблюр видео</title>
<style>
  body{font:16px/1.5 system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;max-width:860px;margin:40px auto;padding:0 16px;color:#111}
  h1{font-size:28px;margin:.5em 0}
  h2{font-size:20px;margin:1.25em 0 .4em}
  small{color:#666}
  .card{background:#fff;border:1px solid #e5e7eb;border-radius:12px;padding:18px}
</style>
</head>
<body>
  <h1>Политика конфиденциальности — «Автоблюр видео»</h1>
  <div class="card">
    <p><small>Последнее обновление: 2025-10-06</small></p>

    <h2>Кратко</h2>
    <p>Расширение не собирает, не передаёт и не продаёт ваши персональные данные. Все настройки (тайминги, сила блюра, смещение времени) хранятся <strong>локально</strong> в браузере с помощью <code>chrome.storage.local</code> и не покидают ваше устройство.</p>

    <h2>Какие данные обрабатываются</h2>
    <ul>
      <li>Локальные настройки расширения: список временных отрезков, уровень блюра, смещение времени.</li>
      <li>Идентификатор сайта (origin) для привязки настроек к конкретному домену.</li>
    </ul>
    <p>Эти данные доступны только вашему браузеру. Расширение не выполняет сетевых запросов на наши/чьи-либо серверы.</p>

    <h2>Разрешения браузера</h2>
    <ul>
      <li><code>storage</code> — хранение локальных настроек.</li>
      <li><code>scripting</code> — вставка кратких скриптов, чтобы применить CSS-блюр к тегу <code>&lt;video&gt;</code> и добавить кнопку на странице с таймингами.</li>
      <li><code>activeTab</code> — работа только с активной вкладкой по действию пользователя.</li>
      <li><code>webNavigation</code> — определение нужного фрейма (iframe) с видеоплеером. История просмотров не читается и не сохраняется.</li>
      <!-- Если укажете конкретные сайты:
      <li>Host permissions — доступ только к доменам, на которых находится видеоплеер/тайминги, чтобы вставить кнопку и применить блюр.</li> -->
    </ul>

    <h2>Детям</h2>
    <p>Расширение не предназначено для детей и не таргетирует несовершеннолетних.</p>

    <h2>Связь</h2>
    <p>По вопросам политики напишите на: <a href="mailto:youremail@example.com">youremail@example.com</a>.</p>

    <h2>Изменения политики</h2>
    <p>Мы можем обновлять эту страницу. Актуальная версия всегда доступна по этому URL.</p>
  </div>

  <hr style="margin:32px 0;border:none;border-top:1px solid #e5e7eb">

  <h1>Privacy Policy (EN)</h1>
  <div class="card">
    <p><small>Last updated: 2025-10-06</small></p>
    <h2>Summary</h2>
    <p>This extension does not collect, transmit, or sell personal data. All settings (timing ranges, blur strength, time offset) are stored <strong>locally</strong> in the browser via <code>chrome.storage.local</code> and never leave your device.</p>
    <h2>Data processed</h2>
    <ul>
      <li>Local extension settings: timing ranges, blur strength, time offset.</li>
      <li>Site origin used to bind settings per domain.</li>
    </ul>
    <p>No network requests are made to our or any third-party servers.</p>
    <h2>Permissions</h2>
    <ul>
      <li><code>storage</code> — store local settings.</li>
      <li><code>scripting</code> — inject small scripts to apply CSS blur to the <code>&lt;video&gt;</code> element and add a button near timings.</li>
      <li><code>activeTab</code> — operate only on the active tab after user action.</li>
      <li><code>webNavigation</code> — detect the correct iframe that hosts the video player; browsing history is neither read nor stored.</li>
      <!-- If using site-scoped hosts:
      <li>Host permissions — limited to the domains where the player/timings live; used solely to insert the button and apply blur.</li> -->
    </ul>
    <h2>Contact</h2>
    <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
    <h2>Changes</h2>
    <p>We may update this policy; the latest version will always be available at this URL.</p>
  </div>
</body>
</html>
