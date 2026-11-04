# U4_1 Clustering

Proyecto de la Unidad 4 de Tópicos de Big Data: aprendizaje no supervisado (clustering).

## Práctica 4.1 — Segmentación de clientes con K-Means

Agrupamiento de clientes de un distribuidor mayorista según su gasto anual en seis categorías de productos (dataset *Wholesale Customers*, UCI Machine Learning Repository), con una sección de experimentación que cambia `k`, la etiqueta y la semilla. Ver [`notebooks/U4_1_Clustering_Wholesale_Customers.ipynb`](notebooks/U4_1_Clustering_Wholesale_Customers.ipynb).

El notebook lee el CSV desde `data/raw/` (no lo descarga). Si falta, hay que colocar ahí el archivo `Wholesale customers data.csv` de [UCI](https://archive.ics.uci.edu/dataset/292/wholesale+customers).

## Estructura del proyecto

```
U4_1_clustering/
├── .venv/                          ← Entorno virtual local (NO se sube a GitHub)
├── data/
│   ├── raw/                        ← Datos originales
│   │   └── Wholesale customers data.csv
│   └── processed/                  ← Datos transformados
├── notebooks/                      ← Jupyter Notebooks
│   └── U4_1_Clustering_Wholesale_Customers.ipynb
├── src/                            ← Código Python reutilizable
├── .gitignore                      ← Archivos/carpetas que Git debe ignorar
├── README.md                       ← Documentación del proyecto
└── requirements.txt                ← Dependencias Python
```

## Configuración del entorno

1. Crear el entorno virtual (o reutilizar el de otra carpeta del curso, ya que `.venv/` no se sube a GitHub):

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
