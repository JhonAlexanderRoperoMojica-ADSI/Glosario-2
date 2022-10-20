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

## JSON

es un formato de texto totalmente independiente del lenguaje de programación

```
{
  "llave1": "valor1",
  "llave2": "valor2",
  "llave3": "valor3",
  "llave4": 7,
  "llave5": null,
  "favAmigos": ["Kolade", "Nithya", "Dammy", "Jack"],
  "favJugadores": {"uno": "Kante", "dos": "Hazard", "tres": "Didier"}
}
```

