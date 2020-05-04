# Tema 'Hámelin' #
### (The 'Hamelin' Theme) ###
![Vista previa](https://i.imgur.com/z4Eh9J6.png)

Tema o plantilla para utilizar con el creador de sitios estáticos [Nikola.](https://getnikola.com/)
Puedes consultar las fuentes del proyecto [aquí.](https://github.com/getnikola/nikola)

El tema 'Hámelin' combina elementos del tema ['hpstr'](https://github.com/getnikola/nikola-themes/tree/master/v7/hpstr), que funciona con **Mako** como motor,
 y de [w3](https://www.w3schools.com/css/css_rwd_templates.asp).

## Instalación ##
La instalación de estos temas o plantillas se hace mediante la configuración del archivo `conf.py` del sitio generado con Nikola:
```python
# Name of the theme to use.
THEME = "hamelin"
```

Por el momento no está soportado el uso de 'bundles', así que:
```python
USE_BUNDLES = False
```

Es necesario poner la carpeta `themes` en el directorio de desarrollo de nuestro sitio (no en la carpeta `output`).

### Modificaciones ###
Las modificaciones de estilos están contenidas en el archivo `custom.css`, disponible en `[mi_sitio]/themes/hamelin/assets/css`

### [Licencia](https://github.com/Darkfoe703/hamelin-theme/blob/pruebas/LICENSE) ###
