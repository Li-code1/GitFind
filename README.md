
```markdown
# 🔎 GitHub Profile Finder

Um buscador de perfis e repositórios do GitHub desenvolvido em React.js, utilizando HTML, CSS, JavaScript e Fetch API.  
O usuário digita o nome de usuário do GitHub e a aplicação retorna informações do perfil e lista de repositórios públicos.

---

## 🚀 Tecnologias utilizadas
- [React.js](https://reactjs.org/)  
- HTML5  
- CSS3  
- JavaScript (ES6+)  
- Fetch API  
- Yarn ou NPM para gerenciamento de pacotes  

---

## 📂 Estrutura do projeto
```
src/
├── App.js          # Componente principal com lógica de busca
├── App.css         # Estilos do App
├── index.js        # Ponto de entrada que renderiza o App
├── index.css       # Estilos globais
```

---

## ⚙️ Instalação e execução

### 1. Clonar o repositório
```bash
git clone https://github.com/seu-usuario/github-profile-finder.git
cd github-profile-finder
```

### 2. Instalar dependências
Com Yarn:
```bash
yarn install
```
Ou com NPM:
```bash
npm install
```

### 3. Rodar o projeto
Com Yarn:
```bash
yarn start
```
Ou com NPM:
```bash
npm start
```

A aplicação abrirá automaticamente em `http://localhost:3000`.

---

## 🖥️ Como usar
1. Digite o nome de usuário do GitHub no campo de busca.  
2. Clique em **Buscar**.  
3. O perfil e os repositórios públicos serão exibidos na tela.  

Exemplo:  
- Usuário: `torvalds`  
- Resultado: Perfil de Linus Torvalds + lista de repositórios.

---

## 🎨 Layout básico
- Campo de entrada para o nome de usuário.  
- Botão de busca estilizado.  
- Card com informações do perfil (nome, login, avatar, bio).  
- Lista de repositórios com links para o GitHub.  

---

## 📌 Melhorias futuras
- Paginação de repositórios.  
- Exibir estatísticas (seguidores, estrelas, linguagens mais usadas).  
- Histórico de buscas.  
- Deploy em plataformas como Netlify ou Vercel.  

---

## 📄 Licença
Este projeto é open-source e pode ser utilizado livremente para estudos e melhorias.
```
