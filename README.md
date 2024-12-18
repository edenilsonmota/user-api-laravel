# user-api-laravel
Api simples crud para criação de usuario e ligando com autenticação.

## Requisitos
- Docker

## Rodando o projeto
1. Acessar projeto (Dentro do projeto clonado):

```bash
./vendor/bin/sail up
```

2. Criar dependencias do banco:

```bash
./vendor/bin/sail artisan migrate
```

3. Para atualizar o composer bastar colocar o:

```bash
./vendor/bin/sail composer install
```
