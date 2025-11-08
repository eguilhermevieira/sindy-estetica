# Plano de Conteúdo e Design para o Site Sindy Barrios

## 1. Design & UI

O design será **fluido, moderno e acolhedor**, com espaçamento generoso e foco na **confiança** e **saúde feminina**.

### Paleta de Cores Sugerida

A paleta combina tons neutros e terrosos (para seriedade e bem-estar) com um toque de rosa/vinho (para feminilidade e inspiração).

| Nome da Cor | Código HEX | Uso Principal |
| :--- | :--- | :--- |
| **Principal (Inspiração)** | `#A5526A` | Botões de CTA, Destaques, Títulos de Seção. |
| **Secundária (Acolhimento)** | `#F0D8D8` | Fundos de Seção, Elementos de Suporte. |
| **Neutro (Base)** | `#FFFFFF` | Fundo principal, Conteúdo de texto. |
| **Texto Principal** | `#333333` | Textos, Títulos. |
| **Destaque (Saúde)** | `#708D81` | Ícones, Linhas de Divisão, Elementos de Confiança. |

### Tipografia Sugerida

Serão utilizadas fontes do Google Fonts, garantindo carregamento rápido e licença de uso.

| Uso | Fonte Sugerida | Justificativa |
| :--- | :--- | :--- |
| **Títulos (Headlines)** | **Playfair Display** (Serif) | Elegante e profissional, transmite sofisticação e autoridade. |
| **Corpo de Texto** | **Poppins** (Sans-serif) | Moderna, limpa e altamente legível em todos os dispositivos (desktop e mobile). |

### Layout e Microinterações

*   **Layout:** Grid de 12 colunas para desktop, adaptando-se a 4 colunas no mobile. Uso de `flexbox` e `grid` para responsividade.
*   **Microinterações:**
    *   **Hover em CTAs:** Leve aumento de escala e mudança sutil de cor de fundo (de `#A5526A` para um tom ligeiramente mais escuro) para indicar interatividade e convidar ao clique. *Impacto na Usabilidade: Feedback visual imediato, aumentando a taxa de conversão.*
    *   **Transição Suave:** Uso de `transition: all 0.3s ease-in-out;` em elementos como cards de serviço e links para evitar mudanças bruscas e tornar a navegação mais agradável. *Impacto na Usabilidade: Sensação de fluidez e polimento profissional.*
    *   **Carrossel:** Transição suave entre slides, pausa automática ao *hover* ou foco, e *swipe* responsivo para mobile. *Impacto na Usabilidade: Acessibilidade e experiência intuitiva para visualização das provas sociais.*

## 2. Estrutura de Conteúdo (Copy)

### Seção 1: Hero (Acima da Dobra)

| Elemento | Conteúdo Sugerido |
| :--- | :--- |
| **Headline Forte** | **Sua Saúde, Sua Autoestima. Transformadas.** |
| **Sub-headline** | Cosmetologia e Estética Avançada com foco em resultados reais e bem-estar feminino. Descubra o poder da sua melhor versão, com ciência e acolhimento. |
| **CTA Principal** | **Agende Sua Avaliação Personalizada** (Link WhatsApp) |
| **CTA Secundário** | **Veja Nossos Resultados Reais** (Âncora para a seção Resultados) |

### Seção 2: Serviços (O que fazemos)

Foco em 3 pilares principais, baseados na análise das imagens:

1.  **Modelagem Corporal Avançada:** Redução de medidas e gordura localizada com tecnologias não invasivas (Criolipólise, Radiofrequência, Eletroterapia). *Copy: "Corpo esculpido com tecnologia e segurança, sem cirurgia. Resultados comprovados pela ciência."*
2.  **Saúde e Bem-Estar Feminino:** Tratamentos que vão além da estética, focando em autoestima, melhora da circulação e qualidade de vida. *Copy: "Cuidado integral que nutre sua confiança. Sua jornada de bem-estar começa aqui."*
3.  **Tratamentos Faciais e Skincare:** Personalização de rotinas e procedimentos para uma pele saudável e radiante. *Copy: "A beleza da sua pele com protocolos exclusivos e ativos de alta performance."*

### Seção 3: Resultados (Carrossel de Provas Sociais)

*   **Título:** **Resultados Reais. Autoestima Renovada.**
*   **Subtítulo:** Veja a transformação que o método Sindy Barrios proporciona. *As imagens serão carregadas dinamicamente da pasta `assets/proofs`.*
*   **Microcopy:** "Todas as imagens são de clientes reais, com consentimento. O seu resultado é o nosso próximo foco."

