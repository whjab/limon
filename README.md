<h1 align="center">
<img src="./public/assets/images/icons8-top-hat-96.png" height="130px">

<b>Hat Lab<b>

</h1>
<p align="center">
Hat Lab is a hacking environment for web testing
</p>

```javascript
const express = require("express")
const app = express()

app.set("view engine", "ejs")

app.get("/", function (req, res) {
  res.render("pages/index")
})

app.get("/sobre", function (req, res) {
  res.render("pages/about")
})

app.listen(8080)
console.log("Rodando")
```

> Version 1
