# Microservices-HW2

## 2.1. What are the relationships with other architecture styles?
Service-oriented integration: 
Possibilidades. Com microservices podemos implementar SOI. Podemos, por exemplo, criar um serviço API Gateway para integrar em um nó “tradutor” a comunicação entre sistemas legados.;

Service-oriented application:
 Com microservices podemos abstrair o cluster formado, dinamicamente, pelos services como uma grande camada de apresentação, oferecendo para o webapp um único canal de entrada e saída, conforme a figura abaixo:

Monolithic migration using SOA. 
Podemos ter microservices contidos em ambientes monolíticos. Sua migração e expansão da-se de forma semelhante a qualquer implementação monolítica, com diferença que ao invés de criar um ambiente monolítico idêntico basta criarmos um novo ambiente com apenas os serviços em estresse.


## 2.2. What are the relations between microservices and Twelve-Factor apps?

A priori, um não depende necessariamente do outro. Pondendo existirem separadamente ou coexistirem no mesmo sistema.
O Twelve-Factor Apps traz fatores para construir software com boa fundação. Enquanto microservices traz princípios arquiteturais para construir software que reage bem a situações de estresse.
Ao ter os princípios dos dois sendo representado, temos uma combinação poderosa de um sistema orgânico que, individualmente ou em grupo, resiste a situações de estresse e possui uma maior tolerância a falhas. Um sistema que respeita os princípios dos 12-factor apps tem em si sinais que agirá bem para escala de uso, mudanças na equipe de desenvolvimento e expansão do sistema em features. O esquema arquitetural microservices traz em si princípios capazes de dar ao sistema autonomia de reagir ao contexto de ambiente/consumo em que está imerso, de forma a garantir o funcionamento do sistema como um todo.
A combinação de ambos é amplamente indicada por empresas como Heroku, IBM e Pivotal.

## 2.3. Choose 3 early adopters case to tell (briefly) the history.
Netflix (www.netflix.com): Netflix, an international on-demand media streaming company, is a pioneer in the microservices space. Netflix transformed their large pool of developers developing traditional monolithic code to smaller development teams producing microservices. These microservices work together to stream digital media to millions of Netflix customers. At Netflix, engineers started with monolithic, went through the pain, and then broke the application into smaller units that are loosely coupled and aligned to the business capability.
