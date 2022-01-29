---
layout: two-cols
---

# Legg til React Router

<br />
<div v-click="1">

Åpne terminalen og skriv inn:
<br/>

<code>npm i react-router-dom@6</code>
</div>

::right::

<div v-click="2">

Åpne <code>/index.js</code>
<br />

```js {all|all|6|10,12|all}
import React from "react";
import ReactDOM from "react-dom";
import "./index.css";
import App from "./App";
import reportWebVitals from "./reportWebVitals";
import { BrowserRouter } from "react-router-dom";

ReactDOM.render(
<React.StrictMode>
    <BrowserRouter>
    <App />
    </BrowserRouter>
</React.StrictMode>,
document.getElementById("root")
);
```
</div>