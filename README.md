# Teste A/B para E-Commerce

![Image1](/images/test_ab_image.jpg)

## Problema de Negócio

<p>A Electronic House é um comercio online ( e-commerce ) de produtos de
informática para casas e escritórios. Os clientes podem comprar mouses,
monitores, teclados, computadores, laptops, cabos HDMI, fones de ouvido,
cameras webcam, entre outros, através de um site online e recebem os produtos
no conforto de suas casas.</p>

<p>O Diretor de Produtos Global pediu ao Head de Design que desenvolvesse uma
nova forma de finalizar a compra com cartão de crédito, sem a necessidade do
cliente preencher manualmente todas as informações do cartão e que
funcionasse em todos os países.</p>

<p>O Head de Designer gostaria de medir a efetividade do novo dispositivo de
preenchimento automático dos dados do cartão de crédito na página de vendas
e reportar os resultados ao Diretor de Produtos Global, para concluir se a nova
forma de pagamento é realmente melhor do que a antiga.</p>

## Desafio

<p>Depois de alguns meses de experimento, o time de Designers da Electronic
House, precisa avaliar os resultados do experimento realizado, a fim de concluir
qual era a forma de pagamento mais eficaz.</p>
<p>Porém, o time não possui as habilidades necessárias para avaliar os dados e
concluir o experimento. Nesse contexto, o desafio como Cientista de
Dados é ajudar o time de Designers a validar a efetividade do novo meio de
pagamento, com mais confiança e rigidez na análise.</p>

## Suposições de Negócio

-> O time de negócio espera um lift de 15% no faturamento com a página nova.

## Dados Disponíveis

| Atributos  |  Descrição |
| ------------------- | ------------------- |
|  uid |  ID do Cliente |
|  country |  País onde foi feita a compra |
|  gender |  Gênero do Cliente |
|  spent |  Valor Gasto para o Cliente |
|  purchases |  Quantidade de Compras |
|  date |  Data da Compra |
|  group | Grupo a qual o cliente foi colocado. A = Preenchimento Automático; B = Preenchimento Manual |
|  device | Dispositivo utilizado na compra. I = Compra Feita através do Site; A = Compra feita pelo App |

## Resultados Obtidos

<p>Foi necessária uma análise aprofundada por país para identificarmos a efetividade das páginas.</p>

No México a nova página tem o potencial de **aumentar o faturamento da empresa em $ 1.569.801,00**
<br>
Na Áustria a nova página tem o potencial de **aumentar o faturamento da empresa em $ 287.517,00**

**Totalizando um Aumento na Receita da empresa de $ 1.857.318,00**

<p>Nos demais países foi possível identificar uma queda significativa de performance no faturamento. Portanto, não é recomendado a alteração para a nova página.</p>


