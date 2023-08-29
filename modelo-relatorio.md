# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 28/08/2023
Empresa: UConnect 
Responsável: Kaique Siqueira Meneguelli

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa UConnect, realizado por Kaique Siqueira Meneguelli. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2
- Tornar possível a utilização de servidores virtuais
- A empresa UConnect necessita de uma ampliação de seus servidores, porém a empresa não sabe exatamente o tamanho da demanda que pode ocorrer nos próximos meses, então investir em uma estrutura física pode ser muito custoso e ineficaz, já que pode acontecer de se ter um investimento muito alto e a capacidade não ser bem utilizada. Também pode acontecer de a capacidade ser insuficiente para a demanda que pode ocorrer. Então, ao utilizar o Amazon EC2, é possível ter servidores virtuais disponíveis e aumentar ou diminuir os servidores de acordo com a demanda, de forma prática e simples. Você também só paga pelo tempo que usar, o que torna muito mais eficiente que uma estrutura física, que demanda espaço e consome muita energia.

Etapa 2: 
- AWS Auto Scaling
- O AWS Auto Scaling monitora os aplicativos e ajusta automaticamente a capacidade para manter um desempenho constante e previsível pelo menor custo possível.
- Através do Auto Scaling, é possível definir um número mínimo e máximo de instâncias EC2 que a empresa deseja trabalhar. Então o Auto Scaling irá cuidar de utilizar as instâncias necessárias, conforme a demanda. Evitando assim, custos desnecessários, já que apenas as instâncias essenciais irão estar em funcionamento.

Etapa 3: 
- Instâncias SPOT do Amazon EC2
- As instâncias spot do Amazon EC2 permitem aproveitar a capacidade não utilizada do EC2 na Nuvem AWS.
- Através da utilização das instâncias SPOT, é possível ter um desconto de até 90% quando comparado com as instâncias sob demanda. Porém essas instâncias apenas são recomendadas caso houver flexibilidade quanto ao momento em que as aplicações serão executadas e se as aplicações podem ser interrompidas, tornando essa funcionalidade muito útil para a empresa, que pode utilizar essa função para trabalhar com big data e cargas de trabalho conteinerizadas. Também é possível combinar a utilização de instâncias SPOT com instâncias sob demanda, para ter mais possibilidades de trabalho.



## Conclusão
A implementação de ferramentas na empresa UConnect tem como esperado uma redução de custos de implementação, além de tornar possível a utilização de um sistema com alta escalabilidade e disponibilidade, o que aumentará a eficiência e a produtividade da empresa, com um custo muito mais baixo do que se houvesse a implementação de uma estrutura física de servidores. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

(https://aws.amazon.com/pt/ec2/spot/)
(https://aws.amazon.com/pt/ec2/)
(https://aws.amazon.com/pt/autoscaling/)

Nome do Responsável pelo Projeto:
Kaique Siqueira Meneguelli
