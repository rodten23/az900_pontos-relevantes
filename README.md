# Curso "Microsoft Azure Essentials" da DIO - Tópicos apresentados nos desafios.

## Desafio "Microsoft Azure - Localizando Serviços por Categoria"

- Mesmo com conta gratuita, Portal Azure apresenta uma enorme gama de serviços, produtos e configurações que atendem a diversos tipos de aplicações e perfis de empresas e usuários;
- Portal pode ser configurado para facilitar seu uso pelo usuário, podendo ser alterado idioma, cores e formato do painel, entre outros itens;
- Já na tela inicial do Portal temos atalhos para as principais funções, itens acessados recentemente, ferramentas e links para documentações e produtos;
- Também está disponível o menu principal, onde todas as funções e serviços podem ser acessados por categoria, o que agiliza a contração e configuração destes, assim como o monitoramento, gestão de custos e acesso à seção de Ajuda e Suporte do Azure;
- No cabeçalho temos a nossa disposição o principal filtro de busca para o Azure, sino de notificações, engrenagem para configurações do Portal Azure, o Cloud Shell (terminal próprio para ação direta em produtos e serviços) e botão para acesso ao Copilot, uma das ferramentas em que a Microsoft mais tem investido para disponibilizar o uso de IA aos clientes;
- Por fim, além do Portal Azure, podemos usar também o VSCode e suas extensões para criar e configurar produtos e serviços do Azure por linha de código e scripts, que inclusive tem diversos exemplos prontos no Microsoft Learn para apenas ajustar para o uso de cada profissional.

## Desafio "Criando máquinas Virtuais na Azure"

- Ao criar recursos no Azure, é importante observar a disponibilidade pretendida x disponibilidade oferecida pelo SLA contratado, o qual é definido por várias opções, como região, zona de disponibilidade, tipo da assinatura, etc;
- Também é importante observar como é o cálculo de SLA para cada tipo de recurso;
- Dentro do Portal Azure, a maioria (senão todas) da opções para os recursos tem o tooltip (i) com um resumo de informações sobre aquela opção e, as vezes, links ("Saiba mais") para documentação completa da Microsoft;
- Além da completude das informações, duas grandes vantagens das documentações Microsoft é que são atualizadas continuamente e estão disponíveis em diversos idiomas. Por sinal, é recomendável revisitar as documentações dos recursos que mais utiliza, pois sempre pode ter novidades/atualizações importantes;
- Para criação de máquinas virtuais, um dos recursos mais importantes é o "Redundância", o qual dispõe atualmente de 4 estratégias para garantir disponibilidade de forma adequada a cada projeto;
- Uma novidade (pelo menos pra mim, pois não tinha quando usei o Azure pela primeira vez) é que, junto às opções de criação de máquina virtual, temos agora a seção "Custos mensais estimados", que já nos dão uma prévia do custo que teremos para aquele recurso;
- E, mesmo para máquina virtual mais simples, temos diversas opções a escolher nos menus, então vale a pena olhar cada menu e entender o básico de cada opção.

## Desafio "Configurando uma instância de Banco de Dados na Azure"

- Assim como para máquinas virtuais, ao criar "Banco de Dados SQL" temos diversas opções, as quais devem ser definidas conforme nosso escopo de negócios e requisitos, mas levando em conta os impactos em custos, segurança e disponibilidade, além de como isso se encaixa a nível de arquitetura de solução, sua escalabilidade e manutenção;
- Levando isso em conta, ideal é sempre avaliar com muito cuidado as vantagens e desvantagens entre seguir um modelo IaaS e PaaS, que nos permitem maior controle dos recursos, versus o modelo SaaS, que nos trás mais facilidade de configuração e provavelmente maior agilidade na implantação;
- Outro ponto importante é definir de forma cuidadosa os grupos de recursos e o que fará parte de cada um destes grupos, assim como as definições de segurança com o "Microsoft Entra" e outros métodos de acesso;
- Além disso, lembremos que o "Banco de Dados SQL" é só um dos muitos formatos de banco de dados que o Azure disponibiliza, devendo ser escolhido o que mais se adequa ao nosso projeto e custos pretendidos. Também podemos lembrar que podemos criar estes recursos como desenvolvimento ou produção, cada um trazendo custos, disponibilidade, etc, diferentes;
- Uma sugestão dada pela instrutora Valéria Baptista e que eu também concordo é que, independente da área/cargo da pessoa que irá trabalhar com Azure, ideal é que esta mantenha algum nível de contato com o Portal Azure, pois apenas observar relatórios, planilhas, documentações, ou configurar por código via IDE, não trás ao (à) profissinal tudo aquilo que o Azure oferece, nem as opções e suas variações de configurações. Inclusive porque, de forma geral, as evoluções do Azure surgem primeiro no Portal Azure, então manter este contato direto também é uma forma da pessoal estar sempre atualizada e motivada a evoluir seus sistemas.

## Desafio "Otimizando Custos no Azure"

