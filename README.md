# Caderno Temático no NotebookLM: Educação Financeira e Gestão de Crédito Responsável

## 📌 Contexto e Objetivos
Este repositório documenta o desenvolvimento de um Caderno Temático no Google NotebookLM, integrando Inteligência Artificial ao campo da Administração e Finanças Pessoais. 

O principal objetivo deste projeto é explorar ferramentas de **aprendizagem ativa** (como simulação de quizzes e geração de cenários de tomada de decisão) para fixar conceitos complexos de balanço patrimonial, modalidades de crédito e autorregulação bancária, superando o modelo de estudo passivo e linear.

---

## 📚 Curadoria de Fontes
As seguintes fontes oficiais e abertas foram selecionadas e carregadas no NotebookLM para compor a base de conhecimento do Caderno Temático:

1. **Guia CVM de Planejamento Financeiro (Comissão de Valores Mobiliários):** Aborda a estruturação do orçamento pessoal, cálculo de patrimônio líquido (ativos vs. passivos) e formação de reserva de emergência.
2. **Guia de Uso Responsável do Crédito (FEBRABAN):** Detalha as diferentes modalidades de crédito (cheque especial, consignado, CDC), o cálculo do Custo Efetivo Total (CET) e direitos do consumidor.
3. **Código de Defesa do Consumidor (Artigos sobre Serviços Financeiros):** Base legal que rege a transparência na oferta de crédito e proteção ao superendividamento.
4. **Normativos do Sistema de Autorregulação Bancária - SARB:** Diretrizes setoriais focadas nos princípios de ética, legalidade e adequação de produtos ao perfil do cliente.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Durante o treinamento e interação com o NotebookLM, foram documentados os seguintes testes de prompts e refinamentos de comandos:

### Tentativa 1 (Abordagem Direta - Resultado Linear/Passivo)
*   **Prompt utilizado:** *"Resuma quais são as modalidades de crédito listadas no guia da FEBRABAN."*
*   **Resultado da IA:** A ferramenta gerou uma lista textual crua definindo cada crédito (cheque especial, cartão, consignado).
*   **Cicatriz/Dificuldade:** O formato gerou leitura passiva. Descobriu-se que resumos puros não estimulam a retenção de longo prazo ou a capacidade analítica do profissional.

### Tentativa 2 (Abordagem Avançada - Resultado Ativo/Gamificado)
*   **Prompt utilizado:** *"Aja como um Gerente de Riscos focado no SARB. Cruzando os dados do guia da CVM e da FEBRABAN, crie um estudo de caso fictício onde um consumidor deficitário tenta contratar um empréstimo. Formule uma pergunta de múltipla escolha para testar a adequação do produto (Princípio do Crédito Responsável). Não me dê o gabarito agora."*
*   **Resultado da IA:** A IA reteve o gabarito e gerou uma simulação de tomada de decisão baseada em riscos operacionais e limite de comprometimento de renda (30% no consignado), forçando o raciocínio crítico imediato.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados do Assunto
*   **Gestão Patrimonial (CVM):** Organização financeira dividida em Balanço Patrimonial (riqueza atual baseada em ativos e passivos) e Fluxo de Caixa (controle mensal de receitas e despesas).
*   **Uso Inteligente do Crédito (FEBRABAN):** O crédito deve ser encarado como ferramenta de antecipação planejada e nunca como extensão do salário. Modalidades de curto prazo (como cheque especial) possuem juros punitivos elevados e devem ser restritas a emergências pontuais.
*   **Custo Efetivo Total (CET):** Indicador obrigatório determinado pelo Banco Central que unifica todos os encargos, taxas e juros de uma operação, sendo a única métrica real para comparação entre instituições.

### 2. Glossário de Conceitos Críticos
*   **Consumidor Deficitário:** Status financeiro em que as despesas mensais superam a receita, indicando falta de capacidade de poupança e risco iminente de inadimplência.
*   **Crédito Consignado:** Empréstimo com desconto direto em folha de pagamento, possuindo menor taxa de juros do mercado, mas limitado estritamente a 30% da renda do tomador.
*   **SARB (Autorregulação Bancária):** Sistema criado pela FEBRABAN que dita normas voluntárias de conduta para os bancos, indo além das obrigações puramente legais para garantir o respeito ao consumidor.

### 3. Prompts Reutilizáveis para Revisão Dinâmica
*   `Com base no manual da FEBRABAN, transforme as seções de 'Cuidados com o Cartão de Crédito e Nome' em 3 perguntas de simulação prática para um treinamento de atendimento ao cliente.`
*   `Extraia as regras de formação de Reserva de Emergência do Guia da CVM e cruze com os alertas de fraudes bancárias da FEBRABAN para montar um checklist preventivo de saúde financeira.`
