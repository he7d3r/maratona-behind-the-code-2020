# Desafio

## Proposta

A proposta do desafio da Fiat Chrysler Automobiles encontra-se no submódulo
"desafio".

## Solução

Para a solução do desafio na plataforma da *IBM Cloud*, foi criado um modelo
no Watson Knowledge Studio para anotação de texto em linguagem natural. Depois,
foi utilizado o *Node-RED* (ver [nlu-flow.json](solução/nlu-flow.json)) para
construir uma API de análise de sentimentos e recomendação, integrada com os
serviços *Watson Natural Language Understanding* e *Watson Speech-to-Text*
(*STT*), como ilustrado a seguir:

<div align="center">
<img width="90%" src="./solução/screenshot-node-red.png" alt='Screenshot do fluxo do Node-RED'>
</div>
