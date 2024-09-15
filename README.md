# resumo-lab-azure
Este repositório contem o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

# Resumo do conteúdo assimilado;

Nos foi apresentado os conceitos da computação em núvem e tambem os seus benefícios em sua aplicação em um ambiente profissional, dos quais alem de facilitar e reduzir o custo operacional para uma organização, temos tambem a segurança e agilidade por ela proposta, alem de mostrar os ganhos que podemos adquirir com os fatores CapEX e OpEX.

O Azure fornece varios tipos de níveis de gerenciamentos, entre eles segurança, custos, entre outras, do qual é possivel mitigar problemas/falhas e tambem reduzir custos de operação onde é possivel obter esses dados de forma rapida e eficiente. Se tratando de nuvem, tambem falamos de escalabilidade e tambem confiabilidade dessas plataformas, mostrando robustes e facilidade de implementação de baixa ou larga escala. Governança e Gerenciabilidade são pontos que são facilmente assimilados dentro do ambiente de nuvem, uma vez que fazem parte do ambiente de facilitação de trabalho dos administradores da rede/recurso que é apresentada a uma empresa, mas sem que tenhamos que ter um custo elevadissimo com pessoal e fazer os gerenciamentos de segurança, monitoramento e aplicação dessas regras.

Foi abordado os tipos de serviços de nuvem e o qual seu papel dentro do contexto geral da aplicação da ferramenta, sendo elas:
    * IaaS - Infrastructure as a Service
    * PaaS - Platform as a Service
    * SaaS - Software as a Service
    - Lembrando que os modelos representados são de responsabilidade compartilhada, ou seja, a Azure fornece as ferramentas mas o cliente é responsável em aplica-las ou não;

A arquitetura de um serviço Azure é assegurado por componentes de arquitetura que são divididos em Regiões e Zonas, Assinaturas e grupos de recursos.
As regiões são onde se encontra o servidor baseado na localização que o cliente escolheu como base de seus dados, e, dependendo dessa decisão, a mesma irá afetar diretamente a performance apresentada ao consumidor final. Todas as Regioes consistem em pares de dados, ou seja, quando a região fica inoperativa, a região secundário tomará o papel de principal de forma temporária até a disponibilidade da original. 

A computação de rede no Azure oferece uma ampla gama de soluções para garantir disponibilidade, escalabilidade e flexibilidade. Um dos aspectos mais importantes dessa infraestrutura é a alta disponibilidade, que é mantida por meio de data centers distribuídos globalmente. Esses data centers garantem redundância e recursos de failover, assegurando que, em caso de falhas, os serviços possam ser transferidos para outras regiões, minimizando o tempo de inatividade.

Além disso, o Azure Virtual Desktop é um serviço que permite criar e gerenciar áreas de trabalho virtuais, acessíveis remotamente por meio da nuvem. Ele é especialmente útil para empresas que desejam centralizar a gestão de seus desktops e permitir que seus colaboradores acessem o ambiente de trabalho de qualquer lugar, mantendo a segurança e a integridade dos dados. Isso facilita a mobilidade do trabalho e reduz a necessidade de manutenção física dos dispositivos dos usuários.

No contexto de contêineres, o Azure também oferece serviços avançados como o Azure Kubernetes Service (AKS), uma solução gerenciada que facilita a execução de clusters Kubernetes na nuvem. O Kubernetes, por sua vez, é amplamente utilizado para orquestrar a implantação, o gerenciamento e a escalabilidade de aplicações em contêiner. No Azure, além do AKS, há o Azure Container Instances (ACI), que possibilita a execução de contêineres de maneira isolada e flexível. Exemplos comuns de contêineres utilizados no Azure incluem o Docker e o LXC, que proporcionam ambientes portáteis e isolados para a execução de aplicações e suas dependências.

No campo das máquinas virtuais, uma abordagem popular é o Lift-and-Shift, que se refere à migração de aplicativos e workloads de um ambiente local para a nuvem sem realizar grandes modificações. Essa técnica é ideal para empresas que desejam mover rapidamente suas operações para o Azure, aproveitando os benefícios da nuvem sem precisar reescrever ou adaptar os aplicativos existentes. Adicionalmente, o Azure oferece suporte a logons de múltiplos clientes, o que permite que diferentes usuários ou organizações acessem as mesmas infraestruturas virtuais de maneira segura, mantendo a segregação de dados e controle sobre o acesso.

