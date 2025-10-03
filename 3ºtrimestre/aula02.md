# 📱 UC21 — Design de Aplicativos  
## Aula 02 • 3º Trimestre — Estrutura de Projeto & Navegação Inicial 🗂️

![Trimestre](https://img.shields.io/badge/Trimestre-3º-blue)
![Aula](https://img.shields.io/badge/Aula-02%2F08-informational)
![Duração](https://img.shields.io/badge/Duração-50_minutos-lightgrey)
![Projeto](https://img.shields.io/badge/Projeto-SGSA-8A2BE2)

> ✨ *“Um bom design não é apenas como parece, mas como funciona.” — Steve Jobs*

---

## 🎯 Objetivos da Aula
- Entender como funciona a **estrutura de um projeto de aplicativo** (pastas, arquivos e telas).  
- Diferenciar **front-end** (interface) e **back-end** (dados e lógica).  
- Criar a navegação inicial do SGSA (Login → Menu → Chamada).  
- Aplicar **boas práticas de organização** desde o início do desenvolvimento.  

---

## 🧱 Conteúdo da Aula

### 1) Estrutura de um Projeto de Aplicativo
Um projeto bem organizado facilita o trabalho em equipe e evita erros.  

- **Pastas:** organização por telas, componentes e assets (imagens, ícones).  
- **Arquivos:** cada tela ou módulo em arquivo separado.  
- **Assets:** imagens, ícones e estilos padronizados.  

📌 Exemplo simplificado (estrutura lógica):  
```

SGSA-App/
├── assets/        # ícones, imagens
├── screens/       # telas (Login, Menu, Chamada)
├── components/    # botões, campos, listas
└── app.json       # configuração inicial

```

---

### 2) Front-end × Back-end
- **Front-end:** tudo o que o usuário vê (botões, listas, menus, cores).  
- **Back-end:** lógica que processa dados, armazena informações e faz conexões.  

👉 Nesta aula, o foco será **front-end inicial** (telas e navegação).  

---

### 3) Navegação Entre Telas
- **Fluxo mínimo do SGSA:**  
  1. **Login** → acesso do professor.  
  2. **Menu** → opções principais.  
  3. **Chamada** → marcar presença.  

- **Boas práticas:**  
  - Botões bem posicionados e rotulados.  
  - Fluxo **linear e simples** no início.  
  - Mensagens de confirmação para cada ação.  

---

### 4) Aplicação Prática no SGSA
Cada grupo deve:  
- Criar a **estrutura inicial do projeto**.  
- Implementar a **navegação básica** entre as telas.  
- Usar **nomes claros** para pastas, arquivos e botões.  

---

## 🧪 Atividades Práticas (em sala)
1. **Organização:** criar a estrutura de pastas do projeto conforme exemplo.  
2. **Implementação:** construir telas estáticas de Login, Menu e Chamada.  
3. **Navegação:** configurar os botões para mudar de uma tela para outra.  
4. **Revisão rápida:** testar se o fluxo Login → Menu → Chamada funciona sem erros.

📤 **Entregáveis (Classroom)**  
- Print da árvore de pastas do projeto.  
- Print de cada tela criada (Login, Menu, Chamada).  
- Arquivo `fluxo-navegacao.md` explicando em até 8 linhas como funciona o fluxo inicial.

---

## 🏠 Atividade para Casa
1. Adicionar uma nova tela ao protótipo: **Tela de Ocorrências**.  
2. Atualizar o fluxo de navegação: Login → Menu → Ocorrências → Voltar ao Menu.  
3. Trazer print do fluxo completo para a próxima aula.  

---

# 🧠 Fixação de Conteúdo

### ✅ 1) Dissertativas
1. Explique a diferença entre **front-end** e **back-end** em um aplicativo.  
2. Por que é importante organizar as pastas e arquivos desde o início de um projeto de aplicativo?  

---

### 🔘 2) Múltipla Escolha (1 correta)
1. O que caracteriza o **front-end** de um aplicativo?  
   - [ ] Lógica de banco de dados  
   - [ ] Configuração do servidor  
   - [ ] Interface que o usuário vê e interage  
   - [ ] Registro de logs de erros  

2. Qual a **principal vantagem** de estruturar pastas e arquivos desde o começo?  
   - [ ] Aumentar o tamanho do projeto  
   - [ ] Tornar mais difícil localizar erros  
   - [ ] Facilitar manutenção e colaboração  
   - [ ] Esconder funções do usuário  

---

### ☐ 3) Caixa de Seleção (múltiplas corretas)
1. São **boas práticas de navegação inicial**:  
   - [ ] Botões com rótulos claros  
   - [ ] Fluxo simples entre telas  
   - [ ] Mensagens de feedback ao usuário  
   - [ ] Menu escondido sem instruções  
   - [ ] Estrutura de pastas organizada  

---

### 🔗 4) Associação de Colunas
Associe o conceito ao exemplo prático:

| Conceito           | Exemplo no SGSA                                   |
| ------------------ | ------------------------------------------------- |
| (A) Front-end      | (  ) Tela de chamada com lista de alunos          |
| (B) Back-end       | (  ) Registro dos dados de presença em um banco   |
| (C) Organização    | (  ) Pastas separadas para assets e componentes   |
| (D) Navegação      | (  ) Login → Menu → Chamada sem travar            |

---

### ✔️ 5) Verdadeiro ou Falso
a) O front-end cuida da interface e interação do usuário.  
b) O back-end é responsável apenas por cores e botões.  
c) A navegação deve ser clara e objetiva.  
d) A organização de pastas facilita o trabalho em grupo.  

- [ ] F V V V  
- [ ] V F V V  
- [ ] V V F F  
- [ ] F V F V  

---

### 🚀 6) Desafio
Crie um **fluxo alternativo** para o SGSA incluindo uma tela adicional (ex.: *Lições de Casa*).  
1. Desenhe o fluxo em papel ou Figma.  
2. Explique em 5–8 linhas como esse fluxo melhora a experiência do usuário (UX).  

---

## 📚 Materiais de Apoio
- **Cap. 5 – Usabilidade:** heurísticas aplicadas ao design de telas.  
- **Cap. 6 – Acessibilidade:** WCAG e boas práticas para interfaces claras.  
- **Cap. 8 – Prototipação:** evolução de fluxos em baixa e alta fidelidade.  

---

### 🧭 Navegação
⬅️ Aula 01 — **Introdução & Kick-off do Projeto** • 🏠 **Home UC21** • ➡️ Aula 03 — **Criando Telas & Fluxos Detalhados**