### Seção 4: Sobre Sindy Barrios

*   **Título:** **Sindy Barrios: Estética com Propósito.**
*   **Copy:** Sindy Barrios é Cosmetóloga e Esteticista, dedicada a promover a saúde e a autoestima feminina através de um olhar integral. Sua abordagem combina o que há de mais avançado em tecnologia estética com um profundo acolhimento, garantindo que cada tratamento seja uma etapa na construção da melhor versão de suas clientes. Mais do que procedimentos, Sindy oferece uma jornada de autoconhecimento e empoderamento.

### Seção 5: Artigos/Evidências Científicas

*   **Título:** **Estética Baseada em Ciência. Sua Segurança em Primeiro Lugar.**
*   **Conteúdo:** Apresentação das 5 referências científicas compiladas na Fase 2, com título, autores, link e a relevância prática para a cliente. (O conteúdo final será formatado em HTML com links e citações).

### Seção 6: FAQs (Perguntas Frequentes)

1.  **Os tratamentos são dolorosos?** (Resposta: Não, são minimamente invasivos e o conforto é prioridade.)
2.  **Quanto tempo dura uma sessão?** (Resposta: Varia de 30 a 90 minutos, dependendo do protocolo.)
3.  **Qual a diferença do seu trabalho para o de uma clínica comum?** (Resposta: Foco na saúde integral, personalização do protocolo e base científica.)
4.  **Os resultados são permanentes?** (Resposta: Os resultados são duradouros, mas dependem da manutenção de hábitos saudáveis e acompanhamento.)
5.  **Como faço para agendar?** (Resposta: Clique no botão do WhatsApp para falar com nossa equipe e agendar sua avaliação.)

### Seção 7: Contato/Agenda

*   **CTA Final:** **Pronta para a Sua Transformação?**
*   **Formulário:** Nome, E-mail, WhatsApp (opcional).
*   **CTA do Formulário:** **Quero Agendar Minha Avaliação**

## 3. Documentação

### Estrutura do `README.md`

1.  **Visão Geral do Projeto:** Breve descrição do site e seus objetivos.
2.  **Estrutura de Arquivos:** Explicação da organização da pasta (HTML, CSS, JS, Assets).
3.  **Checklist de Aceitação (QA):**
    *   **Responsividade:** Testado em Mobile (≤600px), Tablet (601–1024px), Desktop (>1024px).
    *   **Acessibilidade (WCAG AA):** Navegação por teclado, contraste de cores, marcação ARIA.
    *   **Performance:** Pontuação alta no Lighthouse (velocidade, otimização de imagens).
    *   **Provas Sociais:** Carrossel funcional, usando apenas as imagens fornecidas.
    *   **Referências Científicas:** 5+ artigos citados e linkados.
4.  **Guia de Atualização de Conteúdo:**
    *   **Como Trocar Textos/Imagens:** Instruções claras sobre onde editar o `index.html` e a pasta `assets`.
    *   **Como Adicionar Provas Sociais:** Instruções sobre como nomear e adicionar novas imagens à pasta `assets/proofs` e como o carrossel as carrega.
    *   **Como Atualizar Referências Científicas:** Onde adicionar novos artigos na seção de evidências.
5.  **Instruções de Uso do Snippet do Carrossel:** Código e passos para incorporar o carrossel em um CMS.

### Checklist de Aceitação (Conteúdo)

| Item | Status | Observações |
| :--- | :--- | :--- |
| Site single-page (HTML) | Pendente | Será implementado na Fase 4. |
| Botão para WhatsApp | Pendente | Será implementado na Fase 4. |
| Organização em Seções | Pendente | Hero, Serviços, Resultados, Sobre, Artigos, FAQs, Contato, Rodapé. |
| Carrossel de Provas Sociais | Pendente | Funcional, com navegação, swipe e autoplay pausado. |
| Uso de Provas Sociais Reais | Concluído | As 14 imagens fornecidas serão usadas. |
| Comentários no Código | Pendente | Para facilitar a manutenção. |
| Paleta de Cores/Tipografia | Concluído | Definidas acima. |
| Pesquisa de Referência | Concluído | 3 sites analisados (JK, Onodera, Behance). |
| Evidência Científica | Concluído | 5 artigos selecionados. |
| Documentação (README) | Pendente | Estrutura definida. |
| Versão Modular (Componentes) | Pendente | Estrutura do HTML será modular para facilitar migração. |

---
**Próxima Fase:** Inicializar o projeto web e começar o desenvolvimento do código.
