# Concepção

O projeto tem como objetivo aplicar os conceitos de domótica de forma a
automatizar uma residência. Para que tenhamos êxito na empreitada alguns requisitos
mínimos devem ser atendidos.

Devemos ser capazes de controlar a iluminação de cômodos,
bem como os LEDS, de forma remota. É necessário também ter acesso às medições feitas
por 2 tipos de sensores, de presença e de gás. E por fim seremos capazes de controlar
um portão eletrônico.

A fim de facilitar a implementação do projeto, uma maquete deve ser feita para
que possamos testar as funcionalidades.

A integração destas funcionalidades será feita através da plataforma Arduino.
Ele será o responsável pela aquisição dos dados emitidos pelos sensores e por controlar
o acionamento ou não, da iluminação, leds ou do portão. A interface de interação entre
o usuário e o Arduino se dará em primeiro momento pelo computador, através de uma rede
sem fio, havendo tempo hábil pode-se estudar uma interface através do smartphone.
	
  Sobre a residência a ser automatizada, optou-se por uma simples. A mesma possui
um quarto, um banheiro e uma cozinha anexa a sala. Temos ainda um quintal com jardim, e
uma garagem. Sobre a disposição dos cômodo, podem ser melhor visualizados na planta.
	
  Todos os cômodos possuem uma lâmpada, enquanto o jardim e o quintal possui 
iluminação de LED. Os sensores de gás estão presentes na cozinha e no banheiro, que 
possui aquecimento a gás, enquanto sensores de presença estão nos fundos e na frente, 
onde também esta o portão eletrônico.
