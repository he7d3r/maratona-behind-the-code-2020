# Desafio

## Proposta

A proposta do desafio da Fiap encontra-se no submódulo "desafio".

## Solução

Para a solução do desafio na plataforma da *IBM Cloud*, foi utilizado um
Jupyter notebook em Python ([extração.ipynb](solução/extração.ipynb)) para
extrair os dados dos websites propostos e convertê-los para o formato JSON.
Esta [coleção de arquivos JSON](solução/dados) foi carregada no
*Watson Discovery*, juntamente com algumas [perguntas](solução/perguntas)
relevantes ao conteúdo de cada documento, para treinar um modelo capaz de
recomendar artigos ou vídeos baseados no interesse do usuário.

**Observação**: Infelizmente não foi feito backup da coleção nem das anotações
no *Watson Discovery*, então o diretório da solução contém apenas o código em
Python usado na etapa de extração dos dados, e um rascunho das perguntas.
