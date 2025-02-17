# 📝 **Capítulo 2 - Documentação de Requisitos**

> "A melhor maneira de prever o futuro é inventá-lo." – Alan Kay

## 📌 **2.1 Introdução**

A documentação de requisitos é um dos passos mais importantes no desenvolvimento de um sistema. Imagine tentar construir uma casa sem uma planta detalhada: haveria confusão, atrasos e erros. Da mesma forma, um sistema sem uma documentação clara pode gerar problemas como:

- Funcionalidades mal compreendidas ou mal implementadas.
- Atrasos no desenvolvimento devido a mudanças inesperadas.
- Dificuldade na manutenção e evolução do sistema.

### **Objetivo do Capítulo**

Neste capítulo, você aprenderá:

- O que é documentação de requisitos e por que ela é essencial.
- Tipos de documentos de requisitos utilizados no desenvolvimento de software.
- Como organizar as informações corretamente para garantir a clareza e eficiência do projeto.
- Exemplos práticos aplicados ao **Sistema de Gerenciamento de Sala de Aula (SGSA)**.

------

## 🎯 **2.2 O que é Documentação de Requisitos?**

A documentação de requisitos é o **registro formal de todas as funcionalidades e restrições do sistema**, garantindo que todos os envolvidos no projeto (clientes, desenvolvedores, testadores e gestores) compreendam exatamente o que será desenvolvido.

Sem uma documentação bem estruturada, o desenvolvimento pode se tornar caótico, pois cada pessoa pode interpretar os requisitos de maneira diferente.

------

## 📋 **2.3 Tipos de Documentos de Requisitos**

Os principais documentos utilizados para registrar requisitos são:

### 📄 **Especificação de Requisitos de Software (ERS)**

- Documento detalhado contendo **todas as funcionalidades e restrições do sistema**.
- Define o que deve ser feito e como deve ser entregue.

### 🔄 **Casos de Uso**

- Descrevem **como os usuários interagem com o sistema**.
- Representam fluxos de ações e alternativas para cada funcionalidade.

### 📝 **Histórias de Usuário**

- Utilizadas em metodologias ágeis, descrevem uma funcionalidade sob a perspectiva do usuário.
- Exemplo: *"Como professor, quero registrar a chamada dos alunos para manter um histórico de presença."*

### 🎨 **Protótipos**

- Representações visuais do sistema antes da implementação.
- Ajudam na validação das interfaces antes da programação.

### 📌 **Exemplo Aplicado ao SGSA**

#### **Especificação de Requisitos para Registro de Chamadas**

- **Título:** Registro de Chamada
- **Descrição:** O professor pode marcar alunos como **presente**, **ausente** ou **atrasado**.
- Requisitos:
  - O sistema deve listar os alunos cadastrados na turma.
  - O professor pode alterar o status dos alunos até o final da aula.
  - Os registros devem ser salvos automaticamente.

------

## 🛠 **2.4 Como Criar uma Documentação de Requisitos Eficiente?**

Para que a documentação seja útil e compreensível, siga estas boas práticas: 
- ✔ **Use linguagem clara e objetiva** – Evite ambiguidades.
- ✔ **Organize os requisitos** – Classifique-os em funcionais e não funcionais.
- ✔ **Use diagramas e tabelas** – Facilitam a visualização.
- ✔ **Mantenha o documento atualizado** – Requisitos podem mudar ao longo do projeto.

------

## 📌 **2.5 Exemplo de Documentação de Requisitos**

A seguir, apresentamos um exemplo real de documentação de requisitos aplicada ao **Sistema de Gerenciamento de Sala de Aula (SGSA)**, utilizando um modelo baseado na Especificação de Requisitos de Software (ERS).

### 📄 **Especificação de Requisitos de Software (ERS) - Exemplo**

#### **Título:** Registro de Chamadas no SGSA

