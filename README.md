# Sensus


## Descrição

O projeto Sensus consiste no desenvolvimento de uma solução baseada em inteligência artificial para análise do ambiente em tempo real. A proposta utiliza a câmera de um dispositivo de realidade estendida como meio de captura de imagens, que são posteriormente processadas por um sistema de IA.

O objetivo é interpretar o ambiente ao redor do usuário, identificando objetos, obstáculos e elementos relevantes, contribuindo para uma melhor compreensão do espaço. O projeto possui caráter educacional e está inserido no contexto da disciplina de Soluções Web.

---

## Objetivo

- Capturar imagens do ambiente por meio de um dispositivo com câmera  
- Processar essas imagens utilizando inteligência artificial  
- Identificar elementos relevantes no ambiente  
- Retornar informações que auxiliem o usuário na interpretação do espaço  

---

## Arquitetura do Sistema
---

## Tecnologias Utilizadas

### Frontend
- JavaScript  
- WebXR  
- APIs de captura de mídia (getUserMedia)

### Backend
- Java  
- Spring Boot  
- API REST  

### Inteligência Artificial
- Python  
- Bibliotecas de visão computacional  

---

## Funcionamento

O sistema opera a partir da captura de imagens do ambiente por meio do dispositivo XR. Essas imagens são enviadas ao backend, que realiza a comunicação com o serviço de inteligência artificial responsável pelo processamento.

A IA analisa os dados recebidos e retorna informações sobre o ambiente, que são então exibidas ao usuário. Esse processo ocorre de forma contínua, permitindo uma análise dinâmica do espaço.

---

## Estrutura do Projeto
---

## Execução

Para execução do projeto, é necessário:

1. Iniciar o backend em Java (Spring Boot)  
2. Iniciar o serviço de IA em Python  
3. Executar o frontend no navegador do dispositivo XR  
4. Garantir que todos os serviços estejam na mesma rede  

---

## Requisitos

- Dispositivo com suporte a WebXR (Meta Quest)  
- Ambiente Java configurado  
- Ambiente Python configurado  
- Conexão em rede entre os serviços  

---

## Contexto Acadêmico

Este projeto foi desenvolvido como parte da disciplina de Soluções Web, com o objetivo de aplicar conceitos de integração entre frontend, backend e serviços de inteligência artificial em um cenário prático.

---

## Autores

Projeto desenvolvido para fins acadêmicos.
