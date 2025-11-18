# Nexus Cidadão: Sistema de Combate à Desinformação

Este é o repositório principal do projeto **Nexus Cidadão**, a solução inédita para o Ideathon do Governo de Goiás - Desafio: Verdade ou Fake News?.

## Visão Geral

O Nexus Cidadão é um sistema de software completo que integra:
1.  **Blockchain (Hyperledger Fabric):** Para garantir a imutabilidade e transparência do processo de verificação de fatos.
2.  **Inteligência Artificial (PLN de Intenção):** Para analisar o contexto e o propósito da desinformação, fornecendo feedback educativo.
3.  **Aplicativo Móvel (Frontend):** Para engajar o cidadão na submissão de notícias e no consumo de conteúdo verificado.

## Estrutura do Projeto

*   `backend/api_gateway/`: Microsserviço principal (FastAPI) que orquestra as requisições.
*   `ia_module/pln_model/`: Módulo de IA de Análise de Intenção (Python/TensorFlow).
*   `blockchain_network/chaincode/`: Contratos Inteligentes (Chaincode) para o consenso de verificação.
*   `frontend/app_cidadao/`: Código-fonte do aplicativo móvel (React Native/Flutter).

## Manual de Instruções


## Tecnologias Chave

*   Python (FastAPI)
*   Hyperledger Fabric
*   React Native / Flutter
*   TensorFlow / PyTorch (para o modelo de IA)
*   PostgreSQL e Neo4j
