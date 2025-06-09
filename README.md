# Fase 4 – Modelação e Processamento de Dados

Nesta fase, foi definido como os dados são guardados, processados e apresentados. Também foi feita a modelação da estrutura dos dados e criada uma solução com dashboard (usando o Node-RED) para visualizar a informação recolhida.

## NOTA IMPORTANTE:
- Nota: Para correr a solução do Node-Red vai ser necessário instalar os seguintes nodes do Manage palette:
    - node-red-dashboard
    - @flowfuse/node-red-dashboard

## Ficheiros necessários para o download correcto do projecto (Node-Red):
- Node_Red_flows.json -- json que contem os flows do Node red e dos seus respetivos módulos.
- docker-compose.yml -- yaml que contém o Node Red, Orion Fiware e Mongo DB.
    - NOTA: Para correr o .yml é preciso por este comando: docker compose up -d. Fizemos um docker com  persistência de dados para o MongoDB.

## Ficheiros para o download se necessário verificar o código do ttgo:
- sistema_introsao.rar -- contem o json do payload formatters do TTN mais o código em micropython (Pycom) do TTGO

## Alterações aos Requisitos Iniciais
- 

## Diagrama da Arquitetura Final
- 

## Dados Guardados
- Foram definidos os tipos de dados recebidos (ex: distância, deteção de movimento).
- Também foi definido de onde vêm e com que frequência são enviados.
- Os dados são recebidos automaticamente quando mudam (via subscrição).

## Estrutura dos Dados
- Foi seguido o formato de dados da FIWARE.
- Cada dado tem um nome, tipo (ex: número ou texto), valor e data de registo.
- Os dados são guardados automaticamente numa base de dados MongoDB através do Orion Context Broker.

## Dashboards Criados
- Foram feitas páginas no Node-RED com gráficos e informações em tempo real.
- Mostram, por exemplo, a distância lida por sensores ou se houve movimento.

## Link da Solução (Dashboad)
> http://nodered:1880/dashboard/page1 ou http://localhost:1880/dashboard/page1 
> (Se estiver ligado a um docker Ou outro link se estiver num servidor)

## O que foi feito nesta fase
- Criado o modelo dos dados com base nos sensores utilizados.
- Configurado o Orion para guardar os dados automaticamente.
- Ligado o Node-RED para receber as notificações e mostrar os valores.
- Testado o envio, receção e visualização dos dados com sucesso.

