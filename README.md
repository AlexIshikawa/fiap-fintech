# Ishikawa FIN — Front-end

Projeto acadêmico desenvolvido para a disciplina de Front-end Web da FIAP.  
Trata-se da interface de uma fintech pessoal chamada **Ishikawa FIN**, com foco em controle de movimentações financeiras.

---

## 👤 Aluno

| Nome | RM |
|---|---|
| Alexandre Ishikawa | RM573280 |

---

## 📋 Sobre o projeto

O Ishikawa FIN é um sistema de gestão financeira pessoal. Esta entrega corresponde à **Atividade - Muito estilo sem sofrimento e Rede Social dos Desenvolvedores**, com a construção da interface utilizando HTML e Tailwind CSS.

A tela desenvolvida é o **Histórico de Movimentações**, que permite ao usuário visualizar, filtrar e gerenciar suas transações financeiras de forma clara e responsiva.

### Funcionalidades presentes na tela

- Sidebar de navegação com seções *Gerencia* e *Atalhos*
- Header com barra de busca e ícones de notificação e configurações
- Cards de resumo financeiro: Fluxo Líquido, Receita e Despesas
- Filtros por categoria, tipo e valor
- Tabela de movimentações com badge de tipo (Entrada/Saída), forma de pagamento e menu de ações (Editar, Duplicar, Excluir)
- Navegação inferior responsiva para dispositivos mobile

---

## 🛠️ Tecnologias utilizadas

- HTML5
- Tailwind CSS v4 (via CLI — sem CDN)
- Google Fonts (Inter)

---

## 📁 Estrutura do projeto

```
ishikawa-fin/
├── dist/
│   ├── css/
│   │   └── styles.css       # CSS compilado — não editar diretamente
│   ├── images/
│   └── index.html           # Arquivo principal
├── src/
│   └── input.css            # Fonte do CSS (tokens + @theme)
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

---

## 🚀 Como executar

Basta abrir o arquivo `dist/index.html` diretamente no navegador.  
Não é necessário instalar dependências — o CSS já está compilado em `dist/css/styles.css`.

### Para desenvolvedores (opcional)

Caso queira editar os estilos e recompilar:

```bash
npm install
npm run dev      # watch mode
npm run build    # build minificado para produção
```

---

## 📦 Entregáveis

- [x] Arquivo HTML separado do CSS
- [x] Tailwind CSS utilizado via CLI
- [x] Responsividade para dispositivos mobile
- [x] Repositório público no GitHub
- [x] CSS compilado incluso para execução sem dependências