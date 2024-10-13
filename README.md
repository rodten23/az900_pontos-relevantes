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
