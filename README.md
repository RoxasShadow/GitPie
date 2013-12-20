GitPie
=================================================

Example
=======
```js
$('#canvas').gitPie('https://api.github.com/users/RoxasShadow/repos?per_page=100', 'things/colors.json');
```

```js
beforeSend = function() { alert('loading...'); };
complete   = function() { alert('done'); };
$('#canvas').gitPie('things/repos.json', 'things/colors.json', beforeSend, complete);
```

