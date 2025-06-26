my-next-app/
├── public/                     # Static assets (images, fonts, etc.)
├── src/
│   ├── app/                    # App directory (Next.js 13+ routing)
│   │   ├── (routes)/           # Pages like home, about, dashboard etc.
│   │   ├── layout.tsx         # Root layout
│   │   ├── globals.css        # Global styles
│   │   └── page.tsx           # Entry (if needed)
│   │
│   ├── components/            # Reusable UI components
│   │   ├── ui/                # Button, Card, Modal, etc.
│   │   ├── layout/            # Header, Footer, Sidebar
│   │   └── shared/            # Icons, Loaders, Skeletons
│   │
│   ├── features/              # Feature-based structure (domain logic)
│   │   ├── auth/              # Login, Register, forgot-password
│   │   ├── user/              # User profile, settings
│   │   └── blog/              # Blog listing, detail, editor
│   │
│   ├── lib/                   # Utility functions, custom hooks
│   │   ├── hooks/             # useAuth, useDebounce etc.
│   │   ├── utils/             # formatDate, classNames, etc.
│   │   ├── api/               # API helper functions (fetchers, axios, etc.)
│   │   └── validators/        # zod or yup schema validators
│   │
│   ├── services/              # API services (e.g., auth.service.ts)
│   │
│   ├── types/                 # Global TypeScript types & interfaces
│   │
│   ├── constants/             # Global constants (routes, regex, enums)
│   │
│   ├── config/                # Environment configs (axios config, app settings)
│   │
│   ├── store/                 # State management (RTK, Zustand, etc.)
│   │
│   └── middleware.ts         # Next middleware (auth, logging, etc.)
│
├── .env.local                 # Local env variables
├── next.config.js             # Next.js configuration
├── tailwind.config.ts         # Tailwind config (if using)
├── tsconfig.json              # TypeScript config
└── package.json
