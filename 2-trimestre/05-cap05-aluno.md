# 📝 **Capítulo 5 – Fundamentos de Usabilidade**

> "A tecnologia só é boa quando aproxima as pessoas." – **Mark Zuckerberg**

---

## 📌 **5.1 Introdução**

Imagine tentar usar um aplicativo que você não consegue entender como funciona. Botões mal posicionados, informações confusas e navegação complicada podem fazer qualquer pessoa desistir de utilizar uma ferramenta digital. 😩

É por isso que a **usabilidade** é fundamental no **design de aplicativos**! Ela garante que as pessoas consigam **usar um sistema de forma fácil, eficiente e satisfatória**. No nosso projeto do **SGSA (Sistema de Gerenciamento de Sala de Aula)**, a usabilidade garante que os professores consigam registrar a chamada de forma rápida, sem complicações.

Neste capítulo, você aprenderá:

- O que é usabilidade.
- Por que a usabilidade é importante no desenvolvimento de aplicativos.
- As **10 heurísticas de usabilidade de Jakob Nielsen**.
- Como aplicar usabilidade ao **SGSA**.

---

## 🎯 **5.2 O que é Usabilidade?**

### ✅ **Definição**

A **usabilidade** é a **facilidade com que os usuários conseguem usar um sistema** para alcançar um determinado objetivo de forma eficiente, eficaz e com satisfação.

Segundo a **ISO 9241-11**, usabilidade é:

> "A medida na qual um produto pode ser usado por usuários específicos para alcançar objetivos específicos com eficácia, eficiência e satisfação em um contexto de uso especificado."

### 📌 **Exemplo prático:**

- No **SGSA**, se um professor precisa mais de 10 minutos para marcar a chamada de uma turma, algo está errado com a usabilidade do sistema.
- Se o botão **"Salvar chamada"** está escondido ou confunde o usuário, isso impacta negativamente a **eficiência** e **satisfação**.

**Objetivo da usabilidade:** Fazer com que **qualquer pessoa**, mesmo sem treinamento técnico, consiga usar o sistema de maneira **natural e intuitiva**.

---

## 🧭 **5.3 Por que Usabilidade é Importante?**

### 🚀 **Benefícios de uma boa usabilidade:**

- **Reduz erros do usuário.**
- **Aumenta a produtividade.**
- **Diminui o tempo de aprendizado.**
- **Gera satisfação e fidelização.**

🔎 **No contexto do SGSA:**

- **Boa usabilidade:** O professor registra a chamada em poucos cliques, sem precisar de ajuda.
- **Má usabilidade:** O professor desiste de usar o sistema e volta para a chamada no papel.

**Conclusão:** Sem usabilidade, o sistema **não será utilizado** ou será usado de forma incorreta, o que compromete o objetivo final.

---

## 🛠 **5.4 As 10 Heurísticas de Usabilidade de Jakob Nielsen**

As **heurísticas** são **princípios gerais** para guiar o design de interfaces mais amigáveis e intuitivas.

### 📋 **Lista das Heurísticas:**

1. **Visibilidade do status do sistema:** O sistema deve sempre informar ao usuário o que está acontecendo, por meio de feedback adequado e em tempo razoável.
   - *Exemplo SGSA:* Após o professor registrar a chamada, o sistema exibe uma mensagem "Chamada salva com sucesso!".

2. **Correspondência entre o sistema e o mundo real:** O sistema deve usar uma linguagem familiar aos usuários.
   - *Exemplo SGSA:* Usar os termos "Presente", "Ausente" e "Atrasado" ao invés de códigos como "P", "A", "T".

3. **Controle e liberdade do usuário:** Oferecer opções para desfazer ou refazer ações.
   - *Exemplo SGSA:* Permitir que o professor edite a chamada até o final da aula.

4. **Consistência e padrões:** Seguir convenções conhecidas, mantendo o design consistente.
   - *Exemplo SGSA:* Usar sempre o mesmo ícone para "salvar" em todas as telas.

5. **Prevenção de erros:** Evitar que erros aconteçam antes de corrigi-los.
   - *Exemplo SGSA:* Mostrar um alerta se o professor tentar salvar a chamada sem marcar todos os alunos.

6. **Reconhecimento ao invés de memorização:** O sistema deve minimizar a necessidade de o usuário lembrar informações.
   - *Exemplo SGSA:* Listar automaticamente os alunos da turma em cada chamada.

7. **Flexibilidade e eficiência de uso:** Atender tanto usuários iniciantes quanto experientes.
   - *Exemplo SGSA:* Oferecer atalhos para professores que já sabem como usar o sistema.

8. **Design estético e minimalista:** Mostrar apenas informações relevantes.
   - *Exemplo SGSA:* Exibir apenas o nome da turma, lista de alunos e botão "Salvar" na tela de chamada.

