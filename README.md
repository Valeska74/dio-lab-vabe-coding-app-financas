# dio-lab-vabe-coding-app-financas
Um aplicativo de gestão de finanças pessoais inovador que combina inteligência artificial com uma interface conversacional intuitiva. Controle seus gastos e receitas através de conversas naturais em português brasileiro, receba categorização automática de transações e acompanhe suas metas financeiras com feedback inteligente.
# Documento de Requisitos de Produto (PRD) - App de Organização de Finanças Pessoais

## 1. Introdução

Este Documento de Requisitos de Produto (PRD) descreve um aplicativo inovador de organização de finanças pessoais, projetado para simplificar o controle financeiro através de uma interface de conversação em linguagem natural. O objetivo é oferecer uma experiência intuitiva e acessível, eliminando a necessidade de formulários complexos ou planilhas manuais.

## 2. Contexto

O aplicativo visa transformar a maneira como os usuários interagem com suas finanças, permitindo o registro e a gestão de gastos por meio de conversas em linguagem natural. Esta abordagem visa facilitar o controle financeiro de forma simples e natural, tornando-o mais acessível a um público amplo.

## 3. Problema a Ser Resolvido

Muitas pessoas desistem de controlar seus gastos devido à complexidade e à necessidade de entrada manual de dados em aplicativos financeiros tradicionais. Este projeto busca resolver essa dor, oferecendo uma experiência de conversação fluida e recomendações automáticas de economia, incentivando a adesão e a consistência no controle financeiro.

## 4. Público-Alvo

O público-alvo são indivíduos que desejam organizar suas finanças de forma prática e sem complicações, especialmente aqueles que se sentem sobrecarregados por métodos convencionais e buscam uma solução mais amigável e interativa.

## 5. Funcionalidades-Chave

As funcionalidades essenciais do aplicativo incluem:

1.  **Registro de Gastos via Chat:** Os usuários poderão registrar suas despesas e receitas por meio de conversas em linguagem natural, como "Gastei 50 reais no almoço" ou "Recebi meu salário de 3000 reais".
2.  **Classificação Automática de Transações:** O sistema classificará automaticamente as transações com base no contexto da conversa e em padrões de gastos, permitindo uma visão clara das categorias de despesas.
3.  **Definição e Acompanhamento de Metas Financeiras:** Os usuários poderão definir metas de economia e o aplicativo fornecerá feedback e progresso em tempo real através do chat.
4.  **Dicas de Economia com "Agente Financeiro":** Um assistente virtual, o "Agente Financeiro", oferecerá dicas personalizadas de economia e insights financeiros baseados nos hábitos do usuário.
5.  **Visualização de Relatórios Simples e Personalizados:** Relatórios claros e gráficos intuitivos serão gerados para que os usuários possam visualizar seu desempenho financeiro de forma compreensível.

## 6. Entregável da IA (para Lovable)

Para a plataforma Lovable, o entregável esperado é um plano de MVP (Produto Mínimo Viável) que inclua:

*   **Principais Telas:** Esboços das telas principais (Dashboard, Chat, Metas, Perfil), com foco na experiência do usuário e na fluidez da interação.
*   **Recursos Necessários:** Identificação dos recursos de UI/UX (componentes, ícones, tipografia) e dados (estruturas de dados para transações, metas) que serão utilizados.
*   **Esboço de Validação Inicial:** Um plano para testar as funcionalidades centrais com um grupo de usuários, coletando feedback para futuras iterações.
*   **Vibe Visual:** Sugestão de um estilo visual (ex: minimalista, cores suaves, dark mode opcional) e uma "vibe" de interação (amigável, encorajadora, eficiente) que o Lovable deverá capturar. Considerar o uso de React/Tailwind para a implementação.

## 7. Sugestões para Vibe Coding e Lovable

Para otimizar a geração no Lovable, é crucial fornecer informações que ajudem a IA a entender a "vibe" do projeto. Além das funcionalidades, considere incluir:

*   **User Stories Detalhadas:** Exemplo: "Como usuário, quero registrar um gasto de almoço de R$50,00 dizendo 'Gastei 50 reais no almoço' para que o aplicativo categorize automaticamente como 'Alimentação' e atualize meu saldo."
*   **Estilo de Design:** "O aplicativo deve ter um design limpo e moderno, com foco na usabilidade. Cores predominantes: tons de azul e verde para transmitir confiança e tranquilidade. Tipografia: Sans-serif, legível e amigável."
*   **Fluxo de Interação:** Descrever o fluxo de uma conversa típica, como o aplicativo responde e guia o usuário.
*   **Tecnologias Implícitas:** Mencionar que a interface será construída com componentes React e estilizada com Tailwind CSS, o que pode guiar a IA na escolha de bibliotecas e padrões de código.
*   **Design Universal:** O aplicativo deve ser projetado para ser acessível e utilizável pelo maior número possível de pessoas, independentemente de suas habilidades, idade ou contexto de uso. Isso inclui considerar contraste de cores, tamanhos de fonte ajustáveis, navegação por teclado, compatibilidade com leitores de tela e legendas para qualquer conteúdo de áudio/vídeo. A IA deve priorizar a implementação de padrões de acessibilidade desde o início.

Este PRD revisado oferece uma base sólida para o desenvolvimento do aplicativo, com informações mais detalhadas e direcionadas para a utilização eficaz de ferramentas como o Lovable, aproveitando o conceito de Vibe Coding para uma geração de código mais alinhada com a visão do produto.

Uma breve reflexão sobre o processo:
O desenvolvimento do Finanças Vibe Chat seguiu uma abordagem estruturada e bem planejada, começando com a definição clara dos requisitos através do PRD (Product Requirements Document), passando pela implementação das funcionalidades e finalizando com testes e documentação. 
O projeto resultante reflete exatamente o que eu imaginava: um assistente financeiro que entende linguagem natural e torna o controle de gastos simples e intuitivo.
O que não funcionou como esperado?
Honestamente, tudo funcionou muito bem! Mas se eu tivesse que mencionar algo, seria:
Algumas funcionalidades como "dicas personalizadas do Agente Financeiro" ainda precisam de refinamento.
Gostaria de ter testado o aplicativo de forma mais interativa durante o desenvolvimento para validar se a experiência de usuário estava realmente alinhada com minha visão.
Seria útil ter dados de exemplo pré-carregados para visualizar como o dashboard fica com transações reais.
Encontrado ponto de fricção na manutenção de dados incluídos, que necessitou de algumas tentativas de ajuste para acolhimento de pedidos de exclusão.
O que funcionou bem?
O chat funciona exatamente como imaginei - simples, intuitivo e em português brasileiro. Consegui conversar naturalmente sobre meus gastos.
As cores com alto contraste, navegação por teclado e compatibilidade com leitores de tela tornaram o app verdadeiramente inclusivo, como eu solicitei.
Os gráficos de evolução temporal, distribuição por categoria e visualização de metas são exatamente o que eu precisava para entender minha situação financeira rapidamente.
O sistema de login com OAuth me dá confiança de que meus dados financeiros estão protegidos.
A estrutura do projeto é clara e bem documentada, facilitando futuras melhorias e manutenção.
A documentação gerada é profissional e deixa claro como o projeto funciona e como contribuir.
