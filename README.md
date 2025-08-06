## Ruff, PyRight, UV, Configuração VS Code e Github

- série de vídeos:
  https://www.youtube.com/watch?v=HuAc85cLRx0&t=1190s

- Github com todas as configurações:
  https://github.com/luizomf/ambiente_python_2025/blob/main/pyproject.toml

## Instalando e configurando projeto com o UV

- Instalando:

```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

- inicializando projeto

```bash
uv init <nome_projeto>
```

- Trocando a versão do Python

```bash
uv python list #Listando as versões Python disponíveis
uv python install <version> #instalando versão Python
uv python pin <version> #Trocando a versão Python do projeto
```

- Verificando a versão Python do meu projeto com o UV

```bash
uv run python --version
```

- Ativando o ambiente virtual

```bash
./.venv/Scripts/activate
```

- Rodando código

```bash
uv run <python_file>
```
