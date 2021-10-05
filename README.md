
<h1 align="center"><img width="300px" alt="Sass" src="https://rawgit.com/sass/sass-site/main/source/assets/img/logos/logo.svg" /></h1>

<div align="center">
<!-- icones de observação -->
:package: Nova funcionalidade 
:up: Atualização 
:lady_beetle: Correção de bug 
:checkered_flag: Release 
 </div>
</div>
</br>

```sh
$text-color:orange;
    @mixin box-shadow($color) {
        box-shadow: 3px 3px 4px 1px $color
    }

@mixin text-effect($val) {
        @if $val==danger {
            color: red;
        }
        @else if$val==alert {
            color: yellow;
        }
        @else {
            color: black;
        }
    }

```

[Blog Sass](https://sass-lang.com)