- **Descrição:** O professor deve ser capaz de registrar a presença dos alunos pelo sistema.
- **Ator Principal:** Professor
- **Stakeholders:** Professores, Coordenadores, Alunos
- **Pré-condições:** O professor deve estar autenticado no sistema e vinculado a uma turma.

#### **Fluxo Principal:**

1. O professor acessa o sistema e seleciona a turma.
2. O sistema exibe a lista de alunos da turma.
3. O professor marca os alunos como "Presente", "Ausente" ou "Atrasado".
4. O sistema salva automaticamente o registro da chamada.
5. O professor pode visualizar chamadas anteriores.

#### **Regras de Negócio:**

- O professor só pode marcar a chamada dentro do horário da aula.
- Os registros de chamada devem ser armazenados por no mínimo 6 meses.
- Apenas professores vinculados a uma turma podem realizar chamadas.

#### **Requisitos Funcionais:**

- O sistema deve listar todos os alunos cadastrados em uma turma.
- O professor deve poder alterar o status da chamada até o fim da aula.
- O sistema deve permitir a consulta de chamadas anteriores.

#### **Requisitos Não Funcionais:**

- O sistema deve estar disponível 99% do tempo.
- A interface deve permitir o registro da chamada em menos de 5 segundos.
- O sistema deve suportar até 500 acessos simultâneos.

Esse exemplo mostra como documentar um requisito de maneira clara e organizada, garantindo que todos os envolvidos no projeto compreendam as funcionalidades e restrições do sistema.

------

## 🔍 **2.6 Conclusão**

A documentação de requisitos **evita falhas e garante que o desenvolvimento ocorra sem surpresas**. Ela deve ser clara, objetiva e acessível para todos os envolvidos no projeto.

Agora que entendemos a importância da documentação, no próximo capítulo veremos como validar e revisar requisitos para garantir que o sistema atenda às expectativas dos usuários! 🚀

------

# 🎯 **Fixação do Conteúdo**

## ✍️ **Questões Dissertativas**

1. Explique por que a documentação de requisitos é fundamental no desenvolvimento de software.
2. Diferencie Casos de Uso e Histórias de Usuário.

## ❓ **Questões de Múltipla Escolha**

1. Qual documento contém **todos os requisitos detalhados do sistema**?
   - (A) Código-fonte
   - (B) Especificação de Requisitos de Software
   - (C) Protótipo
   - (D) Relatório de testes
2. O que um **Caso de Uso** representa?
   - (A) Um modelo visual do sistema
   - (B) A interação entre um usuário e o sistema
   - (C) Um erro encontrado durante os testes
   - (D) Uma análise de desempenho

## ✅ **Questões de Caixa de Seleção**

1. Quais documentos fazem parte da documentação de requisitos?
   -  Código-fonte
   -  Especificação de Requisitos de Software
   -  Casos de Uso
   -  Protótipos

## 🔄 **Questões de Associação de Colunas**

Associe corretamente os conceitos:

1. (  ) Especificação de Requisitos
2. (  ) Caso de Uso
    (A) Define todas as funcionalidades do sistema.
    (B) Descreve a interação do usuário com o sistema.

## ⚖️ **Questões de Verdadeiro ou Falso**

1. ( ) Um Caso de Uso descreve como o sistema deve ser programado.
2. ( ) Histórias de Usuário são mais utilizadas em metodologias ágeis.

------

# 🏆 **Exercícios Práticos**

## 🏛 **Atividade em Sala de Aula**

1. Criar um **Caso de Uso** para um novo recurso do SGSA.
2. Escrever uma **História de Usuário** para uma funcionalidade do sistema.

## 🏡 **Atividade para Casa**

1. Escolher um aplicativo do dia a dia e listar **dois tipos de documentação de requisitos** aplicados a ele.
2. Criar um pequeno **protótipo em papel** de uma funcionalidade do SGSA.

------

💡 **Com esse conteúdo, você está pronto para documentar requisitos de sistemas de forma profissional e eficiente!** 🚀
