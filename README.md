# Proyecto Limpio Android Evolutivo

Este proyecto es una aplicación Android creada con Kivy y Buildozer, que implementa un modelo evolutivo para generar combinaciones numéricas basado en datos históricos.

## 🧠 Características
- Interfaz construida con Kivy.
- Análisis de datos evolutivos a partir de CSVs históricos.
- Algoritmo mejorado con selección elitista, función de fitness, crossover y mutación.

## 🚀 Requisitos
- Python 3.10
- Git
- Buildozer
- SDK de Android con `build-tools;30.0.3` y `api 30`

## ⚙️ Instrucciones de Compilación

### 1. Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
```

### 2. Instalar dependencias
```bash
sudo apt update
sudo apt install -y python3-pip git zip unzip openjdk-17-jdk python3-setuptools \
    python3-dev build-essential libssl-dev libffi-dev libsqlite3-dev zlib1g-dev \
    libncurses5-dev libreadline-dev libtk8.6 libgdbm-dev libbz2-dev libexpat1-dev liblzma-dev

pip install --upgrade cython virtualenv buildozer
```

### 3. Compilar APK
```bash
buildozer android debug
```

El archivo APK estará en el directorio `bin/`.

## 🧪 Compilación Automática
Este proyecto incluye un flujo de trabajo de GitHub Actions (`.github/workflows/build_android_apk.yml`) que compila automáticamente el APK en cada `push` a `main`.

## 📁 Estructura del proyecto
- `main.py` — lógica de la app y predicción evolutiva.
- `buildozer.spec` — configuración de compilación.
- `.github/workflows/` — automatización CI/CD.

---

© 2025 - Proyecto Evolutivo Android
