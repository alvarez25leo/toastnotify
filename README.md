<h3 align="center">Toastnotify.js</h3>

<p align="center">
  Toastnotify es una biblioteca ligera de notificaciones pure vanilla JS.
  <br>
</p>

<p align="center">
  <a href="http://pixmawebdesign.com/library/toastnotify/">
    <img src="http://www.pixmawebdesign.com/library/toastnotify/img/toastnotify.JPG" alt="toastnotify" style="width: auto; height: auto; max-width: 100%;">
  </a>
</p>


 
 <p >
 <a href="http://pixmawebdesign.com/library/toastnotify/" style="font-size:17px; color: rgb(137, 86, 255);">Documentación y demo</a>
 </p>




## Qué está incluido


```text
toastnotify/
└── dist/
    ├── toastnotify.css 
    └── toastnotify.js
```
## Toastnotify default

```text
    Toastnotify.create({
        text:"Habilita las notificaciones de escritorio para Gmail.",
        duration: 5000
    });
```
## Toastnotify dark

```text
    Toastnotify.create({
        text:"Habilita las notificaciones de escritorio para Gmail.",
        type:'dark',
        callbackOk: function(){
            console.log('Precionado OK');
        },
        callbackCancel:function(){
            console.log('Precionado Cancelado');
        }
    });
```

<a >
 copyright 2019 Leonardo Manuel Alvarez
</a>



