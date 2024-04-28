
# Azure Cognitive Search
## Passo a passo para configurar uma pesquisa

1. **Criação de Recursos no Azure:**
   - Acesse o portal do Azure.
   - Crie um recurso Azure AI Search com as configurações necessárias: assinatura, grupo de recursos, nome do serviço, localização e nível de preços.
   - Crie um recurso Azure AI Services na mesma localização do recurso Azure AI Search, com as configurações apropriadas.
   - Crie uma conta de armazenamento (Storage Account) com os contêineres Blob necessários.

2. **Extração e Armazenamento de Dados:**
   - Faça o upload dos documentos de revisão para um contêiner Blob na sua conta de armazenamento.
   - Extraia os dados do contêiner Blob e armazene-os.

3. **Indexação dos Documentos:**
   - Utilize o Azure AI Search para criar um índice e indexar os documentos armazenados.
   - Configure o processo de indexação para extrair insights usando habilidades de IA, como extração de frases-chave, detecção de sentimentos, etc.

4. **Consulta ao Índice:**
   - Utilize a ferramenta Search Explorer no portal do Azure para testar consultas ao índice.
   - Escreva consultas para recuperar documentos com base em critérios específicos, como localização ou sentimento.

5. **Exploração de Insights:**
   - Acesse a Knowledge Store para explorar os dados enriquecidos pela IA.
   - Analise as projeções de objetos e tabelas geradas pela AI para entender os insights extraídos, como frases-chave, entidades detectadas, etc.
   - Examine as imagens e outros dados relacionados armazenados na Knowledge Store para obter insights adicionais.

**Ferramentas Beneficiadas:**
- **Azure AI Search:** Para criar o índice de pesquisa e realizar consultas.
- **Azure AI Services:** Para enriquecer os dados com insights de IA.
- **Azure Storage:** Para armazenar os documentos originais e os dados indexados.
- **Search Explorer:** Para testar e validar consultas ao índice de pesquisa.
- **Knowledge Store:** Para explorar e analisar os insights extraídos dos documentos.

**Aprendizados Adquiridos:**
- Configuração e uso de recursos do Azure para criação de índices de pesquisa e enriquecimento de dados com IA.
- Processo de indexação de documentos e consulta aos índices para recuperar informações relevantes.
- Exploração dos insights extraídos pela IA na Knowledge Store, incluindo projeções de objetos, tabelas e outros dados enriquecidos.

