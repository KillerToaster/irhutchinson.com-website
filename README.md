# irhutchinson.com-website
Personal website files

project-root/
├── backend/                           # Server API (Node, Fastify, Express, etc.)
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   └── utils/
│   ├── tests/
│   └── package.json
│
├── frontend-public/                   # Vue app for PUBLIC SITE
│   ├── src/
│   │   ├── modules/
│   │   │   ├── pages/                 # Public pages
│   │   │   ├── components/            # Public-specific components
│   │   │   ├── api/                   # Public API wrappers
│   │   │   └── stores/                # Pinia stores for public site
│   │   ├── shared/                    # UI & utilities shared only within public app
│   │   │   ├── components/
│   │   │   ├── composables/
│   │   │   └── utils/
│   │   ├── router/
│   │   │   └── index.ts
│   │   ├── assets/
│   │   ├── App.vue
│   │   └── main.ts
│   ├── index.html
│   └── package.json
│
├── frontend-admin/                    # Vue app for ADMIN DASHBOARD
│   ├── src/
│   │   ├── modules/
│   │   │   ├── pages/                 # Dashboard pages
│   │   │   ├── components/            # Admin-specific components
│   │   │   ├── api/                   # Admin API wrappers (auth/editing/etc)
│   │   │   └── stores/                # Admin Pinia stores (auth,user,settings)
│   │   ├── shared/
│   │   │   ├── components/
│   │   │   ├── composables/
│   │   │   └── utils/
│   │   ├── router/
│   │   │   └── index.ts
│   │   ├── assets/
│   │   ├── App.vue
│   │   └── main.ts
│   ├── index.html
│   └── package.json
│
├── shared/                            # Code shared across BOTH frontends & backend
│   ├── types/
│   ├── constants/
│   ├── validation/
│   ├── api-schema/                    # DTOs, zod/yup schemas, interfaces
│   └── utils/
│
├── docker/                            # Deployment configs (optional)
│   ├── nginx-public.conf
│   ├── nginx-admin.conf
│   └── docker-compose.yml
│
└── README.md
