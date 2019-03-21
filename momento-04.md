## Computação em nuvem
Neste módulo, você conhecerá o conceito de Computação em Nuvem, a evolução dos sistemas de armazenamento, e os modelos de implantação de nuvem e de serviços fornecidos por provedores.  

Esperamos que ao final de seus estudos, você tenha entendido como essa tecnologia disponibiliza e amplia o acesso à informação, e que seja capaz de selecionar o modelo de serviço e de plataforma adequados à cada aplicação.  

O Instituto Nacional de Padrões e Tecnologia - NIST, órgão do departamento de governo dos Estados Unidos da América, define computação em nuvem como um modelo para habilitar acesso sob demanda, conveniente e ubíquo, por meio de redes, a um reservatório compartilhado de recursos computacionais configuráveis, por exemplo, redes, servidores, armazenamento, aplicações, etc. que podem ser provisionados rapidamente e liberados com esforço mínimo de gerenciamento ou interação com o provedor de serviços.   

Informalmente, podemos imaginar a nuvem como um grande reservatório de recursos, que foi construído para se adaptar às necessidades de armazenamento de dados de seus clientes e estar disponível em tempo real por meio da Internet.  

Dessa forma, a Computação em Nuvem pode ser compreendida como um modo pelo qual os usuários acessam, por meio da Internet, os recursos computacionais disponíveis, sendo que tais recursos têm capacidade de se adaptar às necessidades desses usuários (clientes).  

1880 - O cartão perfurado, inventado no séc. XIX, foi o precursor da memória usada em computadores.  
1950 - A fita magnética, originalmente inventada para gravar áudio, se tornou o novo método para o armazenamento de dados.   
1962 - É lançado o primeiro compacto áudio-cassete com capacidade de armazenamento de 660 KB em cada lado.   
1963 - O primeiro disco de memória removível (conhecido hoje como HD externo) tinha capacidade de memória de 2.6 MB.   
1971 - Os disquete, que começaram a ser produzidos com 8” e capacidade de armazenamento de 80 KB, evoluíram para 5.25″, com armazenamento de 1.2 MB.   
1990 - Inventado em 1982 originalmente para áudio, com a versão de 1990, que permitia gravar e apagar arquivos, passou a ser utilizado na informática por sua capacidade de armazenamento de até 700 MB, o equivalente a 486 disquetes.   
1994 - O Zip drive, com capacidade de 100 MB, tinha a proposta de substituir o disquete, mas não chegou a conquistar o mercado.   
1995 - A evolução do CD, o DVD chegou com capacidade de 4,7 GB de espaço.   
1999 - O cartão de memória, com capacidade de 1GB, chegou como a proposta de aumentar a memória de câmeras fotográficas e celulares.   
2000 - O Pendrive substituiu definitivamente o disquete. Com capacidade atualmente de 512 GB de armazenamento, há promessa de lançamento de versão com capacidade de 1TB.   
2013 - Do ponto de vista de quem armazena os dados, a Nuvem elimina o equipamento físico. Ou seja, o usuário não precisa se preocupar com o equipamento que vai guardar os seus arquivos. Precisa apenas de um aparelho para acessá-los. Além disso, poderá acessar, de onde estiver, sua conta de e-mail, fotos, músicas, softwares, arquivos de todos os formatos e tamanhos.   

Você viu que a Computação em Nuvem possibilita o armazenamento de recursos, mas não é só isso. Ela é, também, um modelo para habilitar acesso sob demanda. Essa característica está ligada à escalabilidade e à rápida disponibilidade dos recursos na rede. A escalabilidade é uma das características mais importantes na Nuvem, pois permite que seus recursos sejam rapidamente provisionados, atendendo à mudanças no fluxo de demandas.  

Na computação tradicional, os recursos disponíveis para um serviço são fixos. Por exemplo, o número de servidores e o espaço para armazenamento. Já no modelo em nuvem, é possível que os recursos se adaptem às variações no fluxo de demanda, otimizando custos e respondendo de uma maneira dinâmica e rápida a tais variações. Há, portanto, uma economia no projeto e uma capacidade de reação mais rápida frente às mudanças nas demandas.  

A nuvem é dinâmica e seus recursos são provisionados à medida que a demanda cresce ou diminui, em um modelo baseado em métricas de uso. Dessa forma, sua precificação, na maioria das vezes, é calculada de acordo com o uso do serviço. Ou seja, o cliente paga por um serviço de armazenamento proporcionalmente ao espaço que faz uso.  

