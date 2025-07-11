# NLW Agents

Este projeto foi desenvolvido durante o evento **NLW da Rocketseat** e se chama **NLW Agents**. A aplicação é construída com **React**, utilizando **TypeScript**, **Tailwind CSS**, **Vite** e outras ferramentas modernas do ecossistema web.

## 🔧 Tecnologias e Ferramentas

- **React 19** – Biblioteca para construção de interfaces de usuário.
- **TypeScript** – Tipagem estática para JavaScript.
- **Vite** – Bundler moderno e rápido para desenvolvimento.
- **Tailwind CSS** – Framework utilitário para estilização rápida.
- **@vitejs/plugin-react** – Suporte oficial do React no Vite.
- **@biomejs/biome** – Linter e formatter para manter qualidade de código.
- **Ultracite** – Ferramenta moderna para testes e análise de código.

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
```

3. **Execute o projeto em modo de desenvolvimento**
```bash
npm run dev
```
O app estará disponível em: http://localhost:5173

4. **Build para produção**
```bash
npm run build
```
5. **Pré-visualização da build**
```bash
npm run preview
```
## 📁 Estrutura principal

```bash
src/
├── components/       # Componentes reutilizáveis
├── pages/            # Páginas principais
├── styles/           # Estilos (Tailwind)
├── App.tsx           # Componente raiz
├── main.tsx          # Ponto de entrada
vite.config.ts        # Configuração do Vite
tsconfig.json         # Configuração do TypeScript
```


## 📌 Observações
- O projeto usa moduleResolution: "bundler" no TypeScript para melhor compatibilidade com Vite e ESM.

- Lint e formatação automática com Biome.

- Tipagem rigorosa com strict: true.

Feito com 💜 durante o NLW da Rocketseat

