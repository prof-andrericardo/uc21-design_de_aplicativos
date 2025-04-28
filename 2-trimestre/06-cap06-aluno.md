# 📝 **Capítulo 6 – Acessibilidade em Aplicativos Móveis**

> "A verdadeira deficiência é quando as pessoas não conseguem enxergar o potencial dos outros." – **Rick Guidotti** (fotógrafo e defensor da inclusão)

------

## 📌 **6.1 Introdução**

Você já parou para pensar **como uma pessoa com deficiência visual utiliza um aplicativo?** Ou como alguém com dificuldades motoras navega em um celular?

A **acessibilidade digital** garante que **todos** – independentemente de suas limitações físicas, sensoriais ou cognitivas – possam utilizar um sistema de forma **autônoma e eficiente**. 🌍

Neste capítulo, você vai aprender:

- O que é acessibilidade digital.
- Quais são os principais **padrões e normas** de acessibilidade.
- Como implementar **acessibilidade em aplicativos móveis**, com exemplos aplicados ao **SGSA (Sistema de Gerenciamento de Sala de Aula)**.

------

## 🎯 **6.2 O que é Acessibilidade Digital?**

### ✅ **Definição**

A **acessibilidade digital** é o conjunto de práticas que garante que **pessoas com deficiências** consigam acessar, compreender e interagir com sistemas e aplicativos.

De acordo com a **WCAG (Web Content Accessibility Guidelines)**:

> "Acessibilidade é garantir que **conteúdos e interfaces** sejam **perceptíveis, operáveis, compreensíveis e robustos** para todas as pessoas."

### 📌 **Exemplos de deficiências atendidas pela acessibilidade:**

- **Deficiência visual:** cegueira, baixa visão, daltonismo.
- **Deficiência auditiva:** surdez, deficiência auditiva parcial.
- **Deficiência motora:** dificuldades para usar mouse, teclado ou touchscreen.
- **Deficiência cognitiva:** dificuldades de atenção, memória, compreensão.

------

## 🚀 **6.3 Padrões e Normas de Acessibilidade**

### 🌐 **WCAG (Web Content Accessibility Guidelines)**

- Criada pelo **W3C (World Wide Web Consortium)**.
- Organiza os princípios de acessibilidade em **4 pilares**:

1. **Perceptível:** As informações devem ser apresentadas de forma que todos possam perceber (ex: texto alternativo para imagens).
2. **Operável:** A interface deve ser navegável de diversas formas (ex: teclado, voz).
3. **Compreensível:** O conteúdo deve ser claro e previsível.
4. **Robusto:** O sistema deve funcionar com diferentes tecnologias assistivas (ex: leitores de tela).

### 📱 **Diretrizes para Aplicativos Móveis:**

- **Google Material Design Accessibility Guidelines**.
- **Apple Human Interface Guidelines (HIG)**.

Esses guias trazem recomendações para garantir **acessibilidade em dispositivos móveis**.

------

## 🛠 **6.4 Implementando Acessibilidade no SGSA**

### 🔍 **Exemplos de Aplicação no SGSA:**

1. **Texto Alternativo para Imagens:**
   - Caso o **SGSA** tenha ícones ou imagens decorativas, adicionar **descrições (alt text)** para que leitores de tela possam descrever o conteúdo.
2. **Contraste de Cores:**
   - Garantir contraste suficiente entre **texto e fundo** para pessoas com baixa visão ou daltonismo.
   - Exemplo: Evitar usar texto cinza claro sobre fundo branco.
3. **Navegação por Teclado e Voz:**
   - Permitir que o **SGSA** seja totalmente navegável sem o uso do mouse, apenas com teclado ou comandos de voz (usado por pessoas com deficiência motora).
4. **Legenda em Vídeos:**
   - Caso haja tutoriais em vídeo no **SGSA**, incluir **legendas** para usuários com deficiência auditiva.
5. **Mensagens Claras:**
   - Evitar mensagens de erro genéricas como "Erro 404".
   - Preferir mensagens claras, como: "Aluno não encontrado. Verifique o nome digitado."
6. **Tamanhos Flexíveis de Fonte:**
   - Permitir que o usuário **aumente ou diminua o tamanho das fontes**.

