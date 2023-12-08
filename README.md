# Recomendação de Música usando Databricks e API do Spotify

## Visão Geral

Este projeto tem como objetivo criar um sistema de recomendação de música utilizando a plataforma Databricks e a API do Spotify. As etapas iniciais do projeto incluem a importação dos dados e a análise exploratória desses dados. A próxima fase do projeto será a clusterização para identificar padrões e agrupar músicas semelhantes.

## Etapas Concluídas

1. **Importação de Dados:**
   - Os dados foram coletados utilizando a API do Spotify, incluindo informações como artistas, gêneros, popularidade, etc.
   - Os dados foram importados para o ambiente Databricks para análise.

2. **Análise de Dados:**
   - Realizamos uma análise exploratória para entender a distribuição dos dados.
   - Identificamos tendências, outliers e características importantes para o processo de recomendação.

## Próximas Etapas

### 3. Clusterização

   - **Objetivo:** Agrupar músicas semelhantes com base em características como gênero, ritmo, popularidade, entre outros.

   - **Método:**
      - Utilizaremos algoritmos de clusterização, como K-means, para agrupar as músicas.
      - A escolha do número ideal de clusters será feita com base em métricas de desempenho.

   - **Implementação:**
      - Criaremos pipelines no Databricks para facilitar a execução e monitoramento da clusterização.
      - Ajustaremos os parâmetros do algoritmo para otimizar os resultados.

### 4. Sistema de Recomendação

   - **Objetivo:** Desenvolver um sistema de recomendação personalizado com base nos clusters identificados.

   - **Método:**
      - Utilizaremos técnicas de recomendação, como filtragem colaborativa ou baseada em conteúdo, para sugerir músicas com base nos gostos do usuário.

   - **Implementação:**
      - Integraremos o sistema de recomendação com a plataforma Databricks.
      - Testaremos e refinaremos o sistema com feedback contínuo.

## Como Contribuir

Se você deseja contribuir para este projeto, siga estas etapas:

1. Faça um fork do repositório.
2. Crie uma branch para suas alterações (`git checkout -b feature/nova-feature`).
3. Faça as alterações desejadas e faça commit (`git commit -m 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um pull request para revisão.

## Contato

Para dúvidas, sugestões ou colaborações, entre em contato:

- Nome: Patrícia
- Email: patricia.junqueira11@gmail.com

Agradecemos por contribuir para o desenvolvimento deste projeto!
