<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Страница с агентом</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 20px;
        background-color: #f5f5f5;
      }
      .container {
        max-width: 1200px;
        margin: 0 auto;
        background: #ffffff;
        padding: 30px;
        border-radius: 8px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      }
      h1 {
        color: #333;
      }
      p {
        color: #555;
        line-height: 1.5;
      }
      /* Опционально: стили для области виджета */
      #agent-container {
        margin-top: 30px;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <h1>Веб‑страница со встроенным агентом</h1>
      <p>Здесь размещён агент из Яндекс Студии — он поможет с текстами, кодом, анализом файлов и другими задачами.</p>

      <div id="agent-container">
        <!-- Скрипт агента будет загружать виджет сюда -->
        <script
          src="https://widget.aistudio.yandexcloud.net/scripts/widget-loader.js?channel-id=aacfhbabtleakuj15foq"
          async
        ></script>
      </div>
    </div>
  </body>
</html>