------

## 🎮 **6.5 Ferramentas para Testar Acessibilidade**

- **Google Accessibility Scanner:** Analisa aplicativos Android e aponta melhorias.
- **VoiceOver (iOS)** / **TalkBack (Android):** Leitores de tela nativos dos sistemas.
- **Contrast Checker (WebAIM):** Verifica o contraste entre cores.

📚 **Dica Prática:**

- Simule o uso do **SGSA** com o **TalkBack** ativado e tente navegar **somente com teclado** para sentir na prática as dificuldades de um usuário com deficiência.

------

## 🔍 **6.6 Conclusão**

**Acessibilidade** não é um bônus – é um **direito**! Garantir que **todas as pessoas possam usar nossos aplicativos** é uma responsabilidade de qualquer desenvolvedor ou designer.

Com pequenas ações, como adicionar **texto alternativo** ou garantir **contraste adequado**, o **SGSA** pode se tornar uma ferramenta **inclusiva** e **eficiente** para **todos os professores e alunos**.

No próximo capítulo, vamos explorar a **Experiência do Usuário (UX)** para deixar o SGSA ainda mais agradável de usar! 🚀

------

# 🎯 **Fixação do Conteúdo**

## ✍️ **Questões Dissertativas**

1. Explique o que é **acessibilidade digital** e por que ela é importante em aplicativos móveis.
2. Quais são os **quatro princípios** das **WCAG** e como eles ajudam a tornar um aplicativo acessível?

## ❓ **Questões de Múltipla Escolha**

1. Qual das opções **não** é um exemplo de recurso de acessibilidade?
   - (A) Texto alternativo para imagens.
   - (B) Contraste adequado entre texto e fundo.
   - (C) Animações sem controle do usuário.
   - (D) Legendas em vídeos.
2. O que o **princípio "Operável"** da WCAG garante?
   - (A) Que o sistema funcione apenas com mouse.
   - (B) Que o sistema seja navegado por diversas formas (teclado, voz).
   - (C) Que o conteúdo tenha alto contraste.
   - (D) Que o sistema funcione offline.

## ✅ **Questões de Caixa de Seleção**

1. Quais das opções abaixo são **tecnologias assistivas**?
   -  TalkBack.
   -  VoiceOver.
   -  Spotify.
   -  Google Accessibility Scanner.
2. Quais das seguintes práticas ajudam a melhorar a acessibilidade?
   -  Permitir ajuste de tamanho da fonte.
   -  Adicionar textos alternativos a imagens.
   -  Usar apenas cores para diferenciar elementos.
   -  Garantir que o sistema seja navegável por teclado.

## 🔄 **Questões de Associação de Colunas**

Associe o tipo de deficiência com a solução de acessibilidade adequada:

1. (  ) Deficiência auditiva
2. (  ) Deficiência visual
3. (  ) Deficiência motora

(A) Navegação por teclado ou comandos de voz. (B) Leitores de tela. (C) Legendas em vídeos.

## ⚖️ **Questões de Verdadeiro ou Falso**

1. ( ) A acessibilidade digital beneficia apenas pessoas com deficiência.
2. ( ) O contraste de cores influencia diretamente na acessibilidade visual.

------

# 🏆 **Exercícios Práticos**

## 🏛 **Atividade em Sala de Aula**

1. Em grupos, analisem um **aplicativo conhecido** (ex: YouTube, WhatsApp) e apontem **dois pontos fortes** e **dois pontos fracos** em relação à acessibilidade.
2. Simulem a navegação do **SGSA** utilizando o **TalkBack** ou **VoiceOver** e listem as principais dificuldades encontradas.

## 🏡 **Atividade para Casa**

1. Escolha um site ou aplicativo e use o **Contrast Checker (WebAIM)** para verificar se o **contraste de cores** está adequado.
2. Crie uma **lista de melhorias** que poderiam ser implementadas no **SGSA** para torná-lo mais acessível.

------

💡 **Com esse capítulo, você está preparado para desenvolver aplicativos que incluam todas as pessoas, tornando o mundo digital mais justo e acessível!** 🚀