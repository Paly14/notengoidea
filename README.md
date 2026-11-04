# No tengo idea

Base inicial de una página web en español, adaptable a celulares y sin dependencias externas.

## Desarrollo

Requiere Python 3. Desde la carpeta del repositorio:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

El archivo `index.html` contiene la página y sus estilos. Los cambios se ven al recargar el navegador.

## Verificación

Con el servidor en ejecución:

```sh
curl --fail http://127.0.0.1:8000/
```

La respuesta debe incluir el título `No tengo idea`. No hay compilación ni suite de pruebas automatizadas.