Na definição do NIST, para Computação em Nuvem são descritos três modelos de serviços, também chamados de camadas de arquitetura em nuvem. Observe, nas imagens, as diferenças entre eles.  

#### Infraestrutura como serviço
No modelo __IaaS__, o que é gerenciado pelo provedor: Virtualização, Servidores, Armazenamento, Rede.  
O cliente é capaz de gerenciar de maneira mais próxima ao sistema operacional os seguintes recursos: Aplicações, Dados, Tempo de execução, Middlewares, Periféricos de entrada e saída.   

O objetivo desse modelo é tornar mais acessível o fornecimento de recursos computacionais, como servidores, redes, armazenamento etc. que são fundamentais na construção de um ambiente na rede.  

No IaaS, o provedor é responsável fisicamente pelos servidores, dispositivos de armazenamento e pela rede. O cliente da nuvem se torna responsável por obter as máquinas provisionadas pelo provedor de serviços, instalar e configurar o sistema operacional e as demais aplicações de seu interesse.  

Em geral, o cliente não administra ou controla a infraestrutura da nuvem, mas tem controle sobre os sistemas operacionais, armazenamento, aplicativos implantados e, eventualmente, seleciona componentes de rede, tais como firewalls.  

```
Firewall é um software de segurança da rede que monitora o tráfego de entrada, saída, permissões, ou bloqueio de tráfegos de   
acordo com um conjunto definido de regras de segurança. Adaptado de: Cisco.
```   

Em outras palavras, o IaaS é um serviço destinado a uma equipe de tecnologia da informação (TI). Sendo assim, a equipe precisa instalar e configurar, por conta própria, todos os recursos necessários para as suas necessidades, desde o sistema operacional até as aplicações que serão disponibilizadas. Normalmente, é adotado por empresas que visam reduzir investimentos em hardware, eliminando custos como segurança e manutenção, além de liberar o espaço físico que seria ocupado por servidores, por exemplo.

___
#### Plataforma como serviço
No modelo __PaaS__ o cliente recebe o ambiente de desenvolvimento, sem a necessidade de gerenciar detalhes de infraestrutura. O provedor gerencia: Virtualização, Servidores, Armazenamento, Rede, Periféricos de entrada e saída, Middlewares, Tempo de execução.  
O cliente é capaz de gerenciar de maneira mais próxima ao sistema operacional os seguintes recursos: Aplicações e Dados.

Esse é um modelo intermediário, composto por um hardware virtual disponibilizado como um serviço. O provedor do serviço disponibiliza o sistema operacional, linguagens de programação e ambientes de desenvolvimento de aplicações.  

O cliente não administra ou controla a infraestrutura subjacente, mas tem o controle sobre as aplicações implantadas e, possivelmente, sobre as configurações de aplicações hospedadas nessa infraestrutura.  

O foco desse serviço são os desenvolvedores de softwares, pois o PaaS é um ambiente completo para o desenvolvimento de aplicações, tais como compiladores, depuradores, bibliotecas etc.  

Enquanto o IaaS disponibiliza recursos de uma maneira genérica, isto é, com pouca ligação com o objetivo final do cliente, o PaaS disponibiliza recursos diretamente ligados ao negócio do cliente.

```
As soluções Google App Engine e Microsoft Azure se destacam como provedores do PaaS.
```  
___
#### Software como serviço
No modelo __SaaS__ o cliente apenas faz uso de uma aplicação disponível na nuvem, não gerenciando nenhum elemento de tecnologia da informação abaixo da camada de aplicação. O provedor gerencia todos os recursos.  

Esse modelo provisiona soluções de software com diferentes propositivos para os clientes da nuvem, acessíveis, por meio da internet, pelos mais variados dispositivos do usuário. O cliente não administra ou controla a infraestrutura subjacente (rede, servidores, sistema operacional, discos rígidos etc.).  

Esse modelo provê serviços de computação para o usuário final. O usuário enxerga apenas o software que precisa usar e não tem conhecimento de onde estão localizados os recursos empregados, nem quais linguagens de programação foram utilizadas para desenvolver o serviço, assim como desconhece detalhes do sistema operacional e do hardware que o suporta.  
```
Os serviços de armazenamento oferecidos pela Dropbox e pela Google são exemplo desse modelo.
```  
___

