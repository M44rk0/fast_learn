# 📚 Fast API Learn

> 🎯 **Repositório de Estudos**: Este projeto é um laboratório prático dedicado ao aprendizado, estudo e experimentação contínua com **FastAPI** e as melhores práticas do ecossistema Python.

---

## 📌 Sobre o Projeto

O objetivo principal deste repositório é registrar e consolidar a minha jornada de estudos com **FastAPI**, abrangendo desde conceitos fundamentais de rotas e validações até testes automatizados, padronização de código e automação de tarefas.

---

## 🛠️ Tecnologias Utilizadas

- **[Python 3.13](https://www.python.org/)**
- **[FastAPI](https://fastapi.tiangolo.com/)** - Framework web moderno para construção de APIs
- **[Poetry](https://python-poetry.org/)** - Gerenciador de dependências e ambientes virtuais
- **[PoeThePoet](https://github.com/nat-n/poethepoet)** - Task runner para automação de comandos
- **[Ruff](https://docs.astral.sh/ruff/)** - Linter e formatador de código ultrarrápido
- **[Pytest](https://docs.pytest.org/)** - Suíte de testes automatizados e cobertura (`pytest-cov`)

---

## 🚀 Como Executar o Projeto

### 1. Instalar as dependências
```bash
poetry install
```

### 2. Ativar o ambiente virtual (opcional)
```bash
poetry shell
```

### 3. Iniciar o servidor de desenvolvimento
```bash
poetry start
```

Acesse a aplicação em `http://127.0.0.1:8000` e a documentação Swagger interativa em `http://127.0.0.1:8000/docs`.

---

## 🧰 Atalhos de Tarefas (Poe Tasks)

| Comando | Descrição |
| :--- | :--- |
| `poetry start` | Roda a aplicação FastAPI em modo de desenvolvimento |
| `poetry test` | Executa os testes automatizados e gera relatório de cobertura HTML |
| `poetry lint` | Verifica o código com o linter Ruff |
| `poetry format` | Formata e corrige o código automaticamente com o Ruff |
