# `03.2` Un componente real

En el ejericio anterior hemos creado nuestro primer componente llamado **PrintHello** y hemos aprendido que podemos usar el componente como una etiqueta HTML.

```jsx
<PrintHello />
```

Ahora, vamos a crear un nuevo componente (funci贸n) llamado **`<BoostrapCard />`** que generar谩 el siguiente HTML:

```jsx
<div class="card m-5">
  <img class="card-img-top" src="../../.learn/assets/Dylan.png?raw=true" alt="Card image cap" />
  <div class="card-body">
    <h5 class="card-title">Bob Dylan</h5>
    <p class="card-text">Bob Dylan (born Robert Allen Zimmerman, May 24, 1941) is an American singer/songwriter, author, and artist who has been an influential figure in popular music and culture for more than five decades.</p>
    <a href="https://en.wikipedia.org/wiki/Bob_Dylan" class="btn btn-primary">Go to wikipedia</a>
  </div>
</div>
```
馃攷
 Este c贸digo HTML est谩 basado en la [Bootstrap Card](https://getbootstrap.com/docs/4.0/components/card/).

## 馃摑 Instrucciones:

1. Por favor, crea una funci贸n llamada `BootstrapCard` que devuelva el c贸digo de la card y usa la funci贸n `ReactDOM.render` para a帽adir `<BootstrapCard />` dentro del sitio web, dentro de `#myDiv`.

## 馃挕 Pista:

* Si no sabes o no recuerdas c贸mo usar `ReactDOM.render`, puedes revisar los ejercicios anteriores.
