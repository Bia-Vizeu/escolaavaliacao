# escolaavaliacao

## Sistema de Controle de Turmas e Atividades de Professores

Este projeto tem como objetivo auxiliar professores no gerenciamento de turmas e atividades, permitindo o cadastro, listagem e exclusão de turmas, além do registro e visualização de atividades.

O sistema também inclui autenticação de usuário (login/logout) e foi desenvolvido com foco em simplicidade e organização pedagógica.

## Linguagem de Programação
- Frontend: HTML5, CSS3 e JavaScript
- Backend: Node.js
- Banco de dados: SQL

### Linguagens utilizadas:
- JavaScript
- SQL

## Dependências principais
```
"dependencies": {
  "express": "^4.18.2",
  "cors": "^2.8.5",
  "pg": "^8.11.1",
  "jsonwebtoken": "^9.0.0",
  "bcryptjs": "^2.4.3",
  "dotenv": "^16.0.3"
}
```

## Instalação e Configuração
1. Clonar o repositório
```
git clone https://github.com/Bia-Vizeu/escolaavaliacao.git

cd controle-turmas
```

2.  Instalar dependências
```
npm install
```

3.  Configurar variáveis de ambiente

Crie um arquivo .env na raiz do projeto:

```
PORT=3000

DATABASE_URL=postgres://usuario:senha@localhost:5432/controle_turmas

JWT_SECRET=sua_chave_secreta
```

4. Rodar o servidor backend
```
npm run dev
```

> [!NOTE]
> O servidor será iniciado em http://localhost:3000

#### Diagrama de Casos de Uso (DCU)
<p align="center">
  <img src="./docs/img/DCU.png" alt="Diagrama de Casos de Uso" style="width:80%; height:auto;">
</p>

#### Diagrama entidade relacionamento (DER)
<p align="center">
  <img src="./docs/img/DER.png" alt="Diagrama entidade relacionamento" style="width:80%; height:auto;">
</p>