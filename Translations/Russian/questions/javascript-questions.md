## Вопросы по JS

Ответы для [Front-end Job Interview Questions - JS Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/questions/javascript-questions.md). Pull request'ы предложений и исправлений приветствуются!

* [Расскажите о делегировании событий.](#explain-event-delegation)
* [Как работает `this` в Javascript?](#explain-how-this-works-in-javascript)
* [Как работает прототипное наследование?](#explain-how-prototypal-inheritance-works)
* [Что вы думаете об AMD vs CommonJS?](#what-do-you-think-of-amd-vs-commonjs)
* [Почему данная функция не работает как IIFE (Immediately Invoked Function Expression, немедленно вызываемая функция): `function foo(){ }();`. Что нужно изменить, чтобы заставить её работать?](#explain-why-the-following-doesnt-work-as-an-iife-function-foo--what-needs-to-be-changed-to-properly-make-it-an-iife)
* [В чем разница между `null`, `undefined` и необьявленными переменными?  Как вы можете проверить переменную на эти состояния?](#whats-the-difference-between-a-variable-that-is-null-undefined-or-undeclared-how-would-you-go-about-checking-for-any-of-these-states)
* [Что такое замыкание? Как и почему вы должны его использовать?](#what-is-a-closure-and-howwhy-would-you-use-one)
* [Опишите основное отличие перебора с помощью `.forEach` и `.map()`. По каким причинам стоит выбрать тот или иной метод?](#can-you-describe-the-main-difference-between-a-foreach-loop-and-a-map-loop-and-why-you-would-pick-one-versus-the-other)
* [Каково основное применение анонимных функций?](#whats-a-typical-use-case-for-anonymous-functions)
* [Как вы организуете свой код? (паттерн "Модуль", классическое наследование?)](#how-do-you-organize-your-code-module-pattern-classical-inheritance)
* [В чем разница между хост объектами (объектами среды выполнения) и нативными объектами?](#whats-the-difference-between-host-objects-and-native-objects)
* [Обьясните разницу: `function Person(){}`, `var person = Person()`, и `var person = new Person()`?](#difference-between-function-person-var-person--person-and-var-person--new-person)
* [Чем отличаются `.call` и `.apply`?](#whats-the-difference-between-call-and-apply)
* [Обьясните принцип работы `Function.prototype.bind`.](#explain-functionprototypebind)
* [Когда вы будете использовать `document.write()`?](#when-would-you-use-documentwrite)
* [В чем разница между "feature detection", "feature inference" и использованием строки юзер-агента? (для определения поддерживаемых браузером клиента возможностей)](#whats-the-difference-between-feature-detection-feature-inference-and-using-the-ua-string)
* [Опишите как можно детальнее технологию Ajax.](#explain-ajax-in-as-much-detail-as-possible)
* [Каковы преимущества и недостатки использования Ajax?](#what-are-the-advantages-and-disadvantages-of-using-ajax)
* [Как работает JSONP  (и почему это не совсем Ajax).](#explain-how-jsonp-works-and-how-its-not-really-ajax)
* [Вы когда-нибудь использовали JavaScript шаблонизаторы? Если да, то какие библиотеки вы использовали?](#have-you-ever-used-javascript-templating-if-so-what-libraries-have-you-used)
* [Обьясните принцип работы "hoisting" ("поднятие" объявления переменных).](#explain-hoisting)
* [Опишите механизм всплытия событий ("event bubbling").](#describe-event-bubbling)
* [В чем разница между аттрибутом ("attribute") и свойством ("property")?](#whats-the-difference-between-an-attribute-and-a-property)
* [Почему расширение встроенных JavaScript объектов - плохая идея?](#why-is-extending-built-in-javascript-objects-not-a-good-idea)
* [Объясните разницу между событиями `load` и `DOMContentLoaded`?](#difference-between-document-load-event-and-document-domcontentloaded-event)
* [Чем отличается `==` от `===`?](#what-is-the-difference-between--and-)
* [Обьясните политику одинакового источника ("same-origin policy") в контексте JavaScript.](#explain-the-same-origin-policy-with-regards-to-javascript)
* [Реализуйте следующую функцию: `duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]`](#make-this-work)
* [Почему тернарное выражение ("Ternary expression") так называется, что обозначает слово "тернарный"?](#why-is-it-called-a-ternary-expression-what-does-the-word-ternary-indicate)
* [Что обозначает выражение "use strict";? Какие вы видите преимущества и недостатки при его использовании?](#what-is-use-strict-what-are-the-advantages-and-disadvantages-to-using-it)
* [Создайте цикл `for`, который выводит в консоль числа от 1 до 100, при этом заменяя число на строку "fizz", если оно делится на 3,"buzz", если число делится на 5, и "fizzbuzz", если число делится и на 3, и на 5. ](#create-a-for-loop-that-iterates-up-to-100-while-outputting-fizz-at-multiples-of-3-buzz-at-multiples-of-5-and-fizzbuzz-at-multiples-of-3-and-5)
* [Почему будет хорошей идеей не помещать ничего в глобальную область видимости сайта?](#why-is-it-in-general-a-good-idea-to-leave-the-global-scope-of-a-website-as-is-and-never-touch-it)
* [В каких обстоятельствах вы используете событие `load`? У этого события есть недостатки? Знаете ли вы какие-либо альтернативы событию `load` и когда их стоит использовать?](#why-would-you-use-something-like-the-load-event-does-this-event-have-disadvantages-do-you-know-any-alternatives-and-why-would-you-use-those)
* [Обьясните, что такое одностраничное приложение ("single page application") и как сделать его доступным для поисковых роботов ("SEO-friendly").](#explain-what-a-single-page-app-is-and-how-to-make-one-seo-friendly)
* [Насколько велик ваш опыт работы с Обещаниями ("Promise") и/или их полифиллами?](#what-is-the-extent-of-your-experience-with-promises-andor-their-polyfills)
* [Каковы плюсы и минусы Обещаний ("Promises") по сравнению с функциями обратного вызова ("callback")?](#what-are-the-pros-and-cons-of-using-promises-instead-of-callbacks)
* [Какие преимущества и недостатки существуют в написании Javascript кода на языке, который компилируются в Javascript?](#what-are-some-of-the-advantagesdisadvantages-of-writing-javascript-code-in-a-language-that-compiles-to-javascript)
* [Какие инструменты и методы вы используете для отладки Javascript кода?](#what-tools-and-techniques-do-you-use-for-debugging-javascript-code)
* [Какие языковые конструкции вы применяете для итерации по свойствам объекта и элементам массива?](#what-language-constructions-do-you-use-for-iterating-over-object-properties-and-array-items)
* [Объясните разницу между изменяемыми("mutable") и неизменяемыми ("immutable") объектами.](#explain-the-difference-between-mutable-and-immutable-objects)
* [Объясните разницу между синхронными и асинхронными функциями.](#explain-the-difference-between-synchronous-and-asynchronous-functions)
* [What is event loop? What is the difference between call stack and task queue?](#what-is-event-loop-what-is-the-difference-between-call-stack-and-task-queue)
* [Объясните разницу между этими объявлениями `foo`: `function foo() {}` и `var foo = function() {}`](#explain-the-differences-on-the-usage-of-foo-between-function-foo--and-var-foo--function-)
* [В тем отличие между способами объявления переменных с помощью `let`, `var` или `const`?](#what-are-the-differences-between-variables-created-using-let-var-or-const)
* [Опишите особенности и отличия в объявлении классов в ES6 (ES6 классы) и ES5 (функции-конструкторы)?](#what-are-the-differences-between-es6-class-and-es5-function-constructors)
* [Предложите удачные примеры использования стрелочных ("arrow") => функций? Чем этот новый синтаксис отличается от других функций?](#can-you-offer-a-use-case-for-the-new-arrow--function-syntax-how-does-this-new-syntax-differ-from-other-functions)
* [В чем преимущество использования стрелочных функций в методах объекта?](#what-advantage-is-there-for-using-the-arrow-syntax-for-a-method-in-a-constructor)
* [Дайте определение функции высшего порядка ("high-order function")?](#what-is-the-definition-of-a-higher-order-function)
* [Можете ли вы привести пример использования деструктурирования ("desctructuring") объекта или массива?](#can-you-give-an-example-for-destructuring-an-object-or-an-array)
* [Строковые шаблоны ("Template literals") из ES6 дают нам большую гибкость в создании строк. Не могли бы вы привести пример?](#es6-template-literals-offer-a-lot-of-flexibility-in-generating-strings-can-you-give-an-example)
* [Можете ли вы привести пример каррирования ("curry") функции? В чем преимущества данного подхода?](#can-you-give-an-example-of-a-curry-function-and-why-this-syntax-offers-an-advantage)
* [В чем преимущества использования "spread" синтаксиса и чем он отличается от "rest" синтаксиса?](#what-are-the-benefits-of-using-spread-syntax-and-how-is-it-different-from-rest-syntax)
* [Как вы можете разделять код между файлами?](#how-can-you-share-code-between-files)
* [В каких обстоятельствах вы захотите использовать статические свойства/методы класса?](#why-you-might-want-to-create-static-class-members)

### Расскажите о делегировании событий

Делегирование событий это техника, при который слушатель события ("event listener") навешивается на родительский элемент вместо того, чтобы добавлять его к каждому дочернему элементу. Слушатель события будет вызван каждый раз, когда событие произойдет на дочерних элементах, благодаря всплытию событий вверх по DOM дереву. Преимуществами данной техники являются:

* Уменьшается расход памяти, потому что необходимо установить только один слушатель события на родительском элементе вместо его установки на каждый дочерний элемент.
* Нет необходимость отключать слушатели событий от удаляемых элементов и подключать к новым добавляемым элементам.

###### Ссылки по теме

* https://davidwalsh.name/event-delegate
* https://stackoverflow.com/questions/1687296/what-is-dom-event-delegation

[[↑] Наверх](#js-questions)

### Как работает `this` в Javascript?

Не существует простого объяснения для `this`; это одна из самых запутанных концепций в JavaScript. Грубое объяснение заключается в том, что `this` зависит от того, как функция была вызвана. Я прочитал много объяснений работы `this` в интернете, и я нахожу объяснение [Arnav Aggrawal](https://medium.com/@arnav_aggarwal) наиболее очевидным. Применяются следующий правилы:

1. Если ключевое слово `new` используется при вызове функции, `this` внутри функции относится к создаваемому объекту.
2. Если `apply`, `call` или `bind` используются для вызова/создания функции, `this` внутри такой функции соответствует объекту, переданному им в качестве аргумента.
3. Если функция вызывается как метод, например `obj.method()`,  `this` будет являться ссылкой на объект, свойством которого является эта функция.
4. Если функция вызывается без перечисленных выше условий, `this` указывает на глобальный объект. В браузере это объект `window`. Если вы используете строгий режим (`'use strict'`), `this` примет значение `undefined` вместо указания на глобальный объект.
5. Если применяются несколько правил из этого списка, то правило, которое находится в списке выше побеждает и установит значение `this`.
6. Если функция является ES2015 стрелочной функцией ("arrow function"), то она игнорирует все приведенные правила и получает `this` контекст из окружающей её на момент создания области видимости.

Для более глубокого объяснения вы можете ознакомиться с его [статьей на Medium](https://codeburst.io/the-simple-rules-to-this-in-javascript-35d97f31bde3).

###### Ссылки по теме

* https://codeburst.io/the-simple-rules-to-this-in-javascript-35d97f31bde3
* https://stackoverflow.com/a/3127440/1751946

[[↑] Наверх](#js-questions)

### Как работает прототипное наследование?

Это очень популярный вопрос на собеседовании. Все объекты в Javascript обладают `prototype` свойством, который является ссылкой на другой объект. Когда запрашивается свойство объекта, и это свойство не будет найдено в исходном объекте, Javascript будет искать это свойство в объекте, указанном в `prototype` исходного объекта, а потом в свойстве `prototype` указанного там объекта, и так до тех пор, пока не найдет нужное свойство или цепочка прототипов не прервется. Такое поведение имитирует классическое наследование,  но на самом деле это скорее [делегирование, чем наследование](https://davidwalsh.name/javascript-objects).

###### Ссылки по теме

* https://www.quora.com/What-is-prototypal-inheritance/answer/Kyle-Simpson
* https://davidwalsh.name/javascript-objects

[[↑] Наверх](#js-questions)

### Что вы думаете об AMD vs CommonJS?

Обе эти технологии служат для реализации модульной системы, которая не была представлена в Javascript до прихода  ES2015. CommonJS - синхронная реализация, тогда как AMD ("Asynchronous Module Definition"), очевидно, асинхронная. CommonJS разработана по большей части для серверной разработки, в то время как AMD, со своей поддержкой асинхронной загрузки модулей, больше подходит для использования в браузерах.

Я нахожу AMD синтаксис довольно многословным, а CommonJS ближе к стилю в котором вы пишите импорты модулей на других языках. В большинстве случаев я нахожу AMD ненужным: если вы храните свой Javascript в одном объединенном файле, вы не выиграете ничего от асинхронной загрузки. К тому же, CommonJS синтаксис ближе к стилю написания модулей на Node, что влечет за собой меньше затрат на переключение контекста при переходе между клиентской и серверной разработкой на Javascript.

Я рад, что с ES2015 модулями (которые поддерживают и синхронную, и асинхронную загрузку), мы можем, наконец, придерживаться одного подхода. И хотя новый синтаксис пока не обладает полной поддержкой во всех браузерах и Node, мы всегда можем использовать траспайлеры ("transpilers") для преобразования нашего кода.

###### Ссылки по теме

* https://auth0.com/blog/javascript-module-systems-showdown/
* https://stackoverflow.com/questions/16521471/relation-between-commonjs-amd-and-requirejs

[[↑] Наверх](#js-questions)

### Почему данная функция не работает как IIFE (Immediately Invoked Function Expression, немедленно вызываемая функция): `function foo(){ }();`. Что нужно изменить, чтобы заставить её работать?

IIFE означает немедленно вызываемая функция. Javascript расценивает код `function foo(){ }();` как `function foo(){ }` и `();`, где первая конструкция является *объявлением функции* (function declaration), а последняя (пара скобок) является попыткой вызова функции, но имя не определено, поэтому появляется ошибка `Uncaught SyntaxError: Unexpected token )`.

Есть два способа исправить это, которые включают в себя добавление дополнительных скобок: `(function foo(){ })()` и `(function foo(){ }())`. Операторы, начинающиеся со слова `function`, являются *объявлением функции (function declaration)*; обернув эту функцию в `()`, мы получим *функциональное выражение (function expression)*, которое может быть вызвано с последующим `()`. Эти функции не будут помещены в глобальную область видимости, и вы можете даже не указывать их названия, если вам не нужно ссылаться на функцию внутри самой функции.

Еще вы можете использовать `void` оператор: `void function foo(){ }();`. К сожалению, у этого подхода существует одна проблема. Результат выполнения этого выражения всегда undefined, поэтому если ваша IIFE функция что-то возвращает, вы не сможете его использовать. Пример:

```
// Don't add JS syntax to this code block to prevent Prettier from formatting it.
const foo = void function bar() { return 'foo'; }();

console.log(foo); // undefined
```

###### Ссылки по теме

* http://lucybain.com/blog/2014/immediately-invoked-function-expression/
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void

[[↑] Наверх](#js-questions)

### В чем разница между `null`, `undefined` и необьявленными переменными?  Как вы можете проверить переменную на эти состояния?

**Необьявленные (Undeclared)** переменные создаются при назначении значения идентификатору, который не был предварительно создан с помощью  `var`, `let` or `const`. Необьявленные переменные определяются глобально, за пределами текущей области видимости. В строгом режиме, при попытке присваивания необъявленной переменной произойдет ошибка `ReferenceError`. Необъявленные переменные плохи так же, как и глобальные переменные. Избегайте их любой ценой! Чтобы проверить на них,  оберните использование такой переменной в блок `try`/`catch`.

```js
function foo() {
  x = 1; // Throws a ReferenceError in strict mode
}

foo();
console.log(x); // 1
```

`undefined` переменная это такая переменная, которая была объявлена, но значение которой не присвоено. Это один из типов `undefined`. Если функция не возвращает никакого значения в результате выполнения, то результатом её выполнения тоже будет `undefined`. Чтобы проверить на это, используйте оператор строгого сравнения  (`===`)  или `typeof`, который даст в результате строку `'undefined'`. Помните, что не стоит использовать оператор нестрого сравнения для проверки, так как он вернет `true` и при значении `null`. 

```js
var foo;
console.log(foo); // undefined
console.log(foo === undefined); // true
console.log(typeof foo === 'undefined'); // true

console.log(foo == null); // true. Wrong, don't use this to check!

function bar() {}
var baz = bar();
console.log(baz); // undefined
```

Переменная, значением которой является `null`, была явно присвоена `null` значению. Она не содержит в в себе фактического значения и отличается от undefined тем, что это отсутствие значение было явно присвоено переменной. Чтобы проверить на `null`, просто сравнению переменную с `null` с помощью оператора строго сравнения. Обратите внимание, что, как и в ситуации выше, вы не должны использовать оператор нестрогого сравнения (`==`) для проверки: он вернет `true` и при значении `undefined`.

```js
var foo = null;
console.log(foo === null); // true
console.log(typeof foo === 'object'); // true

console.log(foo == undefined); // true. Wrong, don't use this to check!
```

Я никогда не оставляю мои переменные необъявленными или неопределенными. Я явно назначаю им `null` при объявлении, если не намерен использовать их прямо сейчас. Если вы используете линтер в своем рабочем процессе, он выдаст вам предупреждение при попытке использования необъявленной переменной.

###### Ссылки по теме

* https://stackoverflow.com/questions/15985875/effect-of-declared-and-undeclared-variables
* https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/undefined

[[↑] Наверх](#js-questions)

### Что такое замыкание? Как и почему вы должны его использовать?

Замыкание это сочетения функции и лексического окружения, в котором эта функция была объявлена. Слово "лексичекий" отражает тот факт, что лексическая область видимости использует местоположение, в котором переменная была объявлена в исходном коде, чтобы определить, где эта переменная будет доступна. Замыкания являются функциями, которые имеют доступ к переменным внешней функции, в который они были объявлены (даже если внешняя функция уже завершила выполнение).

**Зачем использовать замыкания?**

* Конфиденциальность данных / реализация приватных методов через замыкания. Чаще всего используется в  [паттерне модуль](https://addyosmani.com/resources/essentialjsdesignpatterns/book/#modulepatternjavascript).
* [Каррирование и частичное применение функций](https://medium.com/javascript-scene/curry-or-partial-application-8150044c78b8#.l4b6l1i3x).

###### Ссылки по теме

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
* https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36

[[↑] Наверх](#js-questions)

### Опишите основное отличие перебора с помощью `.forEach` и `.map()`. По каким причинам стоит выбрать тот или иной метод?

Чтобы понять разницы между этими способами, давайте взглянем на то, что каждый из них делает.

**`forEach`**

* Перебирает элементы в массиве.
* Выполняет функцию обратного вызова (callback) для каждого элемента.
* Не возвращает значения

```js
const a = [1, 2, 3];
const doubled = a.forEach((num, index) => {
  // Выполняем необходимые действия с num или index 
});

// doubled = undefined
```

**`map`**

* Перебирает элементы в массиве.
* Сопоставляет ("Maps") каждый элемент массива новому элементу, вызывая функцию (callback) для каждого элемента. Возвращает получившийся новый массив.

```js
const a = [1, 2, 3];
const doubled = a.map(num => {
  return num * 2;
});

// doubled = [2, 4, 6]
```

Основное отличие между  `.forEach` и `.map()` в том что `.map()` возвращает новый массив. Если вам нужно получить результат, но вы не хотите изменять оригинальный массив,  `.map()` будет лучшим выбором. Если же вам просто нужно перебрать элементы массива, `forEach` будет отличным способом

###### Ссылки по теме

* https://codeburst.io/javascript-map-vs-foreach-f38111822c0f

[[↑] Наверх](#js-questions)

### Каково основное применение анонимных функций?

Они могут использоваться как самовызывающиеся функции ("IIFE"), для инкапсуляции некоторого кода в локальной области видимости, в результате чего переменные, объявленные здесь, не попадут в глобальную область видимости.

```js
(function() {
  // Some code here.
})();
```

Они могут использоваться как функция обратного вызова ("callback"), которая будет использована один раз и не нужна где-либо еще. Код будет выглядеть более автономным и читаемым, когда обработчики объявляются прямо внутри вызывающего их кода, вместо того чтобы искать их где-то еще, чтобы найти тело функции.

```js
setTimeout(function() {
  console.log('Hello world!');
}, 1000);
```

Автономные функции могут использоваться как аргументы конструкций в стиле функционального программирования или Lodash (похоже на функции обратного вызова)

```js
const arr = [1, 2, 3];
const double = arr.map(function(el) {
  return el * 2;
});
console.log(double); // [2, 4, 6]
```

###### Ссылки по теме

* https://www.quora.com/What-is-a-typical-usecase-for-anonymous-functions
* https://stackoverflow.com/questions/10273185/what-are-the-benefits-to-using-anonymous-functions-instead-of-named-functions-fo

[[↑] Наверх](#js-questions)

### How do you organize your code? (module pattern, classical inheritance?)

В прошлом я использовал Backbone для моих моделей, что дает более ООП подход, создавая Backbone модели и присоединяя к ним методы.

Паттерн модуль все еще хорош, но сейчас я использую React/Redux, которые используют однонаправленный поток данных на основе архитектуры Flux. Я создаю модели моего приложения, используя простые объекты и пишу чистые функции для управления этими объектами. Управление состоянием осуществляется с помощью действий (actions) и редьюсеров (reducers), как и в любом другом Redux приложении.

Я избегаю классического наследования везде, где это возможно. Когда (и если) я это делаю, я придерживаюсь [этих правил](https://medium.com/@dan_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4)

The module pattern is still great, but these days, I use React/Redux which utilize a single-directional data flow based on Flux architecture. I would represent my app's models using plain objects and write utility pure functions to manipulate these objects. State is manipulated using actions and reducers like in any other Redux application.


[[↑] Наверх](#js-questions)

### В чем разница между хост объектами (объектами среды выполнения) и нативными объектами?

Нативные объекты это часть языка JavaScript, заявленные спецификацией ECMAScript , такие как `String`, `Math`, `RegExp`, `Object`, `Function` и так далее.

Хост объекты предоставляются  средой выполнения (браузер или Node), такие как  `window`, `XMLHTTPRequest` и так далее.

###### Ссылки по теме

* https://stackoverflow.com/questions/7614317/what-is-the-difference-between-native-objects-and-host-objects

[[↑] Наверх](#js-questions)

### Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?

Этот довольно расплывчатый вопрос. Мое лучшее предположение: тут спрашивается о конструкторах в Javascript. Формально говоря, `function Person(){}` это обычное объявление функции. Соглашения предписывают использовать PascalCase для функций, которые будут использоваться в качестве конструкторов.

`var person = Person()` вызывает `Person` как функцию, а не как конструктор. Подобный вызов является распространенной ошибкой, когда функция используется в качестве конструктора. Как правило, конструктор не возвращает никакого значения, поэтому вызов конструктора как обычной функции вернет `undefined` и присвоит его переменной, предзначенной предназначенной для экземпляра объекта ("instance").

`var person = new Person()` создаст экземпляр объекта `Person`, используя оператор `new`, который наследует от `Person.prototype`. В качестве альтернативы можно использовать `Object.create`, например: `Object.create(Person.prototype)`.

```js
function Person(name) {
  this.name = name;
}

var person = Person('John');
console.log(person); // undefined
console.log(person.name); // Uncaught TypeError: Cannot read property 'name' of undefined

var person = new Person('John');
console.log(person); // Person { name: "John" }
console.log(person.name); // "john"
```

###### Ссылки по теме

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new

[[↑] Наверх](#js-questions)

### What's the difference between `.call` and `.apply`?

И `.call`, и `.apply` применяются для вызова функций, и первый параметр будет использован в качестве значения контекста `this` внутри функции. Разница заключается в том, что `.call` принимает входные параметры, разделенные запятыми, в качестве следующих аргументов функции, в то время как `.apply` принимает массив в качестве следующего аргумента функции. 

```js
function add(a, b) {
  return a + b;
}

console.log(add.call(null, 1, 2)); // 3
console.log(add.apply(null, [1, 2])); // 3
```

[[↑] Наверх](#js-questions)

### Explain `Function.prototype.bind`.

Дословное объяснение с [MDN](https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_objects/Function/bind):

> Метод `bind()`создает новую функцию, которая при вызове будет использовать в качестве контекста `this` первый переданный аргумент, а остальные переданные в `bind()` аргументы будут использованы в качестве замены входящих аргументов исходной функции в заданном порядке.

По моему опыту, это наиболее полезный прием для привязки контекста `this` к методам классов, которые вы хотите передать в другие функции. Эта возможность часто используется в React компонентах.

###### Ссылки по теме

* https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_objects/Function/bind

[[↑] Наверх](#js-questions)

### When would you use `document.write()`?

`document.write()` записывает строку текста в поток документа, открытый с помощью `document.open()`. Когда `document.write()` выполняется после загрузки страницы, он вызывает  `document.open`, который полностью очищает текущий  документi (включая `<head>` и`<body>`!) и заменяет содержимым, переданным в качестве аргумента `document.write()`. По этой причине его применение обычно считается опасным, им не стоит злоупотреблять. 

Некоторые статьи в интернете объясняют, что  `document.write()` используется в коде аналитических скриптов  или для [включения стилей, которые будут работать только при включенном Javascript в браузере](https://www.quirksmode.org/blog/archives/2005/06/three_javascrip_1.html). Он даже используется в HTML5 boilerplate для [параллельной загрузки скриптов и сохранения порядка выполнения](https://github.com/paulirish/html5-boilerplate/wiki/Script-Loading-Techniques#documentwrite-script-tag)! Тем не менее, я подозреваю что все эти причины могут быть устаревшими, и в наши дни похожих возможностей можно достичь и без применения `document.write()`. Поправьте меня, если я ошибаюсь.

###### Ссылки по теме

* https://www.quirksmode.org/blog/archives/2005/06/three_javascrip_1.html
* https://github.com/h5bp/html5-boilerplate/wiki/Script-Loading-Techniques#documentwrite-script-tag

[[↑] Наверх](#js-questions)

### What's the difference between feature detection, feature inference, and using the UA string?

**Feature Detection**

Feature detection включает в себя работу по определению возможности поддержки браузером пользователя определенного блока кода и запуска разного кода в зависимости от того, поддерживается определенная возможность или нет, так что браузер всегда может обеспечить выполнение определенной работы вместо сбоя или ошибок в некоторых браузерах.
```js
if ('geolocation' in navigator) {
  // Can use navigator.geolocation
} else {
  // Handle lack of feature
}
```

[Modernizr](https://modernizr.com/) отличная библиотека для работы с feature detection.

**Feature Inference**

Feature inference проверяет на наличие определенных возможностей так же, как и feature detection, но использует для этого проверку на другую возможность, предполагая, что она тоже будет существовать, например: 

```js
if (document.getElementsByTagName) {
  element = document.getElementById(id);
}
```

Этот подход не рекомендуется. Feature detection является более надежным.

**Строка User Agent**

Это строка, предоставляемая браузером, позволяет узлам сетового протокола определять тип приложения, операционную систему, поставщика программного обеспечения или версию программного обеспечения запрашивающего агента пользователя. К ней можно получить доступ через `navigator.userAgent`. Тем не менее, эта строка сложна для парсинга и может быть подделана. Например, Chrome представляется и как Chrome, и как Safari. Поэтому для определения браузера Safari вы должны проверять на наличие строки Safari и отсутствие строки Chrome. Старайтесь избегать этого метода.

###### Ссылки по теме

* https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Feature_detection
* https://stackoverflow.com/questions/20104930/whats-the-difference-between-feature-detection-feature-inference-and-using-th
* https://developer.mozilla.org/en-US/docs/Web/HTTP/Browser_detection_using_the_user_agent

[[↑] Наверх](#js-questions)

### Explain Ajax in as much detail as possible.

Ajax (асинхронный JavaScript и XML) это набор методов web разработки, используюших множество wen технологий на стороне клиентской части для создания web приложений. C помощью Ajax, web приложения могут отпралять данные и получать ответ от сервера асинхронно (в фоне) без вмешательства в отображение и поведение текущей страницы. Отделяя слой обмена данными от слоя представления, Ajax позволяет web страницам и приложениям динамически изменять содержимое без необходимости перезагрузки всей страницы. На практике, современные реализации предпочитают использовать формат данные JSON вместо XML, так как JSON является нативным форматом для Javascript. 

Чаще всего для асинхронных запросов используется `XMLHttpRequest`, или более новая технология:  `fetch` API.

###### Ссылки по теме

* https://en.wikipedia.org/wiki/Ajax_(programming)
* https://developer.mozilla.org/en-US/docs/AJAX

[[↑] Наверх](#js-questions)

### What are the advantages and disadvantages of using Ajax?

**Преимущества**

* Лучше интерактивность. Можно подгружать необходимые данные с сервера динамически без необходимости перезагружать всю страницу
* Уменьшение количества запросов к сервису, так как необходимые скрипты и стили уже загружены.
* Легче поддерживать состояние приложения. JavaScript переменные и состояние DOM дерева будут сохраняться, поскольку страница не будет перезагружена. 
* Наибольшие преимущества достигаются при использовании в SPA (Single page application, одностраничные приложения).

**Недостатки**

* Динамическое содержимое сложнее поместить в закладки браузера.
* Не работает при отключенном Javascript в браузере.
* Некоторые веб краулеры (поисковые роботы) не выполняют Javascript код и не могут увидеть контент, который загружаются с помощью Javascript.
* Наибольшие недостатки проявляются при использовании в SPA.

[[↑] Наверх](#js-questions)

### Explain how JSONP works (and how it's not really Ajax).

JSONP (JSON with Padding, JSON с дополнением) это метод, который обычно используется для обхода кросс доменных политик безопасности в браузере, поскольку Ajax запросы с текущей страницы на другие домены запрещены.

JSONP работает, выполняя запрос к другому (cross-origin) домену с помощью `<script>` тега и обычно с параметром `callback` (функция обратного вызова) например: `https://example.com?callback=printData`. Сервер при ответе обернет необходимые данные вызовом функции `printData` и вернет результат на клиент.

```html
<!-- https://mydomain.com -->
<script>
function printData(data) {
  console.log(`Меня зовут ${data.name}!`);
}
</script>

<script src="https://example.com?callback=printData"></script>
```

```js
// Файл загруженный со страницы https://example.com?callback=printData
printData({ name: 'Вячеслав Володин' });
```

На стороне клиента существует функция `printData` в глобальной области видимости, и эта функция будет вызвана, когда будет получен ответ с другого (cross-origin) домена.

Использование JSONP может иметь последствия для безопасности вашего приложения. Так как JSONP ответ это исполняемый Javascript код, он может сделать все что угодно, что может сделать обычный Javascript, то есть вы должны полностью доверять источнику данных при JSONP запросах.

В наши дни,  [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing) является рекомендуемым подходом, а JSON рассматривается как "хак".

###### Ссылки по теме

* https://stackoverflow.com/a/2067584/1751946

[[↑] Наверх](#js-questions)

### Have you ever used JavaScript templating? If so, what libraries have you used?

Yes. Handlebars, Underscore, Lodash, AngularJS, and JSX. I disliked templating in AngularJS because it made heavy use of strings in the directives and typos would go uncaught. JSX is my new favorite as it is closer to JavaScript and there is barely any syntax to learn. Nowadays, you can even use ES2015 template string literals as a quick way for creating templates without relying on third-party code.

```js
const template = `<div>My name is: ${name}</div>`;
```

However, do be aware of a potential XSS in the above approach as the contents are not escaped for you, unlike in templating libraries.

[[↑] Back to top](#js-questions)

### Explain "hoisting".

Hoisting is a term used to explain the behavior of variable declarations in your code. Variables declared or initialized with the `var` keyword will have their declaration "moved" up to the top of the current scope, which we refer to as hoisting. However, only the declaration is hoisted, the assignment (if there is one), will stay where it is.

Note that the declaration is not actually moved - the JavaScript engine parses the declarations during compilation and becomes aware of declarations and their scopes. It is just easier to understand this behavior by visualizing the declarations as being hoisted to the top of their scope. Let's explain with a few examples.

```js
// var declarations are hoisted.
console.log(foo); // undefined
var foo = 1;
console.log(foo); // 1

// let/const declarations are NOT hoisted.
console.log(bar); // ReferenceError: bar is not defined
let bar = 2;
console.log(bar); // 2
```

Function declarations have the body hoisted while the function expressions (written in the form of variable declarations) only has the variable declaration hoisted.

```js
// Function Declaration
console.log(foo); // [Function: foo]
foo(); // 'FOOOOO'
function foo() {
  console.log('FOOOOO');
}
console.log(foo); // [Function: foo]

// Function Expression
console.log(bar); // undefined
bar(); // Uncaught TypeError: bar is not a function
var bar = function() {
  console.log('BARRRR');
};
console.log(bar); // [Function: bar]
```

[[↑] Back to top](#js-questions)

### Describe event bubbling.

When an event triggers on a DOM element, it will attempt to handle the event if there is a listener attached, then the event is bubbled up to its parent and the same thing happens. This bubbling occurs up the element's ancestors all the way to the `document`. Event bubbling is the mechanism behind event delegation.

[[↑] Back to top](#js-questions)

### What's the difference between an "attribute" and a "property"?

Attributes are defined on the HTML markup but properties are defined on the DOM. To illustrate the difference, imagine we have this text field in our HTML: `<input type="text" value="Hello">`.

```js
const input = document.querySelector('input');
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello
```

But after you change the value of the text field by adding "World!" to it, this becomes:

```js
console.log(input.getAttribute('value')); // Hello
console.log(input.value); // Hello World!
```

###### References

* https://stackoverflow.com/questions/6003819/properties-and-attributes-in-html

[[↑] Back to top](#js-questions)

### Why is extending built-in JavaScript objects not a good idea?

Extending a built-in/native JavaScript object means adding properties/functions to its `prototype`. While this may seem like a good idea at first, it is dangerous in practice. Imagine your code uses a few libraries that both extend the `Array.prototype` by adding the same `contains` method, the implementations will overwrite each other and your code will break if the behavior of these two methods is not the same.

The only time you may want to extend a native object is when you want to create a polyfill, essentially providing your own implementation for a method that is part of the JavaScript specification but might not exist in the user's browser due to it being an older browser.

###### References

* http://lucybain.com/blog/2014/js-extending-built-in-objects/

[[↑] Back to top](#js-questions)

### Difference between document `load` event and document `DOMContentLoaded` event?

The `DOMContentLoaded` event is fired when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.

`window`'s `load` event is only fired after the DOM and all dependent resources and assets have loaded.

###### References

* https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded
* https://developer.mozilla.org/en-US/docs/Web/Events/load

[[↑] Back to top](#js-questions)

### What is the difference between `==` and `===`?

`==` is the abstract equality operator while `===` is the strict equality operator. The `==` operator will compare for equality after doing any necessary type conversions. The `===` operator will not do type conversion, so if two values are not the same type `===` will simply return `false`. When using `==`, funky things can happen, such as:

```js
1 == '1'; // true
1 == [1]; // true
1 == true; // true
0 == ''; // true
0 == '0'; // true
0 == false; // true
```

My advice is never to use the `==` operator, except for convenience when comparing against `null` or `undefined`, where `a == null` will return `true` if `a` is `null` or `undefined`.

```js
var a = null;
console.log(a == null); // true
console.log(a == undefined); // true
```

###### References

* https://stackoverflow.com/questions/359494/which-equals-operator-vs-should-be-used-in-javascript-comparisons

[[↑] Back to top](#js-questions)

### Explain the same-origin policy with regards to JavaScript.

The same-origin policy prevents JavaScript from making requests across domain boundaries. An origin is defined as a combination of URI scheme, hostname, and port number. This policy prevents a malicious script on one page from obtaining access to sensitive data on another web page through that page's Document Object Model.

###### References

* https://en.wikipedia.org/wiki/Same-origin_policy

[[↑] Back to top](#js-questions)

### Make this work:

```js
duplicate([1, 2, 3, 4, 5]); // [1,2,3,4,5,1,2,3,4,5]
```

```js
function duplicate(arr) {
  return arr.concat(arr);
}

duplicate([1, 2, 3, 4, 5]); // [1,2,3,4,5,1,2,3,4,5]
```

[[↑] Back to top](#js-questions)

### Why is it called a Ternary expression, what does the word "Ternary" indicate?

"Ternary" indicates three, and a ternary expression accepts three operands, the test condition, the "then" expression and the "else" expression. Ternary expressions are not specific to JavaScript and I'm not sure why it is even in this list.

###### References

* https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Operators/Conditional_Operator

[[↑] Back to top](#js-questions)

### What is `"use strict";`? What are the advantages and disadvantages to using it?

'use strict' is a statement used to enable strict mode to entire scripts or individual functions. Strict mode is a way to opt into a restricted variant of JavaScript.

Advantages:

* Makes it impossible to accidentally create global variables.
* Makes assignments which would otherwise silently fail to throw an exception.
* Makes attempts to delete undeletable properties throw (where before the attempt would simply have no effect).
* Requires that function parameter names be unique.
* `this` is undefined in the global context.
* It catches some common coding bloopers, throwing exceptions.
* It disables features that are confusing or poorly thought out.

Disadvantages:

* Many missing features that some developers might be used to.
* No more access to `function.caller` and `function.arguments`.
* Concatenation of scripts written in different strict modes might cause issues.

Overall, I think the benefits outweigh the disadvantages, and I never had to rely on the features that strict mode blocks. I would recommend using strict mode.

###### References

* http://2ality.com/2011/10/strict-mode-hatred.html
* http://lucybain.com/blog/2014/js-use-strict/

[[↑] Back to top](#js-questions)

### Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`.

Check out this version of FizzBuzz by [Paul Irish](https://gist.github.com/jaysonrowe/1592432#gistcomment-790724).

```js
for (let i = 1; i <= 100; i++) {
  let f = i % 3 == 0,
    b = i % 5 == 0;
  console.log(f ? (b ? 'FizzBuzz' : 'Fizz') : b ? 'Buzz' : i);
}
```

I would not advise you to write the above during interviews though. Just stick with the long but clear approach. For more wacky versions of FizzBuzz, check out the reference link below.

###### References

* https://gist.github.com/jaysonrowe/1592432

[[↑] Back to top](#js-questions)

### Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

Every script has access to the global scope, and if everyone uses the global namespace to define their variables, collisions will likely occur. Use the module pattern (IIFEs) to encapsulate your variables within a local namespace.

[[↑] Back to top](#js-questions)

### Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?

The `load` event fires at the end of the document loading process. At this point, all of the objects in the document are in the DOM, and all the images, scripts, links and sub-frames have finished loading.

The DOM event `DOMContentLoaded` will fire after the DOM for the page has been constructed, but do not wait for other resources to finish loading. This is preferred in certain cases when you do not need the full page to be loaded before initializing.

TODO.

###### References

* https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers/onload

[[↑] Back to top](#js-questions)

### Explain what a single page app is and how to make one SEO-friendly.

The below is taken from the awesome [Grab Front End Guide](https://github.com/grab/front-end-guide), which coincidentally, is written by me!

Web developers these days refer to the products they build as web apps, rather than websites. While there is no strict difference between the two terms, web apps tend to be highly interactive and dynamic, allowing the user to perform actions and receive a response to their action. Traditionally, the browser receives HTML from the server and renders it. When the user navigates to another URL, a full-page refresh is required and the server sends fresh new HTML to the new page. This is called server-side rendering.

However, in modern SPAs, client-side rendering is used instead. The browser loads the initial page from the server, along with the scripts (frameworks, libraries, app code) and stylesheets required for the whole app. When the user navigates to other pages, a page refresh is not triggered. The URL of the page is updated via the [HTML5 History API](https://developer.mozilla.org/en-US/docs/Web/API/History_API). New data required for the new page, usually in JSON format, is retrieved by the browser via [AJAX](https://developer.mozilla.org/en-US/docs/AJAX/Getting_Started) requests to the server. The SPA then dynamically updates the page with the data via JavaScript, which it has already downloaded in the initial page load. This model is similar to how native mobile apps work.

The benefits:

* The app feels more responsive and users do not see the flash between page navigations due to full-page refreshes.
* Fewer HTTP requests are made to the server, as the same assets do not have to be downloaded again for each page load.
* Clear separation of the concerns between the client and the server; you can easily build new clients for different platforms (e.g. mobile, chatbots, smart watches) without having to modify the server code. You can also modify the technology stack on the client and server independently, as long as the API contract is not broken.

The downsides:

* Heavier initial page load due to the loading of framework, app code, and assets required for multiple pages.
* There's an additional step to be done on your server which is to configure it to route all requests to a single entry point and allow client-side routing to take over from there.
* SPAs are reliant on JavaScript to render content, but not all search engines execute JavaScript during crawling, and they may see empty content on your page. This inadvertently hurts the Search Engine Optimization (SEO) of your app. However, most of the time, when you are building apps, SEO is not the most important factor, as not all the content needs to be indexable by search engines. To overcome this, you can either server-side render your app or use services such as [Prerender](https://prerender.io/) to "render your javascript in a browser, save the static HTML, and return that to the crawlers".

###### References

* https://github.com/grab/front-end-guide#single-page-apps-spas
* http://stackoverflow.com/questions/21862054/single-page-app-advantages-and-disadvantages
* http://blog.isquaredsoftware.com/presentations/2016-10-revolution-of-web-dev/
* https://medium.freecodecamp.com/heres-why-client-side-rendering-won-46a349fadb52

[[↑] Back to top](#js-questions)

### What is the extent of your experience with Promises and/or their polyfills?

Possess working knowledge of it. A promise is an object that may produce a single value sometime in the future: either a resolved value or a reason that it's not resolved (e.g., a network error occurred). A promise may be in one of 3 possible states: fulfilled, rejected, or pending. Promise users can attach callbacks to handle the fulfilled value or the reason for rejection.

Some common polyfills are `$.deferred`, Q and Bluebird but not all of them comply with the specification. ES2015 supports Promises out of the box and polyfills are typically not needed these days.

###### References

* https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261

[[↑] Back to top](#js-questions)

### What are the pros and cons of using Promises instead of callbacks?

**Pros**

* Avoid callback hell which can be unreadable.
* Makes it easy to write sequential asynchronous code that is readable with `.then()`.
* Makes it easy to write parallel asynchronous code with `Promise.all()`.
* With promises, these scenarios which are present in callbacks-only coding, will not happen:
  * Call the callback too early
  * Call the callback too late (or never)
  * Call the callback too few or too many times
  * Fail to pass along any necessary environment/parameters
  * Swallow any errors/exceptions that may happen

**Cons**

* Slightly more complex code (debatable).
* In older browsers where ES2015 is not supported, you need to load a polyfill in order to use it.

###### References

* https://github.com/getify/You-Dont-Know-JS/blob/master/async%20%26%20performance/ch3.md

[[↑] Back to top](#js-questions)

### What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?

Some examples of languages that compile to JavaScript include CoffeeScript, Elm, ClojureScript, PureScript, and TypeScript.

Advantages:

* Fixes some of the longstanding problems in JavaScript and discourages JavaScript anti-patterns.
* Enables you to write shorter code, by providing some syntactic sugar on top of JavaScript, which I think ES5 lacks, but ES2015 is awesome.
* Static types are awesome (in the case of TypeScript) for large projects that need to be maintained over time.

Disadvantages:

* Require a build/compile process as browsers only run JavaScript and your code will need to be compiled into JavaScript before being served to browsers.
* Debugging can be a pain if your source maps do not map nicely to your pre-compiled source.
* Most developers are not familiar with these languages and will need to learn it. There's a ramp up cost involved for your team if you use it for your projects.
* Smaller community (depends on the language), which means resources, tutorials, libraries, and tooling would be harder to find.
* IDE/editor support might be lacking.
* These languages will always be behind the latest JavaScript standard.
* Developers should be cognizant of what their code is being compiled to — because that is what would actually be running, and that is what matters in the end.

Practically, ES2015 has vastly improved JavaScript and made it much nicer to write. I don't really see the need for CoffeeScript these days.

###### References

* https://softwareengineering.stackexchange.com/questions/72569/what-are-the-pros-and-cons-of-coffeescript

[[↑] Back to top](#js-questions)

### What tools and techniques do you use for debugging JavaScript code?

* React and Redux
  * [React Devtools](https://github.com/facebook/react-devtools)
  * [Redux Devtools](https://github.com/gaearon/redux-devtools)
* Vue
  * [Vue Devtools](https://github.com/vuejs/vue-devtools)
* JavaScript
  * [Chrome Devtools](https://hackernoon.com/twelve-fancy-chrome-devtools-tips-dc1e39d10d9d)
  * `debugger` statement
  * Good old `console.log` debugging

###### References

* https://hackernoon.com/twelve-fancy-chrome-devtools-tips-dc1e39d10d9d
* https://raygun.com/blog/javascript-debugging/

[[↑] Back to top](#js-questions)

### What language constructions do you use for iterating over object properties and array items?

For objects:

* `for-in` loops - `for (var property in obj) { console.log(property); }`. However, this will also iterate through its inherited properties, and you will add an `obj.hasOwnProperty(property)` check before using it.
* `Object.keys()` - `Object.keys(obj).forEach(function (property) { ... })`. `Object.keys()` is a static method that will lists all enumerable properties of the object that you pass it.
* `Object.getOwnPropertyNames()` - `Object.getOwnPropertyNames(obj).forEach(function (property) { ... })`. `Object.getOwnPropertyNames()` is a static method that will lists all enumerable and non-enumerable properties of the object that you pass it.

For arrays:

* `for` loops - `for (var i = 0; i < arr.length; i++)`. The common pitfall here is that `var` is in the function scope and not the block scope and most of the time you would want block scoped iterator variable. ES2015 introduces `let` which has block scope and it is recommended to use that instead. So this becomes: `for (let i = 0; i < arr.length; i++)`.
* `forEach` - `arr.forEach(function (el, index) { ... })`. This construct can be more convenient at times because you do not have to use the `index` if all you need is the array elements. There are also the `every` and `some` methods which will allow you to terminate the iteration early.
* `for-of` loops - `for (let elem of arr) { ... }`. ES6 introduces a new loop, the `for-of` loop, that allows you to loop over objects that conform to the [iterable protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#The_iterable_protocol) such as `String`, `Array`, `Map`, `Set`, etc. It combines the advantages of the `for` loop and the `forEach()` method. The advantage of the `for` loop is that you can break from it, and the advantage of `forEach()` is that it is more concise than the `for` loop because you don't need a counter variable. With the `for-of` loop, you get both the ability to break from a loop and a more concise syntax. 

Most of the time, I would prefer the `.forEach` method, but it really depends on what you are trying to do. Before ES6, we used `for` loops when we needed to prematurely terminate the loop using `break`. But now with ES6, we can do that with `for-of` loops. I would use `for` loops when I need even more flexibility, such as incrementing the iterator more than once per loop. 

Also, when using the `for-of` loop, if you need to access both the index and value of each array element, you can do so with the ES6 Array `entries()` method and destructuring:

```
const arr = ['a', 'b', 'c'];

for (let [index, elem] of arr.entries()) { 
  console.log(index, ': ', elem);
}
```

###### References

- http://2ality.com/2015/08/getting-started-es6.html#from-for-to-foreach-to-for-of
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries

[[↑] Back to top](#js-questions)

### Explain the difference between mutable and immutable objects.

* What is an example of an immutable object in JavaScript?
* What are the pros and cons of immutability?
* How can you achieve immutability in your own code?

TODO

[[↑] Back to top](#js-questions)

### Explain the difference between synchronous and asynchronous functions.

Synchronous functions are blocking while asynchronous functions are not. In synchronous functions, statements complete before the next statement is run. In this case, the program is evaluated exactly in order of the statements and execution of the program is paused if one of the statements take a very long time.

Asynchronous functions usually accept a callback as a parameter and execution continue on the next line immediately after the asynchronous function is invoked. The callback is only invoked when the asynchronous operation is complete and the call stack is empty. Heavy duty operations such as loading data from a web server or querying a database should be done asynchronously so that the main thread can continue executing other operations instead of blocking until that long operation to complete (in the case of browsers, the UI will freeze).

[[↑] Back to top](#js-questions)

### What is event loop? What is the difference between call stack and task queue?

The event loop is a single-threaded loop that monitors the call stack and checks if there is any work to be done in the task queue. If the call stack is empty and there are callback functions in the task queue, a function is dequeued and pushed onto the call stack to be executed.

If you haven't already checked out Philip Robert's [talk on the Event Loop](https://2014.jsconf.eu/speakers/philip-roberts-what-the-heck-is-the-event-loop-anyway.html), you should. It is one of the most viewed videos on JavaScript.

###### References

* https://2014.jsconf.eu/speakers/philip-roberts-what-the-heck-is-the-event-loop-anyway.html
* http://theproactiveprogrammer.com/javascript/the-javascript-event-loop-a-stack-and-a-queue/

[[↑] Back to top](#js-questions)

### Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`

The former is a function declaration while the latter is a function expression. The key difference is that function declarations have its body hoisted but the bodies of function expressions are not (they have the same hoisting behavior as variables). For more explanation on hoisting, refer to the question above [on hoisting](#explain-hoisting). If you try to invoke a function expression before it is defined, you will get an `Uncaught TypeError: XXX is not a function` error.

**Function Declaration**

```js
foo(); // 'FOOOOO'
function foo() {
  console.log('FOOOOO');
}
```

**Function Expression**

```js
foo(); // Uncaught TypeError: foo is not a function
var foo = function() {
  console.log('FOOOOO');
};
```

###### References

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function

[[↑] Back to top](#js-questions)

### What are the differences between variables created using `let`, `var` or `const`?

Variables declared using the `var` keyword are scoped to the function in which they are created, or if created outside of any function, to the global object. `let` and `const` are _block scoped_, meaning they are only accessible within the nearest set of curly braces (function, if-else block, or for-loop).

```js
function foo() {
  // All variables are accessible within functions.
  var bar = 'bar';
  let baz = 'baz';
  const qux = 'qux';

  console.log(bar); // bar
  console.log(baz); // baz
  console.log(qux); // qux
}

console.log(bar); // ReferenceError: bar is not defined
console.log(baz); // ReferenceError: baz is not defined
console.log(qux); // ReferenceError: qux is not defined
```

```js
if (true) {
  var bar = 'bar';
  let baz = 'baz';
  const qux = 'qux';
}

// var declared variables are accessible anywhere in the function scope.
console.log(bar); // bar
// let and const defined variables are not accessible outside of the block they were defined in.
console.log(baz); // ReferenceError: baz is not defined
console.log(qux); // ReferenceError: qux is not defined
```

`var` allows variables to be hoisted, meaning they can be referenced in code before they are declared. `let` and `const` will not allow this, instead throwing an error.

```js
console.log(foo); // undefined

var foo = 'foo';

console.log(baz); // ReferenceError: can't access lexical declaration 'baz' before initialization

let baz = 'baz';

console.log(bar); // ReferenceError: can't access lexical declaration 'bar' before initialization

const bar = 'bar';
```

Redeclaring a variable with `var` will not throw an error, but 'let' and 'const' will.

```js
var foo = 'foo';
var foo = 'bar';
console.log(foo); // "bar"

let baz = 'baz';
let baz = 'qux'; // Uncaught SyntaxError: Identifier 'baz' has already been declared
```

`let` and `const` differ in that `let` allows reassigning the variable's value while `const` does not.

```js
// This is fine.
let foo = 'foo';
foo = 'bar';

// This causes an exception.
const baz = 'baz';
baz = 'qux';
```

###### References

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const

[[↑] Back to top](#js-questions)

### What are the differences between ES6 class and ES5 function constructors?

Let's first look at example of each:

```js
// ES5 Function Constructor
function Person(name) {
  this.name = name;
}

// ES6 Class
class Person {
  constructor(name) {
    this.name = name;
  }
}
```

For simple constructors, they look pretty similar.

The main difference in the constructor comes when using inheritance. If we want to create a `Student` class that subclasses `Person` and add a `studentId` field, this is what we have to do in addition to the above.

```js
// ES5 Function Constructor
function Student(name, studentId) {
  // Call constructor of superclass to initialize superclass-derived members.
  Person.call(this, name);

  // Initialize subclass's own members.
  this.studentId = studentId;
}

Student.prototype = Object.create(Person.prototype);
Student.prototype.constructor = Student;

// ES6 Class
class Student extends Person {
  constructor(name, studentId) {
    super(name);
    this.studentId = studentId;
  }
}
```

It's much more verbose to use inheritance in ES5 and the ES6 version is easier to understand and remember.

###### References

* https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance
* https://eli.thegreenplace.net/2013/10/22/classical-inheritance-in-javascript-es5

[[↑] Back to top](#js-questions)

### Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?

One obvious benefit of arrow functions is to simplify the syntax needed to create functions, without a need for the `function` keyword. The `this` within arrow functions is also bound to the enclosing scope which is different compared to regular functions where the `this` is determined by the object calling it. Lexically-scoped `this` is useful when invoking callbacks especially in React components.

[[↑] Back to top](#js-questions)

### What advantage is there for using the arrow syntax for a method in a constructor?

The main advantage of using an arrow function as a method inside a constructor is that the value of `this` gets set at the time of the function creation and can't change after that. So, when the constructor is used to create a new object, `this` will always refer to that object. For example, let's say we have a `Person` constructor that takes a first name as an argument has two methods to `console.log` that name, one as a regular function and one as an arrow function:

```js
const Person = function(firstName) {
  this.firstName = firstName;
  this.sayName1 = function() { console.log(this.firstName); };
  this.sayName2 = () => { console.log(this.firstName); };
};

const john = new Person('John');
const dave = new Person('Dave');

john.sayName1(); // John
john.sayName2(); // John

// The regular function can have its 'this' value changed, but the arrow function cannot
john.sayName1.call(dave); // Dave (because "this" is now the dave object)
john.sayName2.call(dave); // John

john.sayName1.apply(dave); // Dave (because 'this' is now the dave object)
john.sayName2.apply(dave); // John

john.sayName1.bind(dave)(); // Dave (because 'this' is now the dave object)
john.sayName2.bind(dave)(); // John

var sayNameFromWindow1 = john.sayName1;
sayNameFromWindow1(); // undefined (because 'this' is now the window object)

var sayNameFromWindow2 = john.sayName2;
sayNameFromWindow2(); // John
```

The main takeaway here is that `this` can be changed for a normal function, but the context always stays the same for an arrow function. So even if you are passing around your arrow function to different parts of your application, you wouldn't have to worry about the context changing.

This can be particularly helpful in React class components. If you define a class method for something such as a click handler using a normal function, and then you pass that click handler down into a child component as a prop, you will need to also bind `this` in the constructor of the parent component. If you instead use an arrow function, there is no need to also bind "this", as the method will automatically get its "this" value from its enclosing lexical context. (See this article for an excellent demonstration and sample code: https://medium.com/@machnicki/handle-events-in-react-with-arrow-functions-ede88184bbb)

###### References

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions
* https://medium.com/@machnicki/handle-events-in-react-with-arrow-functions-ede88184bbb

[[↑] Back to top](#js-questions)

### What is the definition of a higher-order function?

A higher-order function is any function that takes one or more functions as arguments, which it uses to operate on some data, and/or returns a function as a result. Higher-order functions are meant to abstract some operation that is performed repeatedly. The classic example of this is `map`, which takes an array and a function as arguments. `map` then uses this function to transform each item in the array, returning a new array with the transformed data. Other popular examples in JavaScript are `forEach`, `filter`, and `reduce`. A higher-order function doesn't just need to be manipulating arrays as there are many use cases for returning a function from another function. `Function.prototype.bind` is one such example in JavaScript.

**Map**

Let say we have an array of names which we need to transform each string to uppercase.

```js
const names = ['irish', 'daisy', 'anna'];
```

The imperative way will be as such:

```js
const transformNamesToUppercase = function(names) {
  const results = [];
  for (let i = 0; i < names.length; i++) {
    results.push(names[i].toUpperCase());
  }
  return results;
};
transformNamesToUppercase(names); // ['IRISH', 'DAISY', 'ANNA']
```

Use `.map(transformerFn)` makes the code shorter and more declarative.

```js
const transformNamesToUppercase = function(names) {
  return names.map(name => name.toUpperCase());
};
transformNamesToUppercase(names); // ['IRISH', 'DAISY', 'ANNA']
```

###### References

* https://medium.com/javascript-scene/higher-order-functions-composing-software-5365cf2cbe99
* https://hackernoon.com/effective-functional-javascript-first-class-and-higher-order-functions-713fde8df50a
* https://eloquentjavascript.net/05_higher_order.html

[[↑] Back to top](#js-questions)

### Can you give an example for destructuring an object or an array?

Destructuring is an expression available in ES6 which enables a succinct and convenient way to extract values of Objects or Arrays and place them into distinct variables.

**Array destructuring**

```js
// Variable assignment.
const foo = ['one', 'two', 'three'];

const [one, two, three] = foo;
console.log(one); // "one"
console.log(two); // "two"
console.log(three); // "three"
```

```js
// Swapping variables
let a = 1;
let b = 3;

[a, b] = [b, a];
console.log(a); // 3
console.log(b); // 1
```

**Object destructuring**

```js
// Variable assignment.
const o = { p: 42, q: true };
const { p, q } = o;

console.log(p); // 42
console.log(q); // true
```

###### References

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment
* https://ponyfoo.com/articles/es6-destructuring-in-depth

[[↑] Back to top](#js-questions)

### ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?

Template literals help make it simple to do string interpolation, or to include variables in a string. Before ES2015, it was common to do something like this:

```js
var person = { name: 'Tyler', age: 28 };
console.log('Hi, my name is ' + person.name + ' and I am ' + person.age + ' years old!');
// 'Hi, my name is Tyler and I am 28 years old!'
```

With template literals, you can now create that same output like this instead:

```js
const person = { name: 'Tyler', age: 28 };
console.log(`Hi, my name is ${person.name} and I am ${person.age} years old!`);
// 'Hi, my name is Tyler and I am 28 years old!'
```

Note that you use backticks, not quotes, to indicate that you are using a template literal and that you can insert expressions inside the `${}` placeholders.

A second helpful use case is in creating multi-line strings. Before ES2015, you could create a multi-line string like this:

```js
console.log('This is line one.\nThis is line two.');
// This is line one.
// This is line two.
```

Or if you wanted to break it up into multiple lines in your code so you didn't have to scroll to the right in your text editor to read a long string, you could also write it like this:

```js
console.log('This is line one.\n' +
	'This is line two.');
// This is line one.
// This is line two.
```

Template literals, however, preserve whatever spacing you add to them. For example, to create that same multi-line output that we created above, you can simply do:

```js
console.log(`This is line one.
This is line two.`);
// This is line one.
// This is line two.
```

Another use case of template literals would be to use as a substitute for templating libraries for simple variable interpolations:

```js
const person = { name: 'Tyler', age: 28 };
document.body.innerHTML = `
  <div>
    <p>Name: ${person.name}</p>
    <p>Name: ${person.age}</p>
  </div>
`
```

**Note that your code may be susceptible to XSS by using `.innerHTML`. Sanitize your data before displaying it if it came from a user!**

###### References

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals

[[↑] Back to top](#js-questions)

### Can you give an example of a curry function and why this syntax offers an advantage?

Currying is a pattern where a function with more than one parameter is broken into multiple functions that, when called in series, will accumulate all of the required parameters one at a time. This technique can be useful for making code written in a functional style easier to read and compose. It's important to note that for a function to be curried, it needs to start out as one function, then broken out into a sequence of functions that each accepts one parameter.

```js
function curry(fn) {
  if (fn.length === 0) {
    return fn;
  }

  function _curried(depth, args) {
    return function(newArgument) {
      if (depth - 1 === 0) {
        return fn(...args, newArgument);
      }
      return _curried(depth - 1, [...args, newArgument]);
    };
  }

  return _curried(fn.length, []);
}

function add(a, b) {
  return a + b;
}

var curriedAdd = curry(add);
var addFive = curriedAdd(5);

var result = [0, 1, 2, 3, 4, 5].map(addFive); // [5, 6, 7, 8, 9, 10]
```

###### References

* https://hackernoon.com/currying-in-js-d9ddc64f162e

[[↑] Back to top](#js-questions)

### What are the benefits of using spread syntax and how is it different from rest syntax?

ES6's spread syntax is very useful when coding in a functional paradigm as we can easily create copies of arrays or objects without resorting to `Object.create`, `slice`, or a library function. This language feature is used often in Redux and rx.js projects.

```js
function putDookieInAnyArray(arr) {
  return [...arr, 'dookie'];
}

const result = putDookieInAnyArray(['I', 'really', "don't", 'like']); // ["I", "really", "don't", "like", "dookie"]

const person = {
  name: 'Todd',
  age: 29,
};

const copyOfTodd = { ...person };
```

ES6's rest syntax offers a shorthand for including an arbitrary number of arguments to be passed to a function. It is like an inverse of the spread syntax, taking data and stuffing it into an array rather than unpacking an array of data, and it works in function arguments, as well as in array and object destructuring assignments.

```js
function addFiveToABunchOfNumbers(...numbers) {
  return numbers.map(x => x + 5);
}

const result = addFiveToABunchOfNumbers(4, 5, 6, 7, 8, 9, 10); // [9, 10, 11, 12, 13, 14, 15]

const [a, b, ...rest] = [1, 2, 3, 4]; // a: 1, b: 2, rest: [3, 4]

const { e, f, ...others } = {
  e: 1,
  f: 2,
  g: 3,
  h: 4,
}; // e: 1, f: 2, others: { g: 3, h: 4 }
```

###### References

* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters
* https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment

[[↑] Back to top](#js-questions)

### How can you share code between files?

This depends on the JavaScript environment.

On the client (browser environment), as long as the variables/functions are declared in the global scope (`window`), all scripts can refer to them. Alternatively, adopt the Asynchronous Module Definition (AMD) via RequireJS for a more modular approach.

On the server (Node.js), the common way has been to use CommonJS. Each file is treated as a module and it can export variables and functions by attaching them to the `module.exports` object.

ES2015 defines a module syntax which aims to replace both AMD and CommonJS. This will eventually be supported in both browser and Node environments.

[[↑] Back to top](#js-questions)

###### References

* http://requirejs.org/docs/whyamd.html
* https://nodejs.org/docs/latest/api/modules.html
* http://2ality.com/2014/09/es6-modules-final.html

### Why you might want to create static class members?

Static class members (properties/methods) are not tied to a specific instance of a class and have the same value regardless of which instance is referring to it. Static properties are typically configuration variables and static methods are usually pure utility functions which do not depend on the state of the instance.

###### References

* https://stackoverflow.com/questions/21155438/when-to-use-static-variables-methods-and-when-to-use-instance-variables-methods

[[↑] Back to top](#js-questions)

### Other Answers

* http://flowerszhong.github.io/2013/11/20/javascript-questions.html
