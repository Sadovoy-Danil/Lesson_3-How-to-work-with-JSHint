# Lesson_3-How-to-work-with-JSHint

В этом уроке мы продолжили настройку нашей рабочей части редактора кода. Для того, чтобы _**JSHint**_ начал работать так, как нам надо: 
1) Установить *Node.js* 
2) Зайти в *PowerShell* и Ввести: 'npm install -g jshint' + Enter, тем самым установить _**JSHint**_

Также для правильной работы _**JSHint**_, нам требуется его настроить, создаем документ _.jshintrc_ и вписуем наши [параметры](https://jshint.com/docs/options/ "Все параметры JSHint"):

{
   "camelcase" : true, 
   "indent": 2,
   "undef": true,
   "quotmark": false,
   "maxlen": 80,
   "trailing": true,
   "curly": true,
   "strict": false,
   "browser": true,
   "jquery": true,
   "esversion": 6
}

_**Словарь**_

[*npm*](https://www.npmjs.com/package/nmp) — менеджер пакетов, входящий в состав Node.js.

[*Node.js*](https://nodejs.org/) — программная платформа, превращающая JavaScript из узкоспециализированного языка в язык общего назначения.

[*JSHint*](https://jshint.com/) — это инструмент  статического анализа кода, а также плагин, который используется в разработке ПО  для проверки, исходный код на JavaScript  соответствует правилам кодирования.

_**P.S. Для того, чтобы красиво выравнить ваш код используйте сочетание клавиш Alt + Shift + F**_
