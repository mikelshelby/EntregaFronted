# html exercises

In this exercises you will have to complete the missing html or remark what should we include. For example:

What is wrong with this HTML?

```html
<customtag>lorem ipsum dolor</customtab>
```

Answer: It is using a key that does not exists.

## Exercise 1

Add what is missing in our html `<head>` tag.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  </head>
  <body>

  </body>
</html>
```

## Exercise 2

This html is not semantic what could we do to improve it.

```html
<div class="main">
  <section>
    <ol>
      <li class="list-item">List item</div>
      <li class="list-item">List item</div>
      <li class="list-item">List item</div>
      <li class="list-item">List item</div>
    </ol>
  </section>
  <section>
    <form class="form">
      <label>description</label>
      <input type="text">
    </form>
  </section>
</div>
```

## Exercise 3

If we want to include two CSS files like `reset.css`, `main.css`, and one javascript file `app.js`. Where should we include it in this html?

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="sylesheet" href="reset.css">
  <link rel="sylesheet" href="main.css">
  <title>Document</title>
</head>
<body>
  <script src="app.js"></script>
</body>
</html>
```

## Exercise 4

We need to improve this html form markup. This form will call and endpoint `/register` with the right method. We also have to include the correct input type and mark all fields as required.

```html
<form action = "/register">
  <div>
    <label>name</label>
    <input required type="text" id="lName" name="lName">
  </div>
  <div>
    <label>surname</label>
    <input required type="text" id="lSurname" name="lSurname">
  </div>
  <div>
    <label>phone</label>
    <input required type="text" id="lPhone" name="lPhone">
  </div>
  <div>
    <label>email</label>
    <input required type="text" id="lEmail" name="lEmail">
  </div>
  <div>
    <label>password</label>
    <input required type="text" id="lPassword" name="lPassword">
  </div>
  <input value="register" type="submit">
</form>
```
