# Python_chat_app
Projeto para a cadeira de Infraestrutura de Comunicação ministrada pelo professor Petrônio. CESAR School.

## Para rodar o projeto

Primeiro, baixe as dependências do python através do requirements.txt:
``` sh
$ pip install -r requirements.txt
```

Depois rode o projeto:
``` sh
$ python chatup.py
```
Agora o projeto já está rodando e, por padrão, começara em: http://127.0.0.1:5000/

Para que o teste de comunicação entre mais de 1 cliente aconteça, abra 2 ou mais abas de navegador no localhost (http://127.0.0.1:5000/) e interaja entre elas.

Todo log de conexão será impresso no terminal durante a execução do código. Nesse log existe o registro de todas as mensagens trocadas e toda vez que uma nova conexão é estabelecida, o terminal informe em qual porta o novo cliente está conectado.
