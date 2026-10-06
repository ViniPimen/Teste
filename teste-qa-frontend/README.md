# Teste QA — Front-end

Dashboard responsivo para organizar casos de teste, acompanhar status e registrar execuções.

## Rodar localmente
Requisitos: Node.js 18+ e npm.

```bash
npm install
npm run dev
```

Abra a URL local informada pelo Vite (normalmente http://localhost:5173).

## Build de produção
```bash
npm run build
npm run preview
```

## Inclui
- Dashboard com contagem de casos aprovados, falhos e pendentes.
- Busca e filtros por status.
- Cadastro de casos de teste.
- Detalhes e registro de execução de um caso.
- Persistência no localStorage do navegador.

**Importante:** este é apenas o front-end. Ainda não está conectado ao GitHub, a uma API ou a um banco de dados. Os dados ficam no navegador atual.
