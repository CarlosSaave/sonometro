# SONOMETRO ![Status badge](https://img.shields.io/badge/status-in%20progress-yellow)

![sonometro](https://www.pce-instruments.com/colombia/slot/16/artimg/normal/pce-instruments-son%C3%B3metro-pce-322a-5870872_1197921.webp)

> ## CONTENIDO
* [Descripción](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Características](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Tecnologías Utilizadas](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Guia de Inicio Rápido](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Instalación](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Despliegue, Compilacion y Pruebas](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/requirements)
* [Autores y Agradecimientos](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Contribuciones e Historial de Versiones](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [FAQs](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Licencia](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)
* [Referencias](https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md)


## Descripción
✨ Comunicacion Serial a traves del puerto USB con sonómetro PCE-322A apto para medir el ruido en el ámbito de la industria, la salud, la seguridad y el medioambiente. El sonometro incluye una función registro que permite almacenar hasta 32.700 valores. Esto lo convierte en un equipo ideal para registros prolongados. 
Realiza una medición en tiempo real y ver los valores directamente en pantalla. El software ofrece una lectura en forma de tabla y como gráfico. Todos estos datos pueden ser exportados a Excel. 

## Características

- Envia emails
- Realiza lecturas automatizadas
- Exporta documentos en excel

## Tecnologías Utilizadas

La aplicación usa utiliza una serie de proyectos de código abierto para funcionar correctamente bajo:


- [python](https://docs.python.org/) - V3.9
- Markdown-it - Analizador Markdown bien hecho. Rápido y fácil de extender.

#  Guia de Inicio Rapido
## 🚀 Instalación
SONOMETRO requiere Python 3.9 y pip
1- Descargue el instalador del archivo ejecutable de Python 3.9 para Windows x86-64 desde la página de descargas de Python.org.

Ejecute el instalador.
Python Software Foundation ofrece instaladores para Windows que incluyen pip.


Abra su terminal favorito y corra los siguientes comandos:

1. Clona este proyecto.
```sh
git clone https://github.com/CLODESAS/sonometro-pce322a.git
```

2. Ve a la carpeta del proyecto
```sh
cd sonometro-pce322a
```
3. Run the project
In the root directory of project, run below code in terminal

`python manage.py runserver`

En ambiente de produccion solo es necesario ejecutar el .exe

## 🛠 Despliegue, Compilación y Pruebas

Abra su terminal favorito y corra los siguientes comandos en el directorio raiz del proyecto:
1. Instala/actualiza el gestor de paquetes de Python
```sh
python -m pip install --upgrade pip
```

2. Instale requerimientos
En el directorio raiz del proyecto, ejecute el siguiente codigo desde el terminal

`pip install -r requirements.txt`

3. Valida Dependencias y versiones instaladas
```sh
pip list
```
| Package | Version |
| ------ | ------ |
|certifi|            2022.9.24
|colorama|           0.4.6
|numpy|              1.23.4
|pandas|             1.5.1
|pyodbc|             4.0.35
|pywin32|            305
|banistmo_batch_logs|1.0.1

4. Instale otros requerimientos manualmente de ser necesario
```sh
pip install virtualenv
virtualenv -p python3 env
.\env\Scripts\activate
pip install numpy  
pip install pandas
pip install pyodbc
pip install colorama
pip install pywin32
pip install zipfile
```
#### Compilación

(optional):

```sh
test
```

Generando pre-built exe artefacto para distribución:

```sh
pyinstaller
```

Despliege en su Navegardo preferido:
```sh
http://127.0.0.1:8000/
```

## ✨ Autores y Agradecimientos
* A los Ingenieros Jhon Quevedo y Carlos Saavedra.

# FAQs
> Lista de Preguntas y Respuestas
* [Que permisos se requieren para funcionar adecuadamente](https://github.com/microsoft/vscode/wiki/How-to-Contribute#pull-requests)
1) 

* [¿Cuales son los insumos necesarios de entrada?](https://github.com/microsoft/vscode/wiki/How-to-Contribute)

* [¿Cual es la Ruta de Salida de la Conciliación?](https://github.com/microsoft/vscode/wiki/How-to-Contribute#debugging)
## 🧾 Licencia
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
The OWNER License (OWNER)

## Contribuciones e Historial de Versiones

Los Pull requests son bienvenidos. Para cambios importantes, abra una Orden de Cambio primero.

Asegúrese de actualizar las pruebas según corresponda.


| Historial de Versiones | |

| Versión |	Área | Participantes | Observaciones | Fecha |
| 1.0.0 | Ingeniería de Software | Jhon Quevedo | Versión Inicial | 20/03/2023 |









## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

- [Django] - ¡HTML mejorado para aplicaciones web!
- [jQuery] - duh
- SQl

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md>
   [PlGh]: <https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md>
   [PlGd]: <https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md>
   [PlOd]: <https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md>
   [PlMe]: <https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md>
   [PlGa]: <https://dev.azure.com/banistmo/VP%20Servicios%20Corporativos/_git/bipaw0142000-scr-conciliacion-clave-online/README.md>

prueba 