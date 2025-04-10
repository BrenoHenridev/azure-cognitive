# Azure Cognitive

Este repositório contém um exemplo de como configurar e utilizar a **Pesquisa Cognitiva do Azure (Azure Cognitive Search)** para enriquecer documentos com IA e permitir buscas inteligentes.

---

## Passo a passo para configurar a Pesquisa Cognitiva

### 1. Criar o serviço no Azure
- Acesse o [portal do Azure](https://portal.azure.com)
- Busque por **Azure Cognitive Search**
- Clique em **"Criar"**
- Preencha os dados:
  - Nome do serviço
  - Grupo de recursos
  - Localização
  - Tipo de preço (gratuito para testes)

### 2. Criar um recurso de Armazenamento
- Crie um **Azure Blob Storage**
- Envie documentos para um container (PDFs, imagens, DOCX, etc.)

### 3. Configurar o Índice de Pesquisa
- Volte ao serviço de Pesquisa Cognitiva
- Vá em **"Importar dados"**
- Escolha o **Azure Blob Storage** como fonte
- Conecte sua conta de armazenamento
- Configure:
  - **Indexer**: define como os dados serão lidos
  - **Skillset**: conjunto de habilidades cognitivas (OCR, idioma, sentimento, frases-chave, etc.)
  - **Index**: estrutura final de pesquisa

### 4. Testar sua busca
- Utilize o **explorador de pesquisa** na interface do Azure
- Faça buscas por termos, frases ou até categorias extraídas
- Veja os resultados enriquecidos com inteligência artificial

---

## Possibilidades e ferramentas que se beneficiam

- **Aplicações Web e Mobile** → busca inteligente com compreensão semântica
- **Sistemas Jurídicos e Financeiros** → análise automatizada de contratos e faturas
- **Portais de conhecimento corporativo** → indexação de manuais, PDFs e documentos técnicos
- **Power BI** → visualizações com base em dados extraídos por IA
- **Chatbots e assistentes virtuais** → base de conhecimento rica e semântica

---

## Aprendizados

Durante a criação e experimentação com a Pesquisa Cognitiva do Azure, foi possível aprender que:

- A **IA pode enriquecer automaticamente documentos** com informações úteis (entidades, sentimento, idiomas, etc.)
- A ferramenta é **flexível e poderosa**, ideal para lidar com grande volume de dados
- É possível integrar com outras ferramentas Microsoft (como **Power Platform**, **Azure Functions**, **Logic Apps**, etc.)
- **Não é necessário programar para testar os recursos** — o Language Studio e os assistentes de configuração facilitam muito o uso

---

## Próximos passos

- Automatizar a indexação de novos documentos via Azure Functions
- Integrar a busca com uma aplicação Angular/React
- Aplicar filtros personalizados e recomendações baseadas em IA

---
