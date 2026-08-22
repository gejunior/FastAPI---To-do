# FastAPI - To do 
API que valida usuários e gerencia tarefas armazenando em um banco de dados

## Passos para rodar a aplicação:

1- Entre no visual code/pycharm.
2- Adicone um interpretador e instale as dependências:
```
pip install FastAPI #para a aplicação
pip install sqlalchamy #para banco de dados
pip install passlib #gerar hash
pip install bcrypt==4.0.1 #encriptar a senha
pip install python-multipart #validar o usuario no banco
pip install "python-jose[cryptography]" #gerar token JWT
```
3- Por fim, utilize o código no terminal:

```uvicorn main:app --reload```
