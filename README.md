# AdviceHealth

Nork-Town é um lugar estranho. Corvos grasnam na manhã enevoada enquanto os velhos apertam os olhos.
É uma cidade pequena, então o prefeito teve uma ideia brilhante de limitar o número de carros que uma pessoa pode possuir.
Uma pessoa pode ter até 3 veículos.
O veículo, registrado para uma pessoa, pode ter uma cor, 'amarelo', 'azul' ou 'cinza'.
E um dos três modelos, 'hatch', 'sedan' ou 'conversível'.

A loja de carros Carford quer um sistema onde eles possam adicionar proprietários de carros e carros.
Os proprietários de carros podem ainda não ter carros, eles precisam ser marcados como uma oportunidade de venda.
Carros não podem existir no sistema sem proprietários.



Rules: 
  - Uma pessoa pode possuir no máximo 3 veiculos.
  - Uma pessoa deve ser marcada como oportunidade de venda quando não possuir veiculos.
  - Veiculos devem possuir um proprietario.
  - Os veiculos devem possuir as cores ‘yellow’, ‘blue’ ou ‘gray’.
  - Os veiculos devem ser dos tipos ‘hatch’, ‘sedan’ ou ‘convertible’.
  


Casos de Teste:

1. Pessoas
  1. Realizar a inclusao de pessoas.
  2. Pode ser realizada a alteracao do nome da pessoa.
  3. É possivel excluir uma pessoa, independente se ela possui veiculos ou nao.
  4. O status de comprador é condicinado para quando a pessoa possuir menos que três veiculos.
  
2. Carros.
  1. Somente é possivel realizar a inclusao de um veiculo relacionando a um proprietario.
  2. É possivel realizar a alteracao do nome, cor e/ou tipo do veiculo.
  3. É possivel excluir um veiculo relacionado a pessoa.
  4. Nao é possivel incluir novos veiculos para proprietarios que ja possuem tres veiculos. 
  
