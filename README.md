# scrollbar-custom

/* Чтобы изменить скролл в Firefox, используйте следующий код. */
  scrollbar-color: #458245 #714826;     /* «цвет ползунка» «цвет полосы скроллбара» */
  scrollbar-width: auto | thin | none;  /* толщина */
    
/* Чтобы стилизовать скролл для Google Chrome, Яндекс.Браузер, Safari и Opera используйте следующие CSS свойства. */
  /* полоса прокрутки (скроллбар) */
  ::-webkit-scrollbar {
      width: 24px; /* ширина для вертикального скролла */
      height: 8px; /* высота для горизонтального скролла */
      background-color: #143861;
  }

  /* ползунок скроллбара */
  ::-webkit-scrollbar-thumb {
      background-color: #843465;
      border-radius: 9em;
      box-shadow: inset 1px 1px 10px #f3faf7;
  }

  ::-webkit-scrollbar-thumb:hover {
      background-color: #253861;
  }

  /* Стрелки */

  ::-webkit-scrollbar-button:vertical:start:decrement {
      background: linear-gradient(120deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
      linear-gradient(240deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
      linear-gradient(0deg, #02141a 30%, rgba(0, 0, 0, 0) 31%);
      background-color: #f6f8f4;
  }

  ::-webkit-scrollbar-button:vertical:end:increment {
      background:
          linear-gradient(300deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
          linear-gradient(60deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
          linear-gradient(180deg, #02141a 30%, rgba(0, 0, 0, 0) 31%);
      background-color: #f6f8f4;
  }

  ::-webkit-scrollbar-button:horizontal:start:decrement {
      background:
          linear-gradient(30deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
          linear-gradient(150deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
          linear-gradient(270deg, #02141a 30%, rgba(0, 0, 0, 0) 31%);
      background-color: #f6f8f4;
  }

  ::-webkit-scrollbar-button:horizontal:end:increment {
      background:
          linear-gradient(210deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
          linear-gradient(330deg, #02141a 40%, rgba(0, 0, 0, 0) 41%),
          linear-gradient(90deg, #02141a 30%, rgba(0, 0, 0, 0) 31%);
      background-color: #f6f8f4;
  }
