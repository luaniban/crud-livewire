# CRUD com Livewire

CRUDs de usuários, disciplinas e currículos feitos com Livewire e TallStackUI. O projeto fica na pasta `myapp/`.

## Funcionalidades

- Tabelas com busca e paginação.
- Modais de criar e editar.
- Exclusão de registros.
- Botão para resetar a senha do usuário.
- A tabela se atualiza sozinha depois de criar ou excluir (eventos do Livewire).

## Tecnologias

- Laravel 11, Jetstream e Livewire 3
- TallStackUI e Tailwind CSS
- MySQL

## Como rodar

```bash
cd myapp
composer install
cp .env.example .env
php artisan key:generate
# crie o banco `myapp` no MySQL e confira os dados de acesso no .env
php artisan migrate --seed
npm install
npm run dev
php artisan serve
```
