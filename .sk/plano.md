# Plano do projeto: Assistente-Juridico-local

_Gerado pelo Mini SK em 06/10/2026, 22:19:49_

## Resumo

- Arquivos: **116** (1.4 MB)
- Tipo: projeto Node com 1 package.json
- Arquivos por tipo: TSX 71, TypeScript 16, JSON 6, HTML 4, JavaScript 4, PNG 3, YAML 2, Batch 2, .env 1, Git 1, NPMRC 1, Texto 1, CSS 1, Shell 1, Markdown 1, SQL 1
- Dependências diferentes: **111** (94 obrigatórias, 17 só para montar)
- Restos da Replit: **1 arquivo(s)**

## 📦 assistente-juridico — `package.json`


**Comandos (scripts):**

| Comando | O que faz | Executa |
|---|---|---|
| `iniciar` | — | `node scripts/iniciar.mjs` |
| `dev` | Liga o app em modo de teste (atualiza sozinho) | `tsx server/index.ts` |
| `build` | Gera a versão final (pasta dist) | `vite build` |
| `start` | Liga a versão final | `tsx server/index.ts --producao` |
| `checar` | — | `tsc --noEmit` |

**Dependências (o app precisa) — 94:**

| Pacote | Versão | Pra que serve | Tipo |
|---|---|---|---|
| `@electric-sql/pglite` | ^0.3.0 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@google/genai` | ^1.43.0 | IA Gemini | 🤖 IA |
| `@hookform/resolvers` | ^3.10.0 | Liga o formulário às regras do Zod | 🖥 Tela |
| `@jridgewell/trace-mapping` | ^0.3.25 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@radix-ui/react-accordion` | ^1.2.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-alert-dialog` | ^1.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-aspect-ratio` | ^1.1.3 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-avatar` | ^1.1.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-checkbox` | ^1.1.5 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-collapsible` | ^1.1.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-context-menu` | ^2.2.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-dialog` | ^1.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-dropdown-menu` | ^2.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-hover-card` | ^1.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-label` | ^2.1.3 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-menubar` | ^1.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-navigation-menu` | ^1.2.6 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-popover` | ^1.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-progress` | ^1.1.3 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-radio-group` | ^1.2.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-scroll-area` | ^1.2.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-select` | ^2.1.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-separator` | ^1.1.3 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-slider` | ^1.2.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-slot` | ^1.2.0 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-switch` | ^1.1.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-tabs` | ^1.1.4 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-toast` | ^1.2.7 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-toggle` | ^1.1.3 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-toggle-group` | ^1.1.3 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@radix-ui/react-tooltip` | ^1.2.0 | Peça de interface pronta (botão, menu, janela) usada pelo shadcn/ui | 🖥 Tela |
| `@tanstack/react-query` | ^5.60.5 | Busca e guarda dados do servidor nas telas | 🖥 Tela |
| `@tiptap/core` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-color` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-font-family` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-highlight` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-link` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-table` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-table-cell` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-table-header` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-table-row` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-text-align` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-text-style` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/extension-underline` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/pm` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/react` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@tiptap/starter-kit` | ^3.20.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `@types/jsonwebtoken` | ^9.0.10 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/multer` | ^2.0.0 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `adm-zip` | ^0.5.16 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `class-variance-authority` | ^0.7.1 | Variações de botões/estilos (shadcn/ui) | 🎨 Estilo |
| `clsx` | ^2.1.1 | Monta listas de classes CSS | 🎨 Estilo |
| `cmdk` | ^1.1.1 | Caixa de comandos/busca rápida | 🖥 Tela |
| `date-fns` | ^3.6.0 | Datas (formatar, somar dias, prazos) | 🧰 Utilidade |
| `docx` | ^9.5.1 | Cria arquivos Word (.docx) | 🧰 Utilidade |
| `drizzle-orm` | ^0.39.3 | Conversa com o banco de dados (Postgres) | 🛢 Banco |
| `drizzle-zod` | ^0.7.1 | Gera as regras do Zod a partir do banco | 🛢 Banco |
| `embla-carousel-react` | ^8.6.0 | Carrossel de imagens/cartões | 🖥 Tela |
| `express` | ^5.0.1 | Servidor (recebe os pedidos das telas: salvar, IA, banco) | 🗄 Servidor |
| `express-session` | ^1.18.1 | Sessão de login | 🗄 Servidor |
| `framer-motion` | ^11.13.1 | Animações nas telas | 🖥 Tela |
| `html-entities` | ^2.6.0 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `input-otp` | ^1.4.2 | Campo de código (tipo SMS) | 🖥 Tela |
| `jsonwebtoken` | ^9.0.3 | Token de login (JWT) | 🗄 Servidor |
| `lucide-react` | ^0.453.0 | Ícones (desenhos dos botões) | 🖥 Tela |
| `mammoth` | ^1.11.0 | Lê arquivos Word (.docx) | 🧰 Utilidade |
| `memorystore` | ^1.6.7 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `msedge-tts` | >=1.3.4 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `multer` | ^2.0.2 | Recebe arquivos enviados (upload) | 🗄 Servidor |
| `next-themes` | ^0.4.6 | Tema claro/escuro | 🖥 Tela |
| `openai` | ^6.18.0 | IA da OpenAI (ChatGPT) — também serve p/ Groq, OpenRouter | 🤖 IA |
| `p-limit` | ^7.3.0 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `p-retry` | ^7.1.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `passport` | ^0.7.0 | Login | 🗄 Servidor |
| `passport-local` | ^1.0.0 | Login com usuário e senha | 🗄 Servidor |
| `pdf-parse` | ^2.4.5 | Lê texto de PDFs (no servidor) | 🗄 Servidor |
| `pdfjs-dist` | ^5.5.207 | Lê PDFs | 🧰 Utilidade |
| `postcss-selector-parser` | ^7.1.1 | (sem descrição — toque no nome para ver no npm) | ❔ |
| `react` | ^18.3.1 | Biblioteca que monta as telas do app | 🖥 Tela |
| `react-day-picker` | ^8.10.1 | Calendário para escolher datas | 🖥 Tela |
| `react-dom` | ^18.3.1 | Coloca as telas do React no navegador | 🖥 Tela |
| `react-hook-form` | ^7.55.0 | Formulários (campos, validação) | 🖥 Tela |
| `react-icons` | ^5.4.0 | Ícones | 🖥 Tela |
| `react-resizable-panels` | ^2.1.7 | Painéis que mudam de tamanho | 🖥 Tela |
| `recharts` | ^2.15.2 | Gráficos | 🖥 Tela |
| `tailwind-merge` | ^2.6.0 | Junta classes do Tailwind sem conflito | 🎨 Estilo |
| `tailwindcss-animate` | ^1.0.7 | Animações prontas para Tailwind | 🎨 Estilo |
| `tsx` | ^4.21.0 | Roda arquivos TypeScript direto (servidor em modo teste) | 🔧 Montagem |
| `tw-animate-css` | ^1.2.5 | Animações prontas para Tailwind | 🎨 Estilo |
| `vaul` | ^1.1.2 | Gaveta que sobe de baixo (celular) | 🖥 Tela |
| `wouter` | ^3.3.5 | Troca de páginas dentro do app (rotas) — leve | 🖥 Tela |
| `ws` | ^8.18.0 | Conexão em tempo real (WebSocket) | 🗄 Servidor |
| `zod` | ^3.25.76 | Confere se os dados estão no formato certo | 🧰 Utilidade |
| `zod-validation-error` | ^3.5.4 | (sem descrição — toque no nome para ver no npm) | ❔ |

**Dependências de montagem (dev) — 17:**

| Pacote | Versão | Pra que serve | Tipo |
|---|---|---|---|
| `@tailwindcss/typography` | ^0.5.15 | Estilo bonito para textos longos | 🎨 Estilo |
| `@tailwindcss/vite` | ^4.1.18 | Liga o Tailwind no Vite | 🎨 Estilo |
| `@types/express` | ^5.0.0 | Tipos do Express (só para montar) | 📐 Tipos |
| `@types/express-session` | ^1.18.0 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/node` | 20.19.27 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/passport` | ^1.0.16 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/passport-local` | ^1.0.38 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/react` | ^18.3.11 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/react-dom` | ^18.3.1 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@types/ws` | ^8.5.13 | Tipos para o TypeScript — só para montar, pode ignorar | 📐 Tipos |
| `@vitejs/plugin-react` | ^4.7.0 | Faz o Vite entender React | 🔧 Montagem |
| `autoprefixer` | ^10.4.20 | Ajusta o CSS para navegadores antigos | 🎨 Estilo |
| `esbuild` | ^0.25.0 | Empacotador rápido: junta o servidor num arquivo só | 🔧 Montagem |
| `postcss` | ^8.4.47 | Processa o CSS (usado pelo Tailwind) | 🎨 Estilo |
| `tailwindcss` | ^3.4.17 | Estilos prontos por classes (cores, espaços, tamanhos) | 🎨 Estilo |
| `typescript` | 5.6.3 | JavaScript com tipos — só para montar, não vai pro app final | 🔧 Montagem |
| `vite` | ^7.3.0 | Monta (builda) o app e roda o modo de teste rápido | 🔧 Montagem |

## ⛔ Restos da Replit (tirar ou trocar)

- server/routes.ts — 4 menção(ões)

## Arquivos importantes (12) — mandar estes para a IA

- `.github/workflows/teste.yml`
- `.github/workflows/windows.yml`
- `client/public/manifest.json`
- `client/src/App.tsx`
- `client/src/main.tsx`
- `components.json`
- `package.json`
- `postcss.config.js`
- `server/index.ts`
- `tailwind.config.ts`
- `tsconfig.json`
- `vite.config.ts`

## Estrutura completa (116 arquivos)

```
├── .github/
│   └── workflows/
│       ├── teste.yml
│       └── windows.yml
├── client/
│   ├── public/
│   │   ├── auditoria.html
│   │   ├── codigo-formatacao.txt
│   │   ├── comparador.html
│   │   ├── favicon.png
│   │   ├── icon-192.png
│   │   ├── icon-512.png
│   │   ├── manifest.json
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── pwa-install.tsx
│   │   │   ├── theme-provider.tsx
│   │   │   ├── theme-toggle.tsx
│   │   │   └── tiptap-editor.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── queryClient.ts
│   │   │   └── utils.ts
│   │   ├── pages/
│   │   │   ├── auditoria-financeira.tsx
│   │   │   ├── code-assistant.tsx
│   │   │   ├── comparador-juridico.tsx
│   │   │   ├── consulta-corporativo.tsx
│   │   │   ├── consulta-pdpj.tsx
│   │   │   ├── consulta-processual.tsx
│   │   │   ├── filtrador.tsx
│   │   │   ├── jurisprudencia.tsx
│   │   │   ├── legal-assistant.tsx
│   │   │   ├── login.tsx
│   │   │   ├── not-found.tsx
│   │   │   ├── painel-processos.tsx
│   │   │   ├── playground.tsx
│   │   │   ├── previdenciario.tsx
│   │   │   ├── robo-djen.tsx
│   │   │   ├── token-generator.tsx
│   │   │   └── tramitacao.tsx
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   └── index.html
├── migrations/
│   ├── meta/
│   │   ├── _journal.json
│   │   └── 0000_snapshot.json
│   └── 0000_init.sql
├── public/
│   └── auditoria.html
├── scripts/
│   ├── abrir-pronto.mjs
│   └── iniciar.mjs
├── server/
│   ├── db.ts
│   ├── djen.ts
│   ├── env.ts
│   ├── index.ts
│   ├── localdb.ts
│   ├── routes.ts
│   ├── storage.ts
│   ├── tts.ts
│   └── web.ts
├── shared/
│   ├── models/
│   │   └── chat.ts
│   └── schema.ts
├── windows/
│   └── Abrir-Juridico.bat
├── .env.exemplo
├── .gitignore
├── .npmrc
├── components.json
├── iniciar.bat
├── iniciar.sh
├── LEIA-ME.md
├── package.json
├── postcss.config.js
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts
```