9. **Ajudar usuários a reconhecer, diagnosticar e recuperar erros:** Mensagens de erro devem ser claras e sugerir soluções.
   - *Exemplo SGSA:* "Aluno não encontrado na turma selecionada. Verifique se a turma correta foi escolhida."

10. **Ajuda e documentação:** Disponibilizar ajuda fácil de encontrar.
   - *Exemplo SGSA:* Botão "Ajuda" com instruções rápidas sobre como registrar chamadas.

---

## 📌 **5.5 Aplicando Usabilidade no SGSA**

Vamos aplicar as heurísticas na criação de um **protótipo da tela de chamada** do SGSA:

- **Visibilidade:** Mensagem "Chamada salva!".
- **Consistência:** Ícones padrão (salvar, editar).
- **Prevenção de erros:** Alerta ao tentar salvar sem completar a chamada.
- **Design minimalista:** Apenas o essencial na tela: lista de alunos, opções de status e botão salvar.

Esses pequenos detalhes tornam a experiência **fluida e agradável**! 😃

---

## 🔍 **5.6 Conclusão**

A **usabilidade** é o que garante que **aplicativos realmente sejam úteis**. Sem ela, até o melhor sistema pode falhar. Ao seguir as **heurísticas de Nielsen**, garantimos que o **SGSA** (e qualquer outro aplicativo) seja **fácil de usar, eficiente e agradável** para os usuários.

No próximo capítulo, vamos explorar **acessibilidade**, para garantir que **todos**, inclusive pessoas com deficiência, possam utilizar o sistema!

---

# 🎯 **Fixação do Conteúdo**

## ✍️ **Questões Dissertativas**

1. Explique, com suas palavras, o que é usabilidade e por que ela é essencial para o sucesso de um aplicativo.
2. Escolha **três heurísticas de Nielsen** e descreva como elas podem ser aplicadas em um aplicativo educacional.

## ❓ **Questões de Múltipla Escolha**

1. Qual das opções **não** é uma heurística de Nielsen?
   - (A) Consistência e padrões
   - (B) Flexibilidade e eficiência de uso
   - (C) Backup automático de dados
   - (D) Prevenção de erros

2. O que significa "visibilidade do status do sistema"?
   - (A) Tornar o sistema mais visível para outras pessoas.
   - (B) O sistema informar ao usuário o que está acontecendo.
   - (C) Permitir que o usuário personalize o sistema.
   - (D) Esconder informações irrelevantes do usuário.

## ✅ **Questões de Caixa de Seleção**

1. Quais das seguintes opções são benefícios de uma boa usabilidade?
   - [ ] Aumentar o tempo de aprendizado.
   - [ ] Reduzir erros.
   - [ ] Melhorar a satisfação do usuário.
   - [ ] Dificultar a navegação.

2. Quais das seguintes heurísticas ajudam a evitar erros?
   - [ ] Prevenção de erros.
   - [ ] Consistência e padrões.
   - [ ] Controle e liberdade do usuário.
   - [ ] Design estético e minimalista.

## 🔄 **Questões de Associação de Colunas**

Associe cada heurística à sua descrição:

1. (  ) Controle e liberdade do usuário
2. (  ) Consistência e padrões
3. (  ) Prevenção de erros
4. (  ) Design estético e minimalista

(A) Seguir convenções familiares para o usuário.
(B) Evitar que erros aconteçam antes que precisem ser corrigidos.
(C) Permitir desfazer ou refazer ações.
(D) Mostrar apenas o essencial, evitando poluição visual.

## ⚖️ **Questões de Verdadeiro ou Falso**

1. ( ) A heurística "reconhecimento ao invés de memorização" sugere que o sistema deve exigir que o usuário memorize comandos complexos.
2. ( ) Um design estético e minimalista ajuda a tornar o sistema mais fácil de usar.

---

# 🏆 **Exercícios Práticos**

## 🏛 **Atividade em Sala de Aula**

1. Escolha um aplicativo conhecido (ex: WhatsApp, Instagram) e identifique **três heurísticas de Nielsen** aplicadas nele.
2. Em grupo, desenhem um **protótipo em papel** da tela de chamada do **SGSA**, aplicando pelo menos **cinco heurísticas**.

## 🏡 **Atividade para Casa**

1. Analise um site ou aplicativo que você usa diariamente e liste **dois pontos fortes** e **dois pontos fracos** em termos de usabilidade.
2. Proponha **duas melhorias** de usabilidade para o **protótipo do SGSA** (pode ser escrito ou desenhado em papel).

---

💡 **Com este capítulo, você está pronto para projetar interfaces que realmente funcionam e agradam os usuários!** 🚀

