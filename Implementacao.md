# Implementação

Nesta etapa do projeto colocaremos em prática o que foi abordado e definido pelas etapas anteriores. De forma a atingir os objetivos estipulados,
podemos definir duas diferentes frentes de trabalho. Programação e Maquete.

## Progamação

O primeiro passo foi realizar testes com os componentes de forma a verificar e compreender seu funcionamento. Ao longo deste processo pode-se notar
que muito do que era feito ali poderia e foi integrado ao código final. Inicialmente apenas testes simples foram realizados, a fim de se habituar a plataforma 
utilizada, *ARDUINO IDE*, e sua metodologia. Este ambiente de desenvolvimento suporta as linguagens **C e C++**, além de já possuir diversas bibliotecas desenvolvidas
que auxiliam na implementação e operação de empreendimentos que se utilizem do Arduino, no caso deste projeto toda a programação foi feito através da linguagem **C**.

Cada componente foi testado separadamente através de rotinas simples, após isso métodos de interação entre eles foram gerados, resultando em um código funcional que atende
as exigências do projeto.É interessante destacar que visando uma interação entre os componentes que se aproxime mais da realidade de uma casa, algumas adaptações foram necessárias, por exemplo,a calibração do sensor PIR, visando uma resposta mais precisa foram feitos ajustes na sua sensibilidade e tempo de resposta, estes ajustes foram feitos no próprio *hardware* através de dois potenciômetros, e no caso de ser detectado movimento, um led relacionado ao ambiente será aceso, no caso nos fundos da casa. Foi necessário também atribuir ao sensor de gás um valor limite para que possa haver uma comparação entre o que é medido com o que seria considerado uma ameaça, este valor foi atribuído no código, e é definido como 300ppm, o que significa que caso ele detecte uma amostra de gás maior que 300 partes por milhão, o alarme será ativado, este alarme é um aviso sonoro via buzzer, bem como uma mensagem ao usuário. O servo motor foi programado para girar de 0° até 180º de forma a abrir o portão, e para fechar o oposto ocorre, para que isso ocorra o usuário poderá controlar digitando a letra 'a' para abrir e 'A' para fechar. Para os leds foram designadas teclas para controlar, minúsculas acendem e letras maiúsculas apagam, de acordo com a tabela abaixo. Todo o código pode ser visualizado abaixo da tabela 1.



 COD  | ambiente              
----- | ---------
 z / Z | sala de estar         
 x / X | cozinha               
 c / C | sala de estar         
 v / V | quarto                
 b / B | garagem               
 n / N | fundos                
 m     | apaga todas           
*tabela 1 - codigos de acionamento dos leds.*

````C
possivel codigo
````
## Maquete

Em desenvolvimento.
