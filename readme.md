## Typed.j

```javascript
var typed = new Typed(".element", {
  /**
   * @property {array} strings strings to be typed
   * @property {string} stringsElement ID of element containing string children
   */
  strings: [
    "These are the default values...",
    "You know what you should do?",
    "Use your own!",
    "Have a great day!"
  ],
  stringsElement: null,

  /**
   * @property {number} typeSpeed escriba la velocidad en milisegundos
   */
  typeSpeed: 0,

  /**
   * @property {number} startDelay tiempo antes de que comience a escribir en milisegundos
   */
  startDelay: 0,

  /**
   * @property {number} backSpeed velocidad de retroceso en milisegundos
   */
  backSpeed: 0,

  /**
   * @property {boolean} smartBackspace solo retrocede lo que no coincide con la cadena anterior
   */
  smartBackspace: true,

  /**
   * @property {boolean} shuffle barajar las cuerdas
   */
  shuffle: false,

  /**
   * @property {number} backDelay tiempo antes de retroceder en milisegundos
   */
  backDelay: 700,

  /**
   * @property {boolean} fadeOut Desvanecer en lugar de retroceder
   * @property {string} fadeOutClass clase css para animación de desvanecimiento
   * @property {boolean} fadeOutDelay Retardo de desvanecimiento en milisegundos
   */
  fadeOut: false,
  fadeOutClass: "typed-fade-out",
  fadeOutDelay: 500,

  /**
   * @property {boolean} loop cuerdas de bucle
   * @property {number} loopCount cantidad de bucles
   */
  loop: false,
  loopCount: Infinity,

  /**
   * @property {boolean} showCursor mostrar el cursor
   * @property {string} cursorChar caracter para cursor
   * @property {boolean} autoInsertCss inserte CSS para el cursor y desvanezca en HTML <head>
   */
  showCursor: true,
  cursorChar: "|",
  autoInsertCss: true,

  /**
   * @property {string} attr atributo para escribir
   * Ej.: marcador de posición de entrada, valor o simplemente texto HTML
   */
  attr: null,

  /**
   * @property {boolean} bindInputFocusEvents enlazar para enfocar y desenfocar si el es entrada de texto
   */
  bindInputFocusEvents: false,

  /**
   * @property {string} contentType 'html' or 'null' for plaintext
   */
  contentType: "html",

  /**
   * Before it begins typing
   * @param {Typed} self
   */
  onBegin: (self) => {},

  /**
   * All typing is complete
   * @param {Typed} self
   */
  onComplete: (self) => {},

  /**
   * Before each string is typed
   * @param {number} arrayPos
   * @param {Typed} self
   */
  preStringTyped: (arrayPos, self) => {},

  /**
   * After each string is typed
   * @param {number} arrayPos
   * @param {Typed} self
   */
  onStringTyped: (arrayPos, self) => {},

  /**
   * During looping, after last string is typed
   * @param {Typed} self
   */
  onLastStringBackspaced: (self) => {},

  /**
   * Typing has been stopped
   * @param {number} arrayPos
   * @param {Typed} self
   */
  onTypingPaused: (arrayPos, self) => {},

  /**
   * Typing has been started after being stopped
   * @param {number} arrayPos
   * @param {Typed} self
   */
  onTypingResumed: (arrayPos, self) => {},

  /**
   * After reset
   * @param {Typed} self
   */
  onReset: (self) => {},

  /**
   * After stop
   * @param {number} arrayPos
   * @param {Typed} self
   */
  onStop: (arrayPos, self) => {},

  /**
   * Después de empezar
   * @param {number} arrayPos
   * @param {Typed} self
   */
  onStart: (arrayPos, self) => {},

  /**
   * Después de destruir
   * @param {Typed} self
   */
  onDestroy: (self) => {}
});
```