Os contêineres desempenham um papel essencial no Azure ao fornecer ambientes isolados que contêm tudo o que uma aplicação precisa para rodar. Esses ambientes são altamente portáteis e eficientes, permitindo a implantação rápida e o escalonamento horizontal das aplicações. A facilidade de mover e executar contêineres em diferentes ambientes os torna uma escolha popular para arquiteturas modernas de microsserviços.

No que diz respeito a soluções de SaaS (Software as a Service), o Azure permite que os usuários acessem aplicativos hospedados na nuvem sem a necessidade de instalar ou manter o software em suas próprias máquinas. Exemplos populares de SaaS no Azure incluem o Microsoft 365 (antigo Office 365) e o Dynamics 365, que fornecem ferramentas de produtividade e CRM acessíveis diretamente pela internet.

Os serviços de rede do Azure são igualmente robustos, oferecendo soluções como o Azure Virtual Network (VNet), que permite criar redes privadas para conectar e proteger recursos na nuvem. O Azure VPN Gateway facilita a conexão entre redes locais e a nuvem, garantindo a continuidade das operações corporativas. Além disso, o Azure Traffic Manager é uma solução de balanceamento de carga global que direciona o tráfego de acordo com as regras de desempenho e disponibilidade configuradas pelos administradores.

Quando se trata de armazenamento, o Azure oferece diversas opções para atender às diferentes necessidades de dados. O Armazenamento de Blobs é uma solução escalável para armazenar grandes volumes de dados não estruturados, como vídeos, backups e imagens. Já o armazenamento de discos é destinado às máquinas virtuais, com opções gerenciadas e não gerenciadas para garantir a resiliência e a alta disponibilidade dos dados. O serviço de filas do Azure, por outro lado, é utilizado para comunicação assíncrona entre componentes de um aplicativo, garantindo que mensagens possam ser trocadas de forma segura e eficiente. O armazenamento de arquivos baseado no protocolo SMB permite o compartilhamento de arquivos entre diferentes máquinas virtuais ou até mesmo com ambientes locais. Outro serviço importante é o armazenamento de tabelas, ideal para grandes volumes de dados não relacionais, oferecendo uma solução flexível e rápida para armazenar dados estruturados sem a necessidade de um esquema rígido.

Além das diferentes opções de armazenamento, o Azure permite a configuração de camadas de acesso (Hot, Cool e Archive), otimizando o custo de armazenamento de acordo com a frequência de acesso aos dados. Dados acessados com frequência podem ser armazenados na camada Hot, enquanto os dados raramente utilizados são movidos para a camada Archive, oferecendo um equilíbrio entre custo e desempenho. Em termos de segurança e mitigação de riscos, o Azure oferece replicação geográfica, backups automáticos e políticas de retenção para garantir a resiliência dos dados contra falhas e perdas. Uma ferramenta essencial nesse contexto é o AZCopy, que facilita a movimentação de grandes volumes de dados para e a partir do armazenamento do Azure, suportando Blobs, Files e Tables de maneira eficiente.

A arquitetura do Azure também inclui serviços avançados de identidade e gerenciamento de acesso. O Azure Active Directory (Azure AD), agora parte do ID Entra, é um serviço que permite gerenciar identidades e controlar o acesso de usuários e aplicativos aos recursos na nuvem. A autenticação no Azure AD garante que apenas usuários verificados possam acessar os sistemas, enquanto a autorização define quais recursos eles podem acessar com base nas permissões. O controle de acesso baseado em função (RBAC) é uma ferramenta poderosa no Azure, que permite definir permissões de acesso de acordo com funções predefinidas ou personalizadas. Isso garante que os usuários tenham acesso apenas aos recursos necessários para suas funções, melhorando a segurança e a eficiência na gestão de grandes ambientes.

Esses serviços e soluções formam a base da oferta do Azure, proporcionando uma plataforma flexível, segura e escalável para diferentes tipos de aplicações e cenários empresariais.

---------------------------
Gerenciamento de custos

	- Calculadora de custos e preços
	- Gerenciamento de custos e marcas
	
