# MenuFlow — Sistema de gestão para restaurantes

Aplicação full stack baseada no documento de mockups da Atividade 5.

## Inclui
- Front-end responsivo em HTML, CSS e JavaScript.
- API back-end em Python com FastAPI.
- Banco de dados SQLite criado automaticamente.
- Login demonstrativo.
- Visão geral, cardápio digital, estoque, equipe, relatórios, pagamentos e produção da cozinha.
- Dados iniciais de demonstração para facilitar a apresentação.

## Como executar
Requer Python 3.10 ou superior.

1. Abra um terminal na pasta `backend`.
2. Crie e ative um ambiente virtual (opcional, recomendado):
   - Windows: `python -m venv .venv` e `.venv\\Scripts\\activate`
   - Linux/macOS: `python3 -m venv .venv` e `source .venv/bin/activate`
3. Instale as dependências:
   `pip install -r requirements.txt`
4. Inicie a aplicação:
   `uvicorn main:app --reload`
5. Acesse `http://127.0.0.1:8000`.

Login de demonstração:
- Usuário: `admin`
- Senha: `123456`

Documentação interativa da API: `http://127.0.0.1:8000/docs`

## Observações
- O banco `menuflow.db` será criado automaticamente em `backend/`.
- Os dados de exemplo são locais e podem ser alterados pela interface.
- O login é apenas demonstrativo para atividade acadêmica. Antes de usar em produção, implemente autenticação real, senhas com hash, controle de permissões, HTTPS, backups e validação de dados mais rigorosa.
