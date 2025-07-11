# NLW Agents

Este projeto foi desenvolvido durante o evento **NLW (Next Level Week)** promovido pela [Rocketseat](https://www.rocketseat.com.br/).

O **NLW Agents** é uma aplicação web que permite o envio de perguntas para salas específicas, com respostas geradas por inteligência artificial. A aplicação se comunica com uma API e utiliza IA para gerar respostas com base em áudios transcritos.

## 🔧 Tecnologias e Ferramentas

- **React** (com Vite)
- **TypeScript**
- **Tailwind CSS**
- **ShadCN UI** (componentes UI)
- **React Query** (`@tanstack/react-query`) – gerenciamento de requisições assíncronas
- **React Hook Form** – formulários
- **Zod** – validação de dados
- **Lucide React** – ícones
- **Dayjs** – manipulação de datas

## 🧱 Padrões e Estrutura

- Projeto modular com separação de responsabilidades.
- Uso de componentes reutilizáveis.
- Estilização via classes utilitárias do Tailwind CSS.
- Configuração moderna com Vite + TypeScript.

## ▶️ Como rodar o projeto localmente

1. **Clone o repositório**
```bash
git clone https://github.com/ViniciusMendesLima/nlw_agents_react.git
cd nlw_agents_react
```

2. **Instale as dependências**
```bash
npm install
# ou
yarn
```

3. **Execute o projeto em modo de desenvolvimento**
```bash
npm run dev
```
O app estará disponível em: http://localhost:5173

## 🧪 Observações
- Certifique-se de que a API do NLW Agents (back-end) esteja rodando corretamente para que o front-end funcione.

- Algumas funcionalidades dependem da transcrição de áudios e IA, fornecidas por uma API customizada (ex: com Gemini ou OpenAI).
## 📁 Estrutura principal

```bash
src/
├── components/       # Componentes reutilizáveis
├── http/              # Hooks de comunicação com API
├── lib/               # Configurações auxiliares (ex: dayjs)
├── pages/            # Páginas principais
├── index.css/           # Estilos (Tailwind)
├── App.tsx           # Componente raiz
├── main.tsx          # Ponto de entrada
vite.config.ts        # Configuração do Vite
tsconfig.json         # Configuração do TypeScript
```


## 📄 Licença
Este projeto é apenas para fins educacionais, desenvolvido durante o evento NLW da Rocketseat.

