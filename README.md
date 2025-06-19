# Práctico de Ingeniería de Software: Git + Docker

Este proyecto es parte de un trabajo práctico para repasar conceptos de Git y Docker. Consiste en una pequeña app Node.js que imprime información del sistema operativo desde un contenedor Docker.

##  Estructura del proyecto

```
.
├── Dockerfile
├── index.js
├── package.json
└── .gitignore
```

##  Cómo ejecutar el proyecto en Docker

### 1. Cloná este repositorio

```bash
git clone https://github.com/YCastEmm/practica-git-docker
```


---

### 2. Construí la imagen Docker

```bash
docker build -t practica-node .
```

Esto crea una imagen llamada `practica-node` usando el `Dockerfile` incluido.

---

### 3. Ejecutá el contenedor

```bash
docker run practica-node
```

Vas a ver por consola información como:

```
🚀 Mensaje ejecutándose desde dentro de Docker
📅 Fecha actual: 7/6/2025 18:20:03
💻 Sistema operativo: Linux 5.15.0-105-generic
🧠 Memoria libre: 134.32 MB
👤 Usuario actual: root
```



## ✅ Entregable

- [x] Proyecto subido a un repositorio 
- [x] Dockerfile 
- [x] README con instrucciones

---
