Mithril Js Simple Application Example

Source: https://mithril.js.org/simple-application.html

What is this?

* A single page web app.
* Makes use of https://rem-rest-api.herokuapp.com/api/users API.
* Just an example to see how the framework works.

Requirements:

* npm

Instructions:
```
npm start
```

Notes:

* MithrilJs uses hyperscript (An alternative to JSX)

Hyperscript Example:
```
    return m("main", [
      m("h1", "Hello world"),
    ])
```

JSX Example:
```
    return (
      <main>
        <h1>Hello world</h1>
      </main>
    )
```


