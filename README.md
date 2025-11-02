# 🛍️ BEWEAR E-commerce Full Stack

## [Link para o Projeto ao Vivo](https://bewear-seven.vercel.app/) | [Meu Perfil no GitHub](https://github.com/Marcosvf23)

## 🌟 Visão Geral do Projeto

O **BEWEAR** é uma plataforma de e-commerce moderna e completa, desenvolvida como projeto final do **Bootcamp Full Stack Club com o Felipe Rocha**.

O objetivo foi criar uma aplicação robusta e pronta para produção, aplicando as mais recentes boas práticas de arquitetura, tipagem estática e acessibilidade, utilizando uma stack de tecnologias de ponta.

---

## ✨ Principais Funcionalidades

| Ícone | Funcionalidade | Descrição |
| :---: | :--- | :--- |
| 🛒 | **Carrinho Dinâmico** | Adição e remoção de produtos em tempo real e atualização de totais. |
| 💳 | **Pagamentos Seguros** | Integração completa com **Stripe** para processamento seguro de transações. |
| 📦 | **Gestão de Pedidos** | Sistema completo para acompanhamento e histórico de pedidos. |
| 🏠 | **Cadastro de Endereços** | Possibilidade de cadastrar múltiplos endereços de entrega para o usuário. |
| 📱 | **Design Responsivo** | Interface adaptável a qualquer dispositivo (Mobile First). |
| 🔒 | **Autenticação Moderna** | Login e registro seguros via Google OAuth e Better Auth. |

---

## 🚀 Stack de Tecnologia

Este projeto foi um mergulho profundo nas seguintes tecnologias e bibliotecas:

### Frontend
* **Next.js 15:** Framework React com Server Components para melhor performance e SEO.
* **React 19:** Biblioteca principal para construção da interface de usuário.
* **TypeScript:** Garantindo tipagem estática, escalabilidade e menos erros em tempo de execução.
* **Tailwind CSS:** Framework de utilitários para estilização rápida e responsiva.
* **Radix UI:** Biblioteca de componentes acessíveis e sem estilo.
* **TanStack Query (React Query):** Para gerenciamento eficiente de estado assíncrono (cache, sincronização de dados).

### Backend & Banco de Dados
* **PostgreSQL:** Banco de dados relacional confiável e robusto.
* **Drizzle ORM:** ORM TypeScript-first que permite tipagem completa do banco de dados ao código.
* **NextAuth (ou Better Auth):** Camada de autenticação para Next.js.

### Serviços e Integrações
* **Stripe:** Gateway de pagamento líder de mercado.
* **Google OAuth:** Autenticação via Google.
* **Zod & React Hook Form:** Para validação de *schema* e gerenciamento de formulários complexos.

---

## 🧠 O Que Aprendi e Pratiquei

* **Arquitetura Escalável:** Organização do código e separação de responsabilidades (Clean Code).
* **Tipagem Forte:** Uso rigoroso de TypeScript e Drizzle ORM para garantir segurança de ponta a ponta.
* **Performance:** Otimização de dados com TanStack Query e renderização híbrida com Next.js.
* **Acessibilidade (A11y):** Uso de Radix UI para construir componentes que seguem as diretrizes de acessibilidade.
* **Integração de Serviços:** Configuração e uso de APIs externas como Stripe e Google Auth.

---

## 🛠️ Como Executar o Projeto Localmente

Para rodar o BEWEAR em sua máquina, siga os passos abaixo:

### Pré-requisitos
* Node.js (versão recomendada 18+)
* pnpm (ou npm/yarn, se preferir)
* Conta no PostgreSQL e chaves de API do Stripe e Google OAuth.

### 1. Clonar o Repositório
```bash
git clone [https://github.com/Marcosvf23/Bewear.git](https://github.com/Marcosvf23/Bewear.git)
cd Bewear
```

2. Instalar Dependências
```bash
   pnpm install
# ou npm install / yarn install
```

3. Configurar Variáveis de Ambiente
Crie um arquivo .env.local na raiz do projeto e preencha com as suas credenciais:
```bash
# Variáveis do NextAuth (substitua por suas chaves)
AUTH_SECRET="SeuSegredoAqui"
AUTH_GOOGLE_ID="..."
AUTH_GOOGLE_SECRET="..."

# Conexão com o Banco de Dados (Drizzle)
DATABASE_URL="postgresql://user:password@host:port/database"

# Chaves do Stripe
STRIPE_SECRET_KEY="sk_live_..."
STRIPE_PUBLIC_KEY="pk_live_..."
# Webhook (configurar no Stripe CLI para desenvolvimento)
STRIPE_WEBHOOK_SECRET="whsec_..."
```

4. Rodar Migrações do Banco de Dados
Certifique-se de que o seu banco de dados PostgreSQL está rodando e use o Drizzle para aplicar o schema:
```bash
pnpm run db:push
# Este comando aplica as migrações definidas pelo Drizzle ao seu DB.

```
5. Iniciar a Aplicação
```bash
pnpm run dev
#ou npm run dev / yarn dev
```
O projeto estará acessível em http://localhost:3000.

## 🤝 Contato

Sinta-se à vontade para entrar em contato ou se conectar!

* **Marcos Fernandes**
* **[LinkedIn](https://www.linkedin.com/in/marcosvf23/)**
* **[GitHub](https://github.com/Marcosvf23)**

---
