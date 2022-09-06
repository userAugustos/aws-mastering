### VPC - Virtual Private Cloud

- Importante lembrar que por padrão a aws já cria um vpc pra você quando se cadastra.

**VPC é o alicerce de toda a infraestrutura que você vai consulmir na aws, já que é ela que define quais são as zonas de hospedagem que vai utilizar e quais os IP's que cada zona vai ter pra poder hospedar as maquinas, serviços... tudo dentro da amazon.**

_VPC é a estrutura de ip's, de rede que a amazon vai disponibilizar para as maquinas._

*Subnets*: 
-	Uma VPC é o pai de todas as redes que você vai ter na sua infraestrutura; Mas pra criar serviços e instanciâs e colocar dentro da VPC, você precisa das subnets, para dizer dentro da vpc, quais as hospedagens que vai delegar a cada serviço.

*Internet Gateway*
 - o IGW vai dar acesso a internet para os vpcs, linkados a ele.

_Um item importante quando configurando sua VPC é habilitar o DNS Hostnames e DNS Resolution, para que os serviços dentro do seu dominio, possam se encontrar por hostnames, endpoints, e não apenas por ip's_

##### Uma vez configurado sua VPC, subnet(s) e IGW:

Você vai precisar também, para fazer funcionar sua IGW e dar acesso a rede, para seu VPC. Determinar quais as rotas de navegação pra dentro e pra fora da sua VPC, isso para que sua aplicações na aws possam acessar sites e endpoints de fora e vise-versa.

Para isso, vá até	`Route Tables` na seção da VPC.