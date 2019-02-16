### Faker.js
---
https://github.com/Marak/Faker.js

```
curl http://faker.hook.io?property=name.findName&locale=de

npm install .
make test
meteor add practicalmeteor:faker
npm run-script build
npm run-script doc
```

```js
var randomName = faker.name.findName();
var randomEmail = faker.internet.email();
var randomCard = faker.helpers.createCard();

var faker = require('faker');

var randomName = faker.name.findName();
var randomEmail = faker.internet.email();
var randomCard = faker.helpers.createCard();

console.log(faker.fake("{{name.lastName}}, {{name.firstName}} {{name.suffix}}"));

var randomName = faker.name.findName();
var randomEmail = faker.internet.email();
var randomCard = faker.helpers.createCard();

var faker = require('faker/locale/de');

facker.seed(123);

var firstRandom = faker.random.number();

faker.seed(123);

var secondRandom = faker.random.number();

console.log(firstRandom === secondRandom);

facker.setLocale("de");
faker.locale = "de";
```

```
```