É a descrição de faties que podem afetar os custos no Azure. É possível comparar e descrever a ferramenta de gerenciamento de custo
do Azure. Também descreve a finalidade das marcas. O maior problema da nuvem atualmente é o custo elevado de implementação, então é importante saber previamente a real necessidade de implementação dos recursos em nuvem. Algum dos fatores que afetam os custos são:
	
	1. Tipo de recurso
		Custos são específicos do recurso, portando, o uso que um medidor rastreia e o numero de medidores associados a um
		recurso, dependendo do tipo de recurso.
	2. Consumo
		Com um modelo pago conforme o uso, o consumo é um dos maiores geradores de custos.
	3. Manutenção
		Monitorar seu volume do Azure e manter seu ambiente pode ajuda-lo a identificar a reduzir os custos que não 
		são necessários, como ao desligar máquinas virtuais.
	4. Áreas geográficas
		O mesmo tipo de recurso pode custar valores dependendo da área geográfica o que afeta os custos do Azure.
	5. Tráfego de rede
		Embora algumas transferências de dados de entrada sejam gratuitas, o custo para dados de saída ou dados entre
		recursos do Azure é afetados por zonas de cobrança.
	6. Assinatura
		O tipo e a configuração da assinatura também podem afetar o custo. Por exemplo, a avaliação gratuita permite 
		explorar alguns recursos do Azure gratuitamente.

O Azure Marketplace permite que os clientes encontrem, experiementem, comprem e provisionem aplicativos e serviços de centenas de 
provedores de serviços líderes, que são todos certificados para execução no Azure. Caso seja instalado um recurso não Microsoft, 
a Microsoft não irá prover suporte, do qual o suporte deverá ser cobrado da empresa fabricante do software. 


Calculadora de preços do Azure

	Quando você precisa de uma simulação de um projeto para prever o custo de um recurso no Azure, o local indicado é a 
	calculadora de preços do Azure. É uma ferramenta que ajuda a estumar o custo dos produtos do Azure. As opções que você pode
	configurar na calculadora de preços entre os produtos, mas as opções básicas de configurações.
		* Região
		* Camada
		* Opção de cobranças
		* Opções de Suporte
		* Programas e ofertas
		* Preço de desenvolvimento/Teste do Azure.
	1. Calculadora de custo total de propriedade (TCO)
		* Uma ferramenta para estimar a economia de custos possível ao migrar para o Azure.
		* Um relatório compara os custos das infraestruturas locais com os custos de uso de produtos e serviços do Azure for 		
		Cloud
		* Geração de custos e cobranças.
		* Enriquecimento de dados.
		* Definição de orçamentos de gastos.
		* Alertas: Quando o custo excede os limites.
		* Recomendação: Recomendações de custo.
		
Marcas (tags)

	As marcas são elementos muito impostantes mas que não são obrigatórias e nem herdáveis para subconjuntos. Fornecem metadados 
	aos recursos do Azure. Organizam os recursos em uma taxonomia de maneira lógica. Consistem em um par nome-valor. Elas são 
	úteis par reunir informações de cobrança.
	

Laboratório de Custos
	
	Calculadora TCO
		* https://azure.microsoft.com/en-us/pricing/tco/calculator/


Governaça e Conformidade

	Governança e conformidade
		- Blueprints, politicas e bloqueios de recursos
		- Portal de confiança do serviço
		
	Azure Policy
		O Azure Polyce ajuda a impor padrões organizacionais e a avaliar a conformidade em escala. Ele fornece governança e 
		consistência de recursos com conformidade regulatória, segurança, custo e gerenciamento. Com ele, é possível aplicar
		a regra independente de quem queira realizar a criação de um recurso, sendo owner ou não.
		
		- Avalia e identifica os recursos do azure que não atendam as suas politicas
		- Fornecem definições de politicas e iniciativas integradas, em categorias como armazenamento, rede, computação, 
		central de segurança e monitoramento.
		
	Bloqueios de recurso
		- Proteja os recursos do Azure de exclusão ou modificação acidental;
		- Gerenciar bloqueios na assinatura, grupos de recursos ou níveis de recursos individuais do portal do Azure.
	
	Portal de confiança do serviço
		Onde poderá ser possível encontrar todas as informações quanto a regras e leis de empresas de governos. Nada mais é 
		que um link onde poderá ser consultado vários cenários de auditorias de empresas na área de Cloud.
		
	Microsoft Purview
		Aplicação que é da família de soluções de governança, risco e conformidade de dados que ajuda a obter uma única 
		exibição unificada em seus dados. Reúne insights sobre seus dados locais, multinuvens e de software como serviço. 
			- Descoberta de dados automatizada
			- Classificação de dados confidenciais
			- Linhagem de dados de ponta a ponta

Pagina para verificação de regras e documentação regulamentatória
	https://servicetrust.microsoft.com/