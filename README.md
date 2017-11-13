[![Build status](https://travis-ci.org/TherapyChat/time-counter.svg?branch=master)](https://travis-ci.org/TherapyChat/time-counter)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/therapychat/time-counter)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com)

# \<time-counter\>

Web Component to display an incremental timer

Intall:
```bash
bower install -S time-counter
```

Example of use:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="time-counter.html">
    <next-code-block></next-code-block>

    <button id="restart">Restart</button>
    <button id="stop">Stop</button>

    <script>
      var timerElement = document.querySelector('#timer')
      var restartButton = document.querySelector('#restart')
      var stopButton = document.querySelector('#stop')

      var restartTimer = function () {
        timerElement.startDate = Date.now()
      }

      var stopTimer = function () {
        timerElement.startDate = undefined
      }

      restartButton.addEventListener('click', restartTimer)
      stopButton.addEventListener('click', stopTimer)

      restartTimer()
    </script>
  </template>
</custom-element-demo>
```
-->
```html
<time-counter id="timer"></time-counter>
```

## Documentation

Checkout the [webcomponents page](https://www.webcomponents.org/element/therapychat/time-counter).

## Changelog

See [CHANGELOG](./CHANGELOG.md) file.

## Contributing

Please read [CONTRIBUTING](./CONTRIBUTING.md) file to follow good practices.

You will need [NodeJS](https://nodejs.org).

1. Close the repo: `git clone git@github.com:TherapyChat/time-counter.git`
1. Install dependencies: `npm install`
1. Code!
1. Test: `npm test`
1. Create a [Pull Request](https://github.com/therapychat/time-counter/pulls)

### Contributors

- [Alberto Fernandez](https://github.com/AlbertoFdzM)

## License

This project is available under the `Apache License 2.0`. See the [LICENSE](./LICENSE) file for more info.
