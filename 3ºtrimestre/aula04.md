# 📱 UC21 — Design de Aplicativos  
## Aula 04 • 3º Trimestre — Funcionalidades Básicas & Primeiros Dados ⚡

![Trimestre](https://img.shields.io/badge/Trimestre-3º-blue)
![Aula](https://img.shields.io/badge/Aula-04%2F08-informational)
![Duração](https://img.shields.io/badge/Duração-50_minutos-lightgrey)
![Projeto](https://img.shields.io/badge/Projeto-SGSA-8A2BE2)

> ✨ *“Um aplicativo é útil quando resolve problemas reais de forma simples e eficaz.”*

---

## 🎯 Objetivos da Aula
- Introduzir o conceito de **variáveis** e como elas guardam informações.  
- Ligar botões e inputs a **ações simples** no aplicativo.  
- Criar a primeira funcionalidade básica do SGSA: **registro simples de chamada**.  
- Compreender a importância do **feedback imediato** ao usuário.  

---

## 🧱 Conteúdo da Aula

### 1) O que são Variáveis?
- **Definição:** espaço na memória do sistema usado para guardar informações.  
- **Exemplo no SGSA:** variável `presenca` armazena se um aluno está **Presente**, **Ausente** ou **Atrasado**.  

---

### 2) Lógica Básica de Ações
- Botões não são apenas elementos visuais → eles **executam ações**.  
- Exemplo: ao clicar em “Salvar Chamada”, o app guarda valores selecionados em variáveis.  
- Esse é o primeiro passo para evoluir depois para um **CRUD (Create, Read, Update, Delete)**.  

---

### 3) Criando o Registro Simples de Chamada
Fluxo esperado:  
1. Professor escolhe uma turma no **Menu**.  
2. Marca a presença dos alunos na tela **Chamada**.  
3. Clica em **Salvar**.  
4. O sistema mostra mensagem: **“Chamada salva com sucesso!”**.  

👉 Nesta versão, os dados podem ser salvos **apenas na sessão** (sem banco de dados).  

---

### 4) Feedback ao Usuário
- O sistema deve sempre responder às ações do usuário.  
- Exemplo: **toast/snackbar** ou mensagem em tela confirmando a chamada.  
- Sem feedback, o usuário pode não saber se a ação funcionou.  

---

## 🧪 Atividades Práticas (em sala)
1. Criar variáveis simples para armazenar presença de alunos.  
2. Programar o botão “Salvar Chamada” para registrar os valores.  
3. Exibir mensagem de confirmação ao final da ação.  

📤 **Entregáveis (Classroom)**  
- Print da tela de chamada funcional.  
- Arquivo `registro-simples.md` explicando em até 6 linhas como a chamada foi implementada.  

---

## 🏠 Atividade para Casa
1. Adicionar **um campo extra** na tela de chamada para registrar observações (ex.: “chegou atrasado às 08h20”).  
2. Implementar o botão **Limpar** para reiniciar a lista de presença.  

---

# 🧠 Fixação de Conteúdo

### ✅ 1) Dissertativas
1. Explique, com suas palavras, o que são variáveis e como elas podem ser usadas em um aplicativo.  
2. Por que o **feedback ao usuário** é fundamental na experiência de uso de um app?  

---

### 🔘 2) Múltipla Escolha (1 correta)
1. O que é uma **variável** em programação?  
   - [ ] Um botão gráfico  
   - [ ] Um tipo de layout  
   - [ ] Um espaço na memória que guarda informações  
   - [ ] Uma imagem de ícone  

2. Qual é um exemplo de **feedback de sistema**?  
   - [ ] Nenhuma mensagem após clicar em “Salvar”  
   - [ ] Mensagem “Chamada salva com sucesso!”  
   - [ ] Ícone decorativo sem função  
   - [ ] Botão sem rótulo  

---

### ☐ 3) Caixa de Seleção (múltiplas corretas)
1. São exemplos de ações básicas em um app:  
   - [ ] Clicar em botões  
   - [ ] Guardar valores em variáveis  
   - [ ] Alterar status de alunos  
   - [ ] Mensagem de erro ou confirmação  
   - [ ] Criar protótipos em papel (não é ação do sistema, mas de design)  

---

### 🔗 4) Associação de Colunas
Associe o conceito ao exemplo:

| Conceito            | Exemplo no SGSA                           |
| ------------------- | ------------------------------------------ |
| (A) Variável        | (  ) Guardar status de presença            |
| (B) Ação de botão   | (  ) Salvar chamada                        |
| (C) Feedback        | (  ) Mostrar “Chamada registrada com sucesso” |
| (D) Campo de input  | (  ) Observações do professor              |

---

### ✔️ 5) Verdadeiro ou Falso
a) Variáveis servem para armazenar dados temporários ou permanentes.  
b) Feedback visual é opcional em aplicativos.  
c) Botões só têm função estética.  
d) Inputs permitem entrada de dados pelo usuário.  

- [ ] V F V F  
- [ ] V F F V  
- [ ] V V F V  
- [ ] F V F V  

---

### 🚀 6) Desafio
Implemente uma melhoria no fluxo de chamada:  
1. Ao salvar, o sistema deve mostrar não apenas “Chamada salva”, mas também **quantos alunos foram marcados presentes**.  
2. Explique em até 6 linhas por que esse feedback adicional melhora a **experiência do professor**.  

---

## 📚 Materiais de Apoio
- **Cap. 4 – Implementação Inicial de Requisitos:** como começar a transformar requisitos em código.  
- **Cap. 5 – Usabilidade:** importância do feedback ao usuário.  
- **Cap. 7 – Experiência do Usuário (UX):** como fluxos simples impactam a satisfação.  

---

### 🧭 Navegação
⬅️ Aula 03 — **Criando Telas & Fluxos Detalhados** • 🏠 **Home UC21** • ➡️ Aula 05 — **Integração com Dados & CRUD Inicial**
