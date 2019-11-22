<h3 align="center">Toastnotify.js</h3>

<p align="center">
  Toastnotify es una biblioteca ligera de notificaciones pure vanilla JS.
  <br>
</p>

## Install

```text
npm i toastnotify
```

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
        callbackOk:()=>{
            console.log('Precionado OK');
        },
        callbackCancel:()=>{
            console.log('Precionado Cancelado');
        }
    });
```

<a >
 copyright 2019 Leonardo Manuel Alvarez
</a>



