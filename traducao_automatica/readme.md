## Pergunta 1: 

- Tente valores diferentes do argumento num_examples na funçãoload_data_nmt. Como isso afeta os tamanhos do vocabulário do idioma de origem e do idioma de destino?

(Tem print no notebook)

Resposta: Podemos chegar na conclusão que quanto maior o número de exemplos que colocamos, maior vai ser o tamanho do vocabulário de Origem e de Destino

## Pergunta 2: 

- O texto em alguns idiomas, como chinês e japonês, não tem indicadores de limite de palavras (por exemplo, espaço). A tokenização em nível de palavra ainda é uma boa ideia para esses casos? Por que ou por que não?

Para o japonês e pro Chinês em que não possui o espaço entre as palavras, a tokenização em nível de palavra não seria eficiente, já que determinar onde uma palavra começa e termina é muito ambíguo sem delimitadores aparente.

### Texto em japonês

![Texto em japones](img/citacoes-em-japones-e-traducoes-em-ingles_503645-569.webp)

### Texto em Chinês

![Texto em japones](img/learning-chinese.webp)
