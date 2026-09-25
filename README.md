# Proposta_Comercial-Black
proposta-comercial-black-main/
├── app/
│   ├── page.tsx                    → página inicial (pode redirecionar ou ser institucional)
│   ├── proposta/
│   │   └── [codigo]/
│   │       └── page.tsx            → a proposta pública, dinâmica por link único
│   ├── admin/
│   │   ├── login/
│   │   │   └── page.tsx            → tela de login do admin
│   │   └── page.tsx                → painel: criar/editar propostas
│   └── layout.tsx                  → layout raiz (fontes, metadata)
├── components/
│   ├── site/                       → componentes do site público (Hero, Nav, Cards, etc.)
│   └── admin/                      → componentes do painel (formulário, lista de propostas)
├── lib/
│   └── firebase.ts                 → configuração do banco de dados (quando chegarmos lá)
├── public/
│   ├── LOGO_CORUJA.png
│   └── Sala_black.jpg
├── styles/
│   └── globals.css                 → cores da marca como CSS variables (reaproveita o que já temos)
├── package.json
└── next.config.ts