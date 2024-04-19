<h3 align="center">Python Bot</h3>

---

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

Estas son mis primeras APP automatizadoras, egnerare un conjunto de proyectos en el presente con el deseo que tenga un set de bot que me ayude en el día a día

## 🏁 Getting Started <a name = "getting_started"></a>

Por medio de la presente, deseo poner a disponision toda la informacion que recopile del presente.

##### Lista de proyectos
 - browser_autamation_and_web_scraping:
    - scrape_simple_text_with_seleniun

##### browser_autamation_and_web_scraping
Permitira la creacion de ....

### Instalacion
##### Luego de la clonacion del proyecto

```
git clone pryecto
```

##### Identifica el proyecto que deseas acceder
```
cd proyecto_que_deseo
```

##### Genero el entorno virtaul para este
```
python3 -m venv env
```

##### Activacion
```
source env/bin/activate
```

##### En caso de desear desacticar
```
deactivate
```

##### Para validar que los pasos anteriores sean correacto tenemos
```
which python3
```

##### Estas son las librearias que se usan
```
pip install selenium
pip install webdriver_manager
```

##### Guardar instalado en mi archivo de versiones
```
 pip3 freeze > requirements.txt 
```

##### Para tu caso, es solo que apliques este comando y todas las librerias se aplicaran
```
pip3 install -r requirements.txt
```

## 🔧 Running the tests <a name = "tests"></a>

Pasos para poner a correr esta APP

### Ejucutar modo local

```
uvicorn main:app
```

## En caso que deses realizar cambios sin tener que estar deteniendo la APP

```
uvicorn main:app --reload
```

## En caso de necesitar cambiar el puerto de la appla APP

```
uvicorn main:app --reload --port 8080
```

## 🎈 Y la Documentación <a name="usage"></a>

Para hacer uso de la documentacion tenemos
Dependera de donde tiene corriendo la app pero siempre sera el /docs

```
http://127.0.0.1:8080/docs
```

##### Para editar informacion de la documentacion tenemos

```
Por favor, ir al repositorio y buscar "Adicionar informacion para la doc de la APP"
```

## 🚀 Deployment <a name = "deployment"></a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
