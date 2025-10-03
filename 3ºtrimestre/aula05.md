# 📱 UC21 — Design de Aplicativos  
## Aula 05 • 3º Trimestre — Integração com Dados & CRUD Inicial 🗄️

![Trimestre](https://img.shields.io/badge/Trimestre-3º-blue)
![Aula](https://img.shields.io/badge/Aula-05%2F08-informational)
![Duração](https://img.shields.io/badge/Duração-50_minutos-lightgrey)
![Projeto](https://img.shields.io/badge/Projeto-SGSA-8A2BE2)

> ✨ *“Dados organizados transformam informações em conhecimento.”*

---

## 🎯 Objetivos da Aula
- Compreender o conceito de **CRUD** (Create, Read, Update, Delete).  
- Implementar uma forma simples de **armazenar dados localmente**.  
- Criar o primeiro protótipo de **lista de registros de chamada**.  
- Explorar a importância da **persistência de dados** em aplicativos.  

---

## 🧱 Conteúdo da Aula

### 1) O que é CRUD?
CRUD é o ciclo básico de manipulação de dados em qualquer sistema:  
- **C (Create):** Criar novos registros.  
- **R (Read):** Ler/consultar registros.  
- **U (Update):** Atualizar registros existentes.  
- **D (Delete):** Apagar registros.  

📌 Exemplo no SGSA:  
- Criar chamada → Marcar presença → Atualizar aluno que chegou atrasado → Excluir registro incorreto.

---

### 2) Armazenamento Local
Nesta etapa inicial não usaremos banco de dados externo.  
- **No/Low-Code:** listas internas ou variáveis globais.  
- **IDE (Android Studio/Flutter):** arrays, listas ou armazenamento simples em memória.  

👉 Objetivo: permitir que o professor **veja os registros criados** em tempo real.  

---

### 3) Protótipo de Lista de Chamadas
Fluxo básico:  
1. Professor abre a tela **Chamada**.  
2. Marca presença dos alunos.  
3. Ao salvar, os registros vão para uma **lista visível**.  
4. O professor pode **editar ou excluir** um registro.  

---

### 4) Importância da Persistência
- **Sem persistência:** dados desaparecem ao fechar o app.  
- **Com persistência (mesmo que local):** registros ficam guardados e podem ser consultados depois.  
- Esse é o primeiro passo antes de conectar o app a um **banco de dados real**.  

---

## 🧪 Atividades Práticas (em sala)
1. Criar uma lista simples para armazenar registros de chamada.  
2. Implementar botões para **adicionar** e **exibir** os registros.  
3. Testar as opções de **editar** ou **apagar** registros.  

📤 **Entregáveis (Classroom)**  
- Print da lista de chamadas funcionando.  
- Arquivo `crud-simples.md` descrevendo em até 8 linhas como o CRUD foi implementado no protótipo.  

---

## 🏠 Atividade para Casa
1. Adicionar ao protótipo a possibilidade de **editar o status de um aluno** (de Ausente para Presente, por exemplo).  
2. Criar um botão “Excluir Registro” e testar em pelo menos 3 casos diferentes.  

---

# 🧠 Fixação de Conteúdo

### ✅ 1) Dissertativas
1. Explique o conceito de **CRUD** e dê um exemplo aplicado ao SGSA.  
2. Qual a importância de armazenar dados de forma persistente em um aplicativo?  

---

### 🔘 2) Múltipla Escolha (1 correta)
1. Qual das opções **não** faz parte do CRUD?  
   - [ ] Create  
   - [ ] Read  
   - [ ] Update  
   - [ ] Design  

2. Ao salvar uma chamada e exibi-la em uma lista, estamos aplicando:  
   - [ ] Delete  
   - [ ] Update  
   - [ ] Read  
   - [ ] Nenhuma das anteriores  

---

### ☐ 3) Caixa de Seleção (múltiplas corretas)
1. São operações do CRUD:  
   - [ ] Criar novos registros  
   - [ ] Ler registros  
   - [ ] Atualizar registros  
   - [ ] Deletar registros  
   - [ ] Pintar botões de outra cor  
   - [ ] Mostrar animações  

---

### 🔗 4) Associação de Colunas
Associe a operação CRUD ao exemplo no SGSA:

| Operação  | Exemplo SGSA                               |
| --------- | ------------------------------------------ |
| (A) Create | (  ) Registrar uma nova chamada            |
| (B) Read   | (  ) Consultar lista de presenças          |
| (C) Update | (  ) Alterar status de aluno atrasado      |
| (D) Delete | (  ) Apagar um registro marcado errado     |

---

### ✔️ 5) Verdadeiro ou Falso
a) CRUD é um conceito aplicado apenas a bancos de dados externos.  
b) Persistência de dados é importante para manter registros acessíveis.  
c) Em aplicativos, armazenar informações localmente pode ser uma solução inicial.  
d) Sem persistência, os dados permanecem após fechar o app.  

- [ ] V V V F  
- [ ] F V V F  
- [ ] V F V V  
- [ ] F V F V  

---

### 🚀 6) Desafio
Implemente uma funcionalidade de **lista de presença** que permita:  
1. Criar chamada com 5 alunos.  
2. Mostrar a lista com os status selecionados.  
3. Alterar o status de pelo menos 1 aluno.  
4. Excluir 1 registro incorreto.  

Explique em até 10 linhas como esse CRUD inicial se conecta à **realidade dos professores** no uso do SGSA.  

---

## 📚 Materiais de Apoio
- **Cap. 4 – Implementação Inicial dos Requisitos:** primeiros códigos e testes.  
- **Cap. 5 – Usabilidade:** importância de feedback em ações CRUD.  
- **Cap. 8 – Prototipação:** simulação de fluxos antes da integração real de dados.  

---

### 🧭 Navegação
⬅️ Aula 04 — **Funcionalidades Básicas & Primeiros Dados** • 🏠 **Home UC21** • ➡️ Aula 06 — **Usabilidade & Acessibilidade na Prática**
