# Fase 4 – Modelação e Processamento de Dados

Nesta fase, foi definido como os dados são guardados, processados e apresentados. Também foi feita a modelação da estrutura dos dados e criada uma solução com dashboard (usando o Node-RED) para visualizar a informação recolhida.

## Alterações aos Requisitos Iniciais
- [Indica aqui se houve alguma alteração face ao que estava planeado no início.]

## Diagrama da Arquitetura Final
- [Inserir imagem ou link para o diagrama que mostra os componentes da solução: sensores, Orion, base de dados, Node-RED, etc.]

## Dados Guardados
- Foram definidos os tipos de dados recebidos (ex: distância, deteção de movimento, temperatura).
- Também foi definido de onde vêm e com que frequência são enviados.
- Os dados são recebidos automaticamente quando mudam (via subscrição).

## 🧱 Estrutura dos Dados
- Foi seguido o formato de dados da FIWARE.
- Cada dado tem um nome, tipo (ex: número ou texto), valor e data de registo.
- Os dados são guardados automaticamente numa base de dados MongoDB através do Orion Context Broker.

## 📊 Dashboards Criados
- Foram feitas páginas no Node-RED com gráficos e informações em tempo real.
- Mostram, por exemplo, a distância lida por sensores ou se houve movimento.

## 🌐 Link da Solução
> http://localhost:1880  
> (Ou outro link se estiver num servidor)

## 📝 O que foi feito nesta fase
- Criado o modelo dos dados com base nos sensores utilizados.
- Configurado o Orion para guardar os dados automaticamente.
- Ligado o Node-RED para receber as notificações e mostrar os valores.
- Testado o envio, receção e visualização dos dados com sucesso.

