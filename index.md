## Nav #1
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teste FrontEnd Editor</title>
</head>
<body>
  
  <nav>                      
    <a href="##">logo</a>         
    <ul>                           
      <li>Sobre</li>
      <li>Serviços</li>
      <li>Depoimentos</li>
    </ul>
    <a class="button"href="#">Contato</a> 
  </nav>

</body>
</html>
```

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;500&family=Righteous&family=Roboto:wght@300&family=Rowdies&family=Sarala&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-size: 1rem;
  font-family: 'Roboto';
}

a {
  text-decoration: none;
  color: white;
}

.button {
  display: inline-flex;
  justify-content: center;
  align-items: center;

  padding: .5rem 1rem;

  background: #5e4cac;
  border-radius: .4rem;

  color: white;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: black;
  height: 6rem;
  padding: 0 2.4rem;
}

ul {
  display: flex;
  list-style: none;
  color: white;
  gap: 1.5rem;/*substitui o padding da li*/
}
```


## Nav #2
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teste FrontEnd Editor</title>
</head>
<body>
  
  <nav>                      
    <a href="##">logo</a>          
    <ul>                           
      <li>Sobre</li>
      <li>Serviços</li>
      <li>Depoimentos</li>
      <li><a class="button"href="#">Contato</a></li>
    </ul>
     
  </nav>

</body>
</html>
```
```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;500&family=Righteous&family=Roboto:wght@300&family=Rowdies&family=Sarala&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-size: 1rem;
  font-family: 'Roboto';
}

a {
  text-decoration: none;
  color: white;
}

.button {
  display: inline-flex;
  justify-content: center;
  align-items: center;

  padding: .5rem 1rem;

  background: #5e4cac;
  border-radius: .4rem;

  color: white;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: black;
  height: 6rem;
  padding: 0 2.4rem;
}

ul {
  display: flex;
  list-style: none;
  color: white;
  gap: 1.5rem;/*substitui o padding da li*/
  align-items: center;
}
```

## Nav #3
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teste FrontEnd Editor</title>
</head>
<body>
  
  <nav>                      
    <a href="##">logo</a>          
    <ul>                           
      <li>Sobre</li>
      <li>Serviços</li>
      <li>Depoimentos</li>
      <li><a class="button"href="#">Contato</a></li>
    </ul>
     
  </nav>

</body>
</html>

```
```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;500&family=Righteous&family=Roboto:wght@300&family=Rowdies&family=Sarala&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-size: 1rem;
  font-family: 'Roboto';
}

a {
  text-decoration: none;
  color: white;
}

.button {
  display: inline-flex;
  justify-content: center;
  align-items: center;

  padding: .5rem 1rem;

  background: #5e4cac;
  border-radius: .4rem;

  color: white;
}

nav {
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
  align-items: center;
  background-color: black;
  height: 6rem;
  padding: 0 2.4rem;
}

ul {
  display: flex;
  list-style: none;
  color: white;
  gap: 1.5rem;/*substitui o padding da li*/
  align-items: center;
}
```


## Nav #4

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teste FrontEnd Editor</title>
</head>
<body>
  
  <nav>                      
             
    <ul>                           
      <li>Sobre</li>
      <li>Serviços</li>
      <li><a href="##">logo</a></li>
      <li>Depoimentos</li>
      <li><a href="#">Contato</a></li>
    </ul>
     
  </nav>

</body>
</html>
```

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;500&family=Righteous&family=Roboto:wght@300&family=Rowdies&family=Sarala&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  
}

body {
  font-size: 1rem;
  font-family: 'Roboto';
  
}

a {
  text-decoration: none;
  color: white;
}

.button {
  display: inline-flex;
  justify-content: center;
  align-items: center;

  color: white;
}

nav {
  display: flex;
  flex-direction: row-reverse;
  justify-content: center;
  align-items: center;
  background-color: black;
  height: 6rem;
  padding: 0 2.4rem;
  
}

ul {
  display: flex;
  list-style: none;
  color: white;
  gap: 1.5rem;/*substitui o padding da li*/
  align-items: center;
}

```