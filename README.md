# VR2 Mentoria — Deploy Vercel

## Estrutura
```
vr2-mentoria/
├── public/
│   └── index.html   ← site completo
├── vercel.json      ← config Vercel
└── README.md
```

## Como fazer o deploy

### Opção 1 — Drag & Drop (mais rápido)
1. Acesse **vercel.com/new**
2. Arraste a pasta **inteira** (`vr2-mentoria/`) para a área de upload
3. Clique em **Deploy**
4. Pronto — URL gerada automaticamente

### Opção 2 — GitHub + Vercel
1. Crie repositório no GitHub
2. Faça push desta pasta
3. No Vercel: New Project → Import Git Repository
4. Selecione o repo → Deploy

### Opção 3 — CLI
```bash
npm i -g vercel
cd vr2-mentoria
vercel login
vercel --prod
```

## Domínio personalizado
Após deploy: Vercel Dashboard → Settings → Domains → Add `vr2mentoria.com.br`
