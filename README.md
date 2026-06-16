# 🔬 MathLab

Laboratório de matemática portátil com JupyterLab + Python científico.

## Como usar

```bash
# Primeira vez (build)
docker compose up --build

# Demais vezes
docker compose up

# Parar
docker compose down
```

Acesse: http://localhost:8888

## Estrutura

```
mathlab/
├── Dockerfile            # imagem do container
├── docker-compose.yml    # orquestra portas e volumes
├── requirements.txt      # bibliotecas Python
└── notebooks/            # seus notebooks (salvos na máquina)
    └── algebra_linear.ipynb
```

## Bibliotecas incluídas

| Lib | Para que serve |
|-----|----------------|
| NumPy | Arrays, álgebra linear numérica |
| SciPy | Decomposições, EDOs, otimização |
| SymPy | Matemática simbólica exata |
| Matplotlib | Gráficos 2D/3D |
| Plotly | Gráficos interativos |
| Pandas | Dados tabulares |