Outras vantagens do modelo de computação em nuvem são a confiabilidade e a tolerância à falhas, pois, os clientes podem estabelecer acordos de nível de serviço com os provedores, de modo a garantir a disponibilidade apenas dos recursos que precisam. Além disso, tarefas como backup e proteção contra vulnerabilidades de segurança da informação passam a ser de responsabilidade dos provedores e não mais dos clientes.  

Essa flexibilidade permite que as indústrias tenham maior agilidade, pois no momento em que acontece a maior demanda, a nuvem se adapta a esta necessidade, o que garante que a empresa seja ágil na resposta ao cliente.  
De uma forma genérica, podemos dizer que o que diferencia os tipos de modelos de serviço em nuvem é o tipo de cliente ao qual cada um se destina.  

O Instituto Nacional de Padrões e Tecnologia - NIST define também modelos para a implementação de nuvens. Os modelos definidos mais consagrados são:  

__nuvem pública:__ Centenas de empresas podem usá-la ao mesmo tempo, mas separadamente. Pode ser acessada por qualquer usuário. O provedor da nuvem é responsável pela manutenção e pela segurança. Por serem de uso geral, há maior risco à privacidade.  
__nuvem privada:__ Propriedade de uma única empresa que faz uso exclusivo dos recursos (servidores e software), com a utilização apenas de pessoas específicas. Protegida pelo firewall e administrada de acordo com o regimento da organização. Seu custo, no entanto, pode ser alto e, consequentemente, impeditivo para muitas empresas.  
__nuvem comunitária:__ Pode ser compartilhada por diversas empresas que, normalmente, possuem interesses em comum. A administração geralmente é realizada por uma das empresas parceiras. Os custos também são divididos.   
__nuvem híbrida:__ Composta de duas ou mais nuvens, que preservam as características originais de seu modelo, interligadas por uma tecnologia que possibilite a portabilidade de informações e aplicações.  

### Benefícios 
A computação em nuvem, na Indústria 4.0, permite que diversos sistemas atuem com alta performance, disponibilidade, acessibilidade e economia de recursos.  

Além disso, a computação em nuvem se mostra como uma ferramenta fundamental na quebra de barreiras geográficas, aumento da produtividade, conectividade e geração de novas oportunidades para empresas de todos os portes e segmentos. As soluções em computação em nuvem podem garantir este desempenho, já que ajudam com as ferramentas de colaboração e integração entre os departamentos, possibilitando mais agilidade na produção, melhor comunicação e redução de erros.  

Por exemplo, a indústria pode utilizar um serviço de virtualização que permita construir, implementar e compartilhar soluções de análise em tempo real da operação de um parque fabril. E por meio de armazenamento e serviços na nuvem, a indústria pode aplicar algoritmos de inteligência artificial para auxiliar na análise preditiva.  

Com base nesses dados, a indústria poderá tomar decisões mais assertivas quanto aos recursos materiais e humanos, etapas e volume de produção, períodos de manutenção etc. visando redução de custos e aumento de produtividade.  
___
### Cases
Fórmula 1  
Eficiência energética  
Indústria automativa
___
### Quiz
Como você viu, o Instituto Nacional de Padrões e Tecnologia – NIST define modelos para a implementação de Nuvens. 
Imagine que a empresa na qual trabalha, a fim de se tornar mais ágil, pretenda utilizar essa tecnologia e que você tenha sido designado(a) para definir o tipo de Nuvem que a empresa deverá utilizar.  
Considerando os seguintes requisitos especificados pela equipe de TI:  
```
Na escolha da Nuvem devem ser considerados o custo, que não deverá ser alto, uma vez que estaremos em fase de teste desta aplicação, e  
a privacidade, pois, eventualmente, poderemos armazenar documentos sigilosos. Além disso, ainda não dispomos de pessoal   
qualificado para administrá-la.
```  
Selecione a Nuvem mais adequada às necessidades da empresa:  
- [ ] Nuvem pública  
- [ ] Nuvem privada  
- [X] Nuvem comunitária  
- [ ] Nuvem híbrida  
 
# Módulo 3
___
Neste Módulo, você conheceu o conceito de Computação em Nuvem, os tipos de Nuvens e de serviços oferecidos por provedores.  

Você viu a evolução dos sistemas de armazenamento de dados digitais e que a Nuvem permite o acesso sob demanda, um grande diferencial desse novo sistema de armazenamento, dentre outros benefícios dessa tecnologia para a Indústria 4.0  

No próximo módulo, você vai conhecer o conceito de Big Data, suas tecnologias e aplicações. Avance para continuar seus estudos.
