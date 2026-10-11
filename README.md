---

## 📋 Requisitos e Documentação do Projeto (Santander / DIO)

### 1. Perguntas de Negócio Escolhidas e Justificativa
- **Qual é o volume financeiro total (Receita em USD) e a quantidade de veículos vendidos?** *(Para avaliar o faturamento global da base sanitizada)*.
- **Qual é o ticket médio e a quilometragem média dos veículos?** *(Para entender o padrão de preço e o perfil de uso/desgaste dos carros comercializados)*.
- **Como a receita se distribui por modelos específicos?** *(Para identificar quais linhas de veículos geram maior impacto financeiro)*.
- **Qual é a concentração geográfica e a forma de pagamento predominante?** *(Para orientar estratégias comerciais, canais de financiamento e logística regional)*.

### 2. Prompt Utilizado e Evolução até a Versão Final
- **Prompt Inicial:** *"Crie uma dashboard interativa em HTML/CSS/JavaScript em arquivo único para exibir dados de vendas de veículos Porsche, contendo KPIs de receita, ticket médio, quilometragem, além de filtros dinâmicos por modelo, cidade, ano e forma de pagamento."*
- **Evolução e Ajustes:** Na versão final, refinamos o script para garantir que os cartões de KPIs recalculem os valores matemáticos de forma totalmente síncrona com os seletores de filtros, além de aplicar uma identidade visual corporativa escura com gráficos dinâmicos.

### 3. Tratamento da Base de Dados Antes da IA
- **Sanitização de Registros:** A base continha 100 linhas originais, das quais 24 apresentavam datas inválidas ou inconsistentes e foram excluídas de todas as métricas analíticas, restando **76 vendas válidas**.
- **Padronização:** Uniformização das colunas de preços em dólares americanos (USD), quilometragem em milhas e criação de listas categóricas para os filtros de interface.
- **Segurança de Dados:** Nenhuma informação sensível de clientes (PII) foi incluída, permitindo que a base fosse estruturada de forma segura para o arquivo de visualização web.

### 4. Ferramentas Utilizadas
- **IA e Desenvolvimento:** Utilizado o **ChatGPT com Canvas** para a estruturação iterativa do layout e lógica de filtragem em JavaScript.
- **Hospedagem e Publicação:** **GitHub Pages**.

### 5. Endereço da Dashboard Publicada
- 🌐 **Link de Acesso (GitHub Pages):** https://github.com/ailton0015/trabalho-porsche
