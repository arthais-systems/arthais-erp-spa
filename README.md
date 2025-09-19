# ArthaisERP SPA

## 🎯 Objetivo (MVP)

Entregar a **Single Page Application** do ArthaisERP para o **Fluxo de Caixa**, possibilitando:

- **Lançar transações** (entradas, saídas, investimentos).
- **Visualizar o consolidado** diário/semanal/mensal (gráficos e tabela).
- Consumir os endpoints da API: `/api/ping`, `/transactions`, `/cashflow`.

Stack alvo: **React + Vite + TypeScript + Tailwind**.

## ⚙️ Pré‑requisitos (ambiente local)

- **Git** (2.x+) para versionamento
- **Node.js LTS** (20.x ou 22.x) e **npm** (ou pnpm/yarn, se preferir)
- **API em execução** (por padrão em `http://localhost:8080`)
- Variável de ambiente no projeto:  
  Crie um arquivo `.env.local` com:
  ```env
  VITE_API_URL=http://localhost:8080
  ```
