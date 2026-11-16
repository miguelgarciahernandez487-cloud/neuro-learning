# neuro-learning

Mis notebooks de práctica de neuroingeniería.

## Contenido

- `01_numpy_arrays.ipynb`: ejercicios de arreglos con NumPy (dtypes, broadcasting, operaciones por eje, normalización de columnas y una función de resumen estadístico).
- `02_senal_fft.ipynb`: genera una señal con dos tonos más ruido, calcula su espectro con la FFT (`rfft` y `rfftfreq`) e identifica las dos frecuencias dominantes.

## Cómo correrlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/miguelgarciahernandez487-cloud/neuro-learning.git
   cd neuro-learning
   ```
2. Crea el entorno con conda:
   ```bash
   conda env create -f environment.yml
   ```
3. Actívalo (usa el nombre que aparece en la primera línea de `environment.yml`):
   ```bash
   conda activate neuro
   ```
4. Abre Jupyter y corre los notebooks en orden:
   ```bash
   jupyter notebook
   ```

## Qué no se sube a Git (.gitignore)

- `.ipynb_checkpoints/`: copias automáticas que Jupyter genera solo; no aportan nada al historial y solo ensucian los commits.
- `__pycache__/`: archivos compilados que Python genera al ejecutar código; se regeneran solos.
- `data/`: los datos suelen pesar mucho y GitHub no está hecho para guardarlos.
- `.env`: guarda contraseñas y tokens, y nunca deben subirse a GitHub.