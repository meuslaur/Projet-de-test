# Titre
    Application test
    
## Pour commencer

    Version 0.0.1


**Test en gras**

~~Texte barré~~

[GitHub](https://github.com/)

liste :

* item1
* item2
    * sous item 2
* item 3

code :
```
function redim_png () {
    return src('img/icons/*.png')
        .pipe(resizer({
            width: 64,
            height: 64,
            background: 'none',
            imageMagick: true
        }))
        .pipe(dest('dist/icons/64'))
}
```
