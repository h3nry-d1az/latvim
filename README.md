Latino + Vim == latvim
======================

Este plugin es simplemente una extensión para el ya conocido
editor de código **Vim** para editar códio **Latino**. Ciertamente, este
plugin está construido sobre la extensión
[vim-latino](https://github.com/primitivorm/vim-latino), creada por
[Primitivo R. Montero](https://github.com/primitivorm), con ligeras
variaciones en su contenido, principalmente en la detección
de archivos de código **Latino**, donde la extensión de Primitivo fallaba.

### Instalación
Si usted se encuentra trabajando con el manejador de extensiones de **Vim**
**vim-plug**, añada las siguientes líneas de código a su archivo de configuración
de **Vim**, probablemente `.vimrc` si se encuentra en un entorno **UNIX** o `_vimrc`
si, por el contrario, se encuentra en **MS-Windows**:
```vim
call plug#begin('tu-directorio-de-extensiones')
    Plug 'h3nry-d1az/latvim'
call plug#end
```
