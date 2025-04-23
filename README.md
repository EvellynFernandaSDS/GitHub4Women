
```markdown
# 🌱 EcoTasks – Gerenciador Sustentável de Tarefas

O **EcoTasks** é uma aplicação web que ajuda pessoas a organizarem suas tarefas diárias enquanto promove práticas sustentáveis. A cada tarefa concluída, o usuário ganha pontos verdes que podem ser trocados por dicas ecológicas, desafios ou metas ambientais.

---

## 🚀 Tecnologias Utilizadas

- 🖥️ **Front-end:** React.js + Vite
- 🎯 **Back-end:** Node.js + Express
- 🗃️ **Banco de Dados:** MongoDB
- 🎨 **Estilização:** TailwindCSS
- 🔒 **Autenticação:** JWT
- 🌐 **API externa:** OpenWeatherMap (para mostrar clima local e sugerir ações sustentáveis)

---

## 📁 Estrutura de Pastas

```bash
/
├── client/              # Front-end (React)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
├── server/              # Back-end (Node)
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── index.js
├── .gitignore
├── package.json
└── README.md
```

---

## 🧪 Como Rodar o Projeto

### Pré-requisitos

- Node.js
- MongoDB
- Git

### Passo a passo

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/ecotasks.git

# Acesse a pasta do servidor e instale as dependências
cd ecotasks/server
npm install

# Inicie o servidor
npm run dev

# Em outro terminal, vá para o front-end
cd ../client
npm install

# Rode o front-end
npm run dev
```

---

## ✅ Funcionalidades

- [x] Cadastro e login de usuários
- [x] Adição, edição e exclusão de tarefas
- [x] Sistema de pontos verdes
- [x] Ranking de usuários
- [x] Dicas ecológicas baseadas no clima local
- [ ] Notificações via e-mail (em desenvolvimento)

---

## 📌 Melhorias Futuras

- [ ] Modo escuro
- [ ] Compartilhamento de metas com amigos
- [ ] App mobile com React Native

---

## 🤝 Contribuição

1. Faça um fork
2. Crie uma nova branch: `git checkout -b feature/sua-feature`
3. Commit suas mudanças: `git commit -m 'feat: adiciona nova funcionalidade'`
4. Push para sua branch: `git push origin feature/sua-feature`
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

## 🌟 Agradecimentos

Este projeto foi inspirado por iniciativas sustentáveis e aplicativos de gamificação de tarefas como Habitica.
```
