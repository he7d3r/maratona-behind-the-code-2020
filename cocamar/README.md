# Desafio

## Proposta

A proposta do desafio da Cocamar encontra-se no submódulo "desafio".

## Solução

Para a solução do desafio na plataforma da *IBM Cloud*, foi utilizado o *Watson
Studio* para treinar um modelo de *Visual Recognition* com base em:

* 57 imagens da classe `lagarta`
* 59 imagens da classe `percevejo_marrom`
* 53 imagens da classe `percevejo_pequeno`
* 96 imagens da classe `percevejo_verde`
* 78 imagens da classe `Negative`

O modelo de inteligencia artificial resultante foi utilizado para classificar
imagens em uma aplicação web implementada com o Cloud Foundry.

**Observação**: As imagens não foram incluídas neste repositório pois, embora
possam ser obtidas na internet, nem todas estão sob domínio público ou sob uma
licença livre. Para encontrar tais imagens, pode ser usado tanto o Google
Images, quanto os sites que constam no arquivo
[websites.yml](solução/websites.yml).
