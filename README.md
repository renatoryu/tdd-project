# Projeto de Gerenciamento de Produtos

Este é um projeto de exemplo para gerenciamento de produtos, desenvolvido utilizando Test-Driven Development (TDD). Ele inclui operações CRUD (Create, Read, Update, Delete) para produtos, com testes abrangentes para garantir a qualidade do código. Desenvolvido em parceria com a [DIO](https://www.dio.me/)


## Instalação

Para instalar o projeto, siga os passos abaixo:

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

## Configuração

Antes de executar o projeto, configure as variáveis de ambiente necessárias. Crie um arquivo `.env` na raiz do projeto e adicione as seguintes configurações:

```env
DATABASE_URL=sqlite:///./test.db
```

Ajuste conforme necessário para sua configuração de banco de dados e outras variáveis.

## Executando o Projeto

Para iniciar o servidor, utilize o seguinte comando:

```bash
uvicorn app.main:app --reload
```

O servidor estará disponível em `http://127.0.0.1:8000`.
