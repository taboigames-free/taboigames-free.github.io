# 🎮 TABOI-GAMES

Bem-vindo ao **Taboi-Games**, uma plataforma dedicada à distribuição, organização e acesso simplificado a jogos digitais através da web.

---

## 📌 Sobre o Projeto

O **Taboi-Games** é um projeto web inspirado em plataformas modernas de jogos, com foco em:

* Interface simples e rápida
* Tema visual estilo Steam (modo escuro)
* Acesso direto aos jogos
* Organização via arquivos JSON
* Navegação leve sem instalações complexas

O objetivo é oferecer uma experiência prática para explorar e acessar jogos diretamente pelo navegador.

---

## 🚀 Funcionalidades

* ✅ Página inicial moderna
* ✅ Sistema de navegação por abas
* ✅ Lista dinâmica de jogos
* ✅ Carregamento automático via JSON
* ✅ Redirecionamento rápido entre páginas
* ✅ Interface responsiva
* ✅ Estrutura leve em HTML, CSS e JavaScript

---

## 📁 Estrutura do Projeto

```
taboigames-free.github.io/
│
├── home.html
├── games.html
├── games.json
├── index.html
├── style.css
├── thegame.html
│
├── games/
│   └── stardewvalley.json
```

---

## ⚙️ Como Usar

1. Clone o repositório:

```bash
git clone https://github.com/taboigames/taboi-games.git
```

2. Abra o projeto:

```
home.html
```

3. Execute em um navegador moderno.

> Recomendado usar um servidor local para evitar bloqueios de CORS.

Exemplo:

```bash
python -m http.server
```

---

## 🧩 Como Adicionar Jogos

1. Abra `games.json`
2. Adicione um novo objeto seguindo o padrão:

```json
{
  "name": "Nome do Jogo",
  "page": "data/jogo.json",
  "cover": "assets/images/jogo.jpg"
}
```

3. Crie o arquivo JSON do jogo dentro da pasta `data/`.

---

## 🔒 Segurança

A plataforma segue uma **Licença de Segurança própria**, garantindo:

* verificação básica dos arquivos;
* recomendações de uso seguro;
* responsabilidade compartilhada com o usuário.

---

## 💻 Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* JSON

---

## 🌐 Links Oficiais

* Página principal:
  [[https://taboigames-free.github.io/home.html]((https://taboigames-free.github.io/home.html))]

* GitHub:
  [https://github.com/taboigames-free/taboigames-free.github.io](https://github.com/taboigames-free/taboigames-free.github.io)

---

## 🤝 Contribuição

Contribuições são bem-vindas.

Você pode:

* reportar bugs
* sugerir melhorias
* enviar novas ideias de interface

---

## 📄 Licença

Este projeto possui licença própria de segurança e uso.

© 2026 Taboi-Games — Todos os direitos reservados.