- Um dos profissionais mais buscados hoje para quem trabalha com cloud é quem entende de FinOps, isto porque o gerenciamento e melhorias nos custos de com recursos em nuvem é uma tarefa crucial para saúde e evolução das empresas que levaram seus recursos para cloud. E um ponto interessante na carreira de FinOps é que a pessoa não precisa ter conhecimento e ser da área de TI. Muito pelo contrário: profissionais mais voltados às áreas financeira e contábil podem tem grande ascenção neste cargo;
- A avaliação de FinOps depende de diversos fatores como: CapEx, OpEx, quantidade e tipos de recursos, SLA de disponibilidade, região onde serão alocados, tipo da assinatura Azure envolvida, licenças de software que empresa já tinha anteriormente, etc. E tudo isso avaliando não só o cenário da empresa no momento da "virada pra nuvem", mas sobretudo avaliando continuamente como tudo está funcionando e fazendo as adequações necessárias para atingir a melhor performance com o menor custo;
- Outro ponto importante é que podemos pagar um plano de reserva, o que por ser um compromisso assumido com a Microsoft, nos dá um valor considerável de desconto em relação ao plano de pagamento por uso;
- Nisso o Azure dá total apoio ao profissinais, disponibilizando a "Calculadora TCO (Custo Total de Propriedade)", que nos permite mensurar de forma fácil o que teremos de recursos em nuvem em relação ao que temos no nosso On Premise, gerando estimativas claras, com possibilidade de exportar este relatório, seja para comparar com outros players, seja para apresentar para clientes e parceiros. Importante lembrar sempre que são estimativas e não valores exatos;
- Também temos disponível a "Calculadora de preço do Azure" onde podemos montar estimativas para qualquer recursos em suas diversas opções, garantindo assim o melhor custo x benefício para o negócio. Nela também é possível montar um relatório completo dos recursos necessários e exportar para melhor avaliação posterior;
- No portal temos o menu "Gerenciamento de Custos" onde está disponível adição de alertas, configuração de budgets, recomendações do Advisor e com isso fazer o devido acompanhamento dos custos que nossa assinatura está gerando e como posso melhorar estes custos;
- Nesse sentido, o uso de marcas (tags) é uma das melhores práticas para organizar nossos recursos e custos por eles gerados. O único detalhe é que tags não são herdáveis, o que requer uma atenção quando implementá-las.

## Desafio "Gerenciando Politicas em Acessos Azure"

- A Microsoft disponibiliza o "Portal de Confiança do Serviço", que é uma página onde estão diversas informações e documentações relativas as legislações, certificações, padrões técnicos e de governança de diversos setores, áreas e países. Neste portal o cliente encontra pode ler e baixar os documentos, a maioria de forma aberta e alguns fazendo login, para entender como a Microsoft lida com a segurança dos dados, sua governança, auditoria e alinhamento com países. Tais informações e documentos são atualizados continuamente e são uma ótima fonte de informações para apresentar a cliente e parceiros, tanto no momento da adoção, como durante os anos de uso dos serviços da cloud;
- A nível de segurança, podemos aplicar Bloqueios (Lock) em grupos de recursos e recursos diretamente, sendo que diferente das Marcas (Tags), os Bloqueios são herdáveis;
- Entre os Bloqueios temos o "Delete", para evitar exclusão do recurso/grupo e é o mais indicado para maioria dos casos. Mas também temos a opção "Read only", e essa deve ser usada com maior critério, pois pode impactar de grave em algumas situações. Portanto, uma análise cuidadosa dos cenários e suas ramificações é de extrema importância para definir qual formato de bloqueio é o mais adequado;
- Outro ponto importante é que o Bloqueio Delete, evita apenas as exclusão, então este bloqueio foi atribuido a um grupo de recursos, enquanto o recurso estiver no grupo ele obedecerá o bloqueio (herança), mas o recurso pode ser movido para outro grupo e então passará a obedecer os bloqueios do novo grupo;
- A Microsoft também oferece o "Microsoft Pureview", que é uma suite para governança e análise de riscos para os diversos recursos do Azure, mas também extendendo cada vez mais a produtos de outros nuvens. No Pureview podemos analisar o compliance, governança e segurança dos dados, além de questões de privacidade;
- Também temos as Policies, que podem ser aplicadas para assinaturas, recursos individuais, grupos, etc, e estão acima do nível de usuário, então mesmo que você seja o dono daquela conta no Azure, você será barrado em alguma ação onde uma Policy esteja aplicada;
- No Azure já temos diverdas Policies pré-configuradas para utilizarmos, mas também podemos criar nossas próprias afim de atender melhor nosso negócio;
- Quando aplicamos o Policy em ambientes que já tem recuros com regras diferentes dela, a Policy não altera e/ou exclui o recurso, mas informa em seus relatórios que temos uma situação de não compliance para o usuário tomar as ações que julgue necessário. Existe a opção de remediação, mas ela pode gerar problemas para aplicação, então deve ser usada em casos devidamente validadas;
- As Policies podem ser ativadas ou não no momento da criação e também podemos fazer download para arquivamento e/ou configuração e reuso posterior.
  
- 
