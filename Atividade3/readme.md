
## Documentação de Implementação de Tabela Hash e Tratamentos de Colisão


### Tabela Hash
Uma tabela hash é uma estrutura de dados que permite o armazenamento e recuperação eficiente de dados. Ela funciona associando chaves a valores, permitindo acessar um valor específico através de sua chave em tempo constante, idealmente. Isso é possível graças a uma função de hash, que transforma a chave em um índice na tabela.

### Tratamentos de Colisão
Colisão ocorre quando duas chaves diferentes são mapeadas para o mesmo índice na tabela hash. Existem diferentes abordagens para lidar com esse problema:

* Encadeamento Separado: Nesta abordagem, cada célula da tabela hash é uma lista encadeada de elementos. Quando ocorre uma colisão, os elementos com chaves diferentes mas que mapeiam para o mesmo índice são armazenados em uma lista.

* Endereçamento Aberto: Aqui, quando uma colisão ocorre, busca-se outro local na tabela para armazenar o elemento. Isso pode ser feito de diferentes formas, como sondagem linear, sondagem quadrática, ou sondagem dupla.


### Objetivo do Repositório
O objetivo deste repositório é documentar a implementação de uma tabela hash e os diferentes tratamentos de colisão mencionados acima. Isso inclui o código fonte da implementação em uma ou mais linguagens de programação, juntamente com exemplos de uso, explicações detalhadas e, sempre que possível, testes automatizados para garantir o correto funcionamento da implementação.
