# DevFlash
# 🚀 DevFlash

**DevFlash** é uma plataforma web de flashcards inteligentes para estudo de programação, baseada em repetição espaçada com o algoritmo SM-2.

## 🎯 Objetivo

Ajudar estudantes e iniciantes em programação a aprender de forma eficiente e duradoura, revisando conceitos com flashcards interativos e acompanhamento de progresso.

## 🧠 Funcionalidades

- ✅ Autenticação de usuário (email/senha)
- ✅ CRUD de flashcards (com texto e código)
- ✅ Algoritmo SM-2 para revisão espaçada
- ✅ Interface de estudo com avaliação de confiança
- ✅ Dashboard com decks e cards pendentes
- ✅ Dark Mode 🌙

### ⚡ Diferencial (Versão Estendida)

Você pode escolher um dos diferenciais abaixo para a versão completa:

- 🧪 **Avaliação de Código** (via API Piston): verifica se o código do usuário retorna os resultados esperados.
- 🕹️ **Gamificação**: sistema de XP, streaks, badges simples.

## 🖥️ Tecnologias

| Área           | Tecnologia         |
|----------------|--------------------|
| Frontend       | Next.js (Pages Router) |
| Estilização    | Tailwind CSS |
| Backend/API    | Next.js API Routes |
| Banco de Dados | Prisma + SQLite |
| Autenticação   | NextAuth.js |
| Hospedagem     | Vercel |

---

## 📦 Instalação Local

1. **Clone o repositório**

```bash
git clone https://github.com/seu-usuario/devflash.git
cd devflash
```

2. **Instale as dependências**

```bash
npm install
```

3. **Configure variáveis de ambiente**

Crie um arquivo `.env.local` com as seguintes variáveis:

```env
DATABASE_URL="file:./dev.db"
NEXTAUTH_SECRET=algumasecreta
NEXTAUTH_URL=http://localhost:3000
```

4. **Crie o banco de dados**

```bash
npx prisma migrate dev --name init
```

5. **Rode o projeto**

```bash
npm run dev
```

---

## 🗓️ Cronograma do Projeto

| Mês | Entregas |
|-----|----------|
| 1   | MVP com flashcards e SM-2 |
| 2   | Suporte a código + dark mode |
| 3   | Gamificação ou Avaliação de Código |
| 4-7 | Refino, exportação de decks, estatísticas e entrega final |

---

## 📁 Estrutura de Pastas (Resumo)

```
/pages          → Páginas da aplicação (Next.js)
/components     → Componentes reutilizáveis
/styles         → Estilizações (Tailwind)
/lib            → Utilitários e helpers (ex: algoritmo SM-2)
/prisma         → Schema do banco de dados
```

---

## ✨ Créditos e Inspiração

Este projeto foi idealizado como solução educacional para estudantes de programação.  
Inspirado em plataformas como Anki, Codewars, LeetCode e Memrise.

---

## 📄 Licença

MIT License © 2025 Hellen Barbosa
