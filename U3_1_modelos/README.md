# U2_1 Modelos

Proyecto de la Unidad 2 de Tópicos de Big Data: modelos.

## Estructura del proyecto

```
U2_1_modelos/
├── .venv/                          ← Entorno virtual local (NO se sube a GitHub)
├── data/
│   ├── raw/                        ← Datos originales
│   └── processed/                  ← Datos transformados
├── notebooks/                      ← Jupyter Notebooks
├── src/                            ← Código Python reutilizable
├── .gitignore                      ← Archivos/carpetas que Git debe ignorar
├── README.md                       ← Documentación del proyecto
└── requirements.txt                ← Dependencias Python
```

## Configuración del entorno

1. Crear el entorno virtual (o reutilizar el de `U1_1_probabilidad_estadistica`, ya que `.venv/` no se sube a GitHub y puede compartirse entre carpetas del curso):

   ```bash
   python -m venv .venv
   ```

2. Activar el entorno virtual:

   - Windows (PowerShell):
     ```powershell
     .venv\Scripts\Activate.ps1
     ```
   - Windows (cmd):
     ```cmd
     .venv\Scripts\activate.bat
     ```
   - Git Bash / Linux / macOS:
     ```bash
     source .venv/Scripts/activate
     ```

3. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

4. Lanzar Jupyter Notebook:

   ```bash
   jupyter notebook notebooks/
   ```
