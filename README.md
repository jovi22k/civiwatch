# civiwatch
trabalho civicwatch
# 🏛️ CivicWatch

CivicWatch é uma plataforma web simples que conecta cidadãos às decisões políticas. O projeto permite visualizar políticos e propostas, salvar favoritos, participar da comunidade com comentários e gerenciar um perfil pessoal.

## 📋 Funcionalidades

- Login e cadastro de usuários
- Listagem de políticos e propostas em tramitação
- Botão para salvar propostas e políticos
- Página de comunidade com comentários
- Perfil com edição e logout

## ⚙️ Tecnologias utilizadas

- Node.js
- Express
- MySQL
- EJS
- CSS

## 📦 Pré-requisitos

- Node.js (v16 ou superior)
- MySQL Server
- npm (gerenciador de pacotes)

## 🚀 Como rodar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/civicwatch.git
cd civicwatch
```

2. Instale as dependências:

```bash
npm install
```

3. Configure o banco de dados:

- Crie um banco chamado `civicwatch` no MySQL
- Importe o arquivo `civicwatch_completo_populado.sql` via phpMyAdmin ou terminal:

```sql
SOURCE caminho/para/civicwatch_completo_populado.sql;
```

4. Ajuste suas credenciais no arquivo `db.js`:

```js
const connection = mysql.createConnection({
  host: 'localhost',
  user: 'root',
  password: '',
  database: 'civicwatch'
});
```

5. Rode o servidor:

```bash
node app.js
```

6. Acesse no navegador:

```
http://localhost:3000
```

## 👤 Usuário padrão para teste

Use a tela de cadastro para criar um usuário com e-mail e senha.  
Exemplo de login após cadastro: `joao@email.com` / `123`

## 📁 Estrutura principal

```
.
├── public/
├── views/
├── db.js
├── app.js
├── civicwatch_completo_populado.sql
└── README.md
```

## 📄 Licença

Este projeto é livre para fins educacionais e não possui licença oficial.
