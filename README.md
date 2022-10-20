# Protocolo Cors

es un estándar de seguridad implementado por los navegadores que permite que los scripts que se ejecutan en los navegadores accedan a recursos ubicados fuera del dominio del navegador.

```
var invocation = new XMLHttpRequest();
var url = 'http://bar.other/resources/public-data/';

function callOtherDomain() {
  if(invocation) {
    invocation.open('GET', url, true);
    invocation.onreadystatechange = handler;
    invocation.send();
  }
}
```

# 

