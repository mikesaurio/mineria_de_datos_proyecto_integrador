# 📊 Proyecto de Minería de Datos con Machine Learning y RAG

## 🧩 Requisitos previos

Asegúrate de tener instalado:

* Python 3.9 o superior
* pip (gestor de paquetes de Python)

---

## 🟢 1. Crear entorno virtual (venv)

### En Windows:

```bash
python -m venv venv
```

Activar entorno:

```bash
venv\Scripts\activate
```

---

### En Mac / Linux:

```bash
python3 -m venv venv
```

Activar entorno:

```bash
source venv/bin/activate
```

---

## 🟢 2. Instalar dependencias

Una vez activado el entorno virtual, instala las librerías necesarias:

```bash
pip install -r requirements.txt
```

---

## 🟢 3. Ejecutar el proyecto

Dependiendo del componente:

### Notebook (Jupyter / VSCode)

Abrir y ejecutar el archivo `.ipynb`


---

### RAG con Ollama

Asegúrate de tener instalado **Ollama** y ejecutar:

```bash
ollama run llama3
```

---

## 🔴 4. Desactivar entorno virtual

Cuando termines:

```bash
deactivate
```

---

## 📦 Notas

* El archivo `requirements.txt` contiene todas las dependencias necesarias para reproducir el entorno.
* Se recomienda usar entornos virtuales para evitar conflictos entre proyectos.

---

## 🚀 Reproducibilidad

Para ejecutar este proyecto en otra máquina:

1. Clonar el repositorio
2. Crear entorno virtual
3. Instalar dependencias
4. Ejecutar notebooks o aplicación

