## AWS

##### O que é Cloud Computing?
  _Cloud computing, basicamente é um fazenda de computadores, onde todas as informações, aplicativos, servidores, etc, rodam de forma virtualizada, ou seja você tem um sistema operacional que roda dentro da maquina fisica, e dentro desse sistema operacional rodam varios outros sistemas operacionais, tornando essa máquina uma patlaforma_

Isso muda tudo, já que no plano de hospedagem convencional, você coloca seu site numa maquina, onde tem varios outros sites, sem controle  de performance ou gastos, isso pode prejudicar seu site, ou seu site prejudicar outros. Ou no convencional, nos planos convencionais, você fica limitado ao que o datacenter te libera. 

*No cloud computing, você tem acesso a tudo que você quiser, e personaliza-la, e também a performance e gastos da sua máquina.
**Ainda mais, no cloud computing, você tem uma especie de escala infinita.**
Você pode escalar tanto horizontalmente quanto verficalmente, criando máquinas de acordo com necessidade, datas, momentos necessários da sua aplicação.
*

Já a AWS como conhecemos, iniciou suas atividades por volta de 2002, criando serviços escalavéis, para a própria Amazon(e-commerce).

Os primeiros serviços que a AWS desenvolvou, na época para a própria Amazon(e-commerce), foram: 
- S3:
	(Simple Storage Service) Armazenamento de Arquivos
- SQS:
	(Simple Queue Service) Fila de Mensagens.
	_Este é até hoje, um dos mais utilizados no AWS, fique de olho nele mais pra frente_s

Mas bom, depois de desenvolver esses e outros serviços para o e-commerce, a diretória da Amazon viu no AWS algo enorme, eles estavam se especializando em infraestrutura sobre demanda e muito bem escalavel, onde decidiram, se afundar nisso e transformar em um produto rentável, e então formalizaram a AWS e seus serviços, como algo consumivel.

A AWS chega então a publico como uma empresa propriamente dita, em 2006.


#### Fundamentos

Para monitoramento de gastos: 
 - AWS Cost Explore
   - _Vale ver o Saving Plans aqui_
 - AWS Budgets


###### AWS IAM
	- Roles
    Roles são tipos de usuarios que não podem fazer login na amazon, são usuarios que são criados pra ter acesso programatico a AWS, a role é atribuida diretamente a uma função ou serviço da aws.
		 