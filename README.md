# MLFlowCapacitacao
Capacitação sobre o uso do MLFlow para versionamento de modelos de ML em experimentações ou em produção


## Passo a passo:

0. Criar um ambiente virtual

```bash
python3 -m venv .venv
```

ou

```bash
conda create -n mlf_env python=3.10
```

1. Instalar as dependências

```bash
pip install -r requirements.txt
```

certifique-se de que o MLFlow está instalado

```bash
pip install mlflow
```

2. Treinar o modelo

Experimente diferentes algoritmos e cobinações de parâmetros, faça feature engineering, etc.

3. Rodar o MLFlow

```bash
mlflow server --host 127.0.0.1 --port 8080
```

4. Versionar o modelo

5. Verificar o modelo versionado no MLFlow UI

```bash