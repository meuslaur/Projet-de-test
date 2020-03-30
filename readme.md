# Titre

test push

**Test en gras**

~~Texte barré~~

[GitHub](https://github.com/)

liste :

* item1
* item2
    * sous item 2
* item 3

![texte alternatif image](https://picsum.photos/id/1/200/300 "Titre, image")

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
