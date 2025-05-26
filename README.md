# 🛒 Backend para Sistema de Gestión de Tienda

Este proyecto es el backend de una aplicación web diseñada para la gestión de una tienda, permitiendo la administración de productos, categorías y ventas.

## 📌 Descripción

El sistema proporciona funcionalidades esenciales para la operación de una tienda, incluyendo:

* Gestión de productos y categorías.
* Registro y seguimiento de ventas.
* Interfaz web para interactuar con el sistema.

El backend está desarrollado en **Python** utilizando el framework **Flask**, y se conecta a una base de datos **MySQL**.

## 🛠️ Tecnologías utilizadas

* **Python 3**
* **Flask**
* **MySQL**
* **HTML5**

## 📁 Estructura del proyecto

```

bda-backend/
├── app.py
├── templates/
│   └── index.html
├── schemaTienda.sql
├── LICENSE
└── README.md
```



## 🚀 Instalación y ejecución local

1. Clona el repositorio:

   ```bash
   git clone https://github.com/MargaritaCuervo/bda-backend.git
   ```


2. Accede al directorio del proyecto:

```bash
cd bda-backend
```


3. Crea y activa un entorno virtual:

```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```


4. Instala las dependencias necesarias:

```bash
pip install flask mysql-connector-python
```


5. Configura la base de datos MySQL:

* Crea una base de datos llamada `tienda`.
* Importa el archivo `schemaTienda.sql` para crear las tablas necesarias.

6. Ejecuta la aplicación:

   ```bash
   python app.py
   ```


7. Abre tu navegador y visita `http://localhost:5000` para interactuar con la aplicación.

## 📄 Licencia

Este proyecto se desarrolló con fines académicos y no está destinado para uso comercial.

