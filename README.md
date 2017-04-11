# test coverage for  [learnyounode (v3.5.10)](https://github.com/workshopper/learnyounode#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-learnyounode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-learnyounode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-learnyounode.svg)](https://travis-ci.org/npmtest/node-npmtest-learnyounode)
#### Learn You The Node.js For Much Win! An intro to Node.js via a set of self-guided workshops.

[![NPM](https://nodei.co/npm/learnyounode.png?downloads=true)](https://www.npmjs.com/package/learnyounode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-learnyounode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-learnyounode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-learnyounode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-learnyounode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-learnyounode/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-learnyounode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-learnyounode/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-learnyounode/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-learnyounode/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-learnyounode/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-learnyounode%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-learnyounode/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-learnyounode/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-learnyounode%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-learnyounode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-learnyounode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-learnyounode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rod Vagg",
        "email": "rod@vagg.org",
        "url": "https://github.com/rvagg"
    },
    "bin": {
        "learnyounode": "./bin/learnyounode"
    },
    "bugs": {
        "url": "https://github.com/workshopper/learnyounode/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "email": "r@va.gg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "Andrey Sidorov",
            "email": "sidorares@yandex.ru",
            "url": "https://github.com/sidorares"
        },
        {
            "name": "Julián Duque",
            "email": "julianduquej@gmail.com",
            "url": "https://github.com/julianduque"
        },
        {
            "name": "Lars-Magnus Skog",
            "email": "lars.magnus.skog@gmail.com",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "Tim Inman",
            "email": "tim.inman@gmail.com",
            "url": "https://github.com/thehack"
        },
        {
            "name": "Dan Flettre",
            "email": "fletd01@yahoo.com",
            "url": "https://github.com/Flet"
        },
        {
            "name": "Martin Heidegger",
            "email": "martin.heidegger@gmail.com",
            "url": "https://github.com/martinheidegger"
        },
        {
            "name": "Fred Chien",
            "email": "cfsghost@gmail.com",
            "url": "https://github.com/cfsghost"
        },
        {
            "name": "雨蒼 - Billy",
            "email": "billy3321@gmail.com",
            "url": "https://github.com/billy3321"
        },
        {
            "name": "Leigh Zhu",
            "email": "i@zhuli.me",
            "url": "https://github.com/lisposter"
        },
        {
            "name": "Toshiharu Harada",
            "email": "haradats@gmail.com",
            "url": "https://github.com/haradats"
        },
        {
            "name": "Lucas Fernandes da Costa",
            "email": "fernandesdacostalucas@gmail.com",
            "url": "https://github.com/lucasfcosta"
        },
        {
            "name": "Eric Douglas",
            "email": "eric.douglas.mail@gmail.com",
            "url": "https://github.com/ericdouglas"
        },
        {
            "name": "Alejandro Oviedo",
            "email": "alejandro.oviedo.g@gmail.com",
            "url": "https://github.com/a0viedo"
        },
        {
            "name": "Leonardo Nascimento",
            "email": "leo386386@gmail.com",
            "url": "https://github.com/leonardo386"
        },
        {
            "name": "Christophe Porteneuve",
            "email": "christophe@delicious-insights.com",
            "url": "https://github.com/tdd"
        },
        {
            "name": "Brynn Bateman",
            "url": "https://github.com/brynnb"
        },
        {
            "name": "Chris Contolini",
            "email": "chris@contolini.com",
            "url": "https://github.com/contolini"
        },
        {
            "name": "Jeff Kile",
            "email": "hello@jeffkile.com",
            "url": "https://github.com/jeffkile"
        },
        {
            "name": "Joel Kemp",
            "email": "joel@mrjoelkemp.com",
            "url": "https://github.com/mrjoelkemp"
        },
        {
            "name": "Jonathan Klein",
            "url": "https://github.com/jklein"
        },
        {
            "name": "Justin Noel",
            "url": "https://github.com/calendee"
        },
        {
            "name": "Oli Evans",
            "email": "oli@zilla.org.uk",
            "url": "https://github.com/olizilla"
        },
        {
            "name": "atomizer",
            "email": "danila.gerasimov@gmail.com",
            "url": "https://github.com/atomizer"
        },
        {
            "name": "Yusup Abdullaev",
            "email": "nico.franza@gmail.com",
            "url": "https://github.com/franza"
        },
        {
            "name": "Nazar Gargol",
            "email": "nazargargol@gmail.com",
            "url": "https://github.com/gargol"
        },
        {
            "name": "Takashi Fujita",
            "url": "https://github.com/tgfjt"
        },
        {
            "name": "Ryuta Nakashima",
            "email": "atuyl.jp@gmail.com",
            "url": "https://github.com/AtuyL"
        },
        {
            "name": "Leigh Zhu",
            "email": "i@zhuli.me",
            "url": "https://github.com/lisposter"
        },
        {
            "name": "Eric Douglas",
            "email": "eric.douglas.mail@gmail.com",
            "url": "https://github.com/ericdouglas"
        },
        {
            "name": "Do Minh Hai",
            "url": "https://github.com/dominhhai"
        },
        {
            "name": "Phung Van Tu",
            "email": "tuphungvan@gmail.com",
            "url": "https://github.com/minatu2d"
        },
        {
            "name": "Shim",
            "url": "https://github.com/marocchino"
        },
        {
            "name": "Chayoung You",
            "email": "yous@yous.be",
            "url": "https://github.com/yous"
        },
        {
            "name": "Korneliusz Caputa",
            "email": "helluinster@gmail.com",
            "url": "https://github.com/elkorn"
        },
        {
            "name": "Espen Dalløkken",
            "url": "https://github.com/leftieFriele"
        },
        {
            "name": "Thomas Torp",
            "url": "https://github.com/torsph"
        },
        {
            "name": "Phillip Johnsen",
            "url": "https://github.com/hillipj"
        },
        {
            "name": "Claudio Procida",
            "email": "claudio.procida@gmail.com",
            "url": "https://github.com/claudiopro"
        },
        {
            "name": "Antonio Milesi Bastos",
            "email": "antonio@milesibastos.com",
            "url": "https://github.com/milesibastos"
        },
        {
            "name": "Sagar",
            "url": "https://github.com/sagar"
        },
        {
            "name": "Andrei Korostelev",
            "email": "andrei@korostelev.net",
            "url": "https://github.com/kindkaktus"
        },
        {
            "name": "Trent Oswald",
            "email": "trentoswald@therebelrobot.com",
            "url": "https://github.com/therebelrobot"
        },
        {
            "name": "Marielle Volz",
            "email": "marielle.volz@gmail.com",
            "url": "https://github.com/mvolz"
        },
        {
            "name": "walhs",
            "url": "https://github.com/walhs"
        },
        {
            "name": "Igor Morozov",
            "url": "https://github.com/gogamwar"
        },
        {
            "name": "Robbie Hickey",
            "url": "https://github.com/hodorswit"
        }
    ],
    "dependencies": {
        "after": "~0.8.1",
        "bl": "^1.1.2",
        "boganipsum": "~0.1.0",
        "colors-tmpl": "^1.0.0",
        "combined-stream": "^1.0.5",
        "concat-stream": "^1.5.1",
        "duplexer": "^0.1.1",
        "hyperquest": "^2.0.0",
        "rimraf": "^2.5.4",
        "through": "^2.3.8",
        "through2": "^2.0.1",
        "through2-map": "^3.0.0",
        "workshopper-adventure": "^6.0.0",
        "workshopper-exercise": "^3.0.1",
        "workshopper-wrappedexec": "~0.1.1"
    },
    "description": "Learn You The Node.js For Much Win! An intro to Node.js via a set of self-guided workshops.",
    "devDependencies": {
        "standard": "^8.1.0",
        "standard-version": "^4.0.0",
        "workshopper-adventure-test": "^1.0.4"
    },
    "directories": {},
    "dist": {
        "shasum": "9d7ca83554df0f5b7a2cdbce04abe81a9938c239",
        "tarball": "https://registry.npmjs.org/learnyounode/-/learnyounode-3.5.10.tgz"
    },
    "gitHead": "564e24f9905a9265bbf51f186d69b7c3e791fbf3",
    "homepage": "https://github.com/workshopper/learnyounode#readme",
    "license": "MIT",
    "main": "./learnyounode.js",
    "maintainers": [
        {
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "julianduque",
            "email": "julianduquej@gmail.com"
        },
        {
            "name": "leichtgewicht",
            "email": "mh@leichtgewicht.at"
        }
    ],
    "name": "learnyounode",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/workshopper/learnyounode.git"
    },
    "scripts": {
        "lint": "standard",
        "release": "standard-version",
        "test": "npm run lint && ./node_modules/.bin/workshopper-adventure-test"
    },
    "version": "3.5.10"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
