# comprar proxy móvel: quanto custa por GB, onde o 4G/5G brasileiro funciona e como testar sem assinatura

Quem digita "comprar proxy móvel" normalmente já decidiu o essencial: precisa de IPs de operadora, não de datacenter. A dúvida real vem depois. Quanto custa por GB, se a rede cobre o Brasil do jeito que o projeto precisa, e se existe uma forma de testar antes de assumir uma mensalidade.

É essa última parte que costuma travar a compra. Fornecedores de proxy móvel dedicado, do tipo que vende um IP brasileiro fixo por porta, trabalham na faixa de US$ 46 a US$ 99 por mês em listas públicas de provedores. Para quem só precisa de 3 GB para validar um fluxo de scraping ou segurar algumas contas em redes sociais, pagar um mês inteiro por um único IP é dinheiro parado.

A DataImpulse resolve isso com um modelo diferente: você compra tráfego, não tempo. O proxy móvel começa em US$ 2 por GB, o mínimo de entrada é US$ 5 e os GB comprados não expiram. 👉 [ver os planos de proxy móvel e criar a conta](https://bit.ly/dataimPulse)

Abaixo está o que muda entre os tipos de proxy, a tabela completa dos planos hoje publicados no site, o que checar antes de pagar e onde esse tipo de proxy é simplesmente exagero.

## O que você está comprando quando o pacote diz "proxy móvel"

Proxy móvel roteia seu tráfego por dispositivos reais conectados a redes de operadora em 3G, 4G, 5G ou LTE. O IP visto pelo site de destino não é um servidor em datacenter nem o roteador de uma casa: é um endereço que uma operadora atribuiu a um celular.

Isso muda o comportamento de dois jeitos.

Primeiro, a reputação do IP. Por causa do NAT de nível de operadora, centenas ou milhares de usuários móveis compartilham o mesmo endereço ao mesmo tempo. Sistemas anti-bot que bloqueiam faixas inteiras de datacenter não podem simplesmente bloquear essas faixas, porque estariam derrubando usuários legítimos de celular. É por isso que proxy móvel passa onde residencial às vezes trava.

Segundo, o preço. Essa mesma reputação é o motivo da escassez: IP de operadora real é mais caro de manter que IP de servidor, e o mercado cobra por isso. Um IP de datacenter sai por US$ 0,50/GB, um residencial por US$ 1/GB e um móvel por US$ 2/GB na tabela da DataImpulse. A Bright Data anuncia US$ 8,40/GB no modo avulso para a linha móvel, o que dá a dimensão da diferença entre o topo e o piso do mercado.

Existe uma consequência prática nessa diferença: pagar tarifa móvel para uma tarefa que o residencial resolve é desperdício de orçamento. Se o alvo não bloqueia IP residencial, use residencial. Guarde o móvel para os casos em que só IP de operadora passa.

> A regra que evita gasto desnecessário: descubra qual é o nível mais barato que ainda funciona no seu alvo, e só suba para móvel quando o residencial começar a falhar.

## Quanto custa, em números

Faixas praticadas no mercado para proxy móvel ficam entre US$ 2 e US$ 15 por GB, dependendo do provedor, do tamanho do pool e do nível de direcionamento geográfico. O que determina onde você cai dentro dessa faixa:

- **Modelo de cobrança.** Por GB, você paga pelo que consome. Por porta/IP/mês, você paga mesmo sem usar. Para uso irregular, o segundo modelo é o mais caro dos dois.
- **Expiração do tráfego.** Pacotes que zeram no fim do mês transformam GB não usado em prejuízo. Tráfego que não expira muda a conta em projetos com demanda em picos.
- **Direcionamento.** País costuma estar incluído. Cidade, estado, CEP e ASN geralmente são cobrados à parte. Na DataImpulse, esse direcionamento avançado sai pelo dobro do valor base.
- **Volume.** Desconto real começa a partir de 1 TB. Abaixo disso, a diferença entre planos é mais sobre o tamanho do pacote do que sobre o preço unitário.

## Todos os planos publicados hoje

A DataImpulse trabalha com recarga por uso, não com assinatura. Você escolhe o tipo de proxy, digita a quantidade de GB e o preço aparece na hora. Os níveis abaixo são os pontos de referência que a empresa divulga; nada impede comprar 7 GB ou 30 GB em vez dos valores redondos.

| Tipo de proxy | Nível | Tráfego | Preço total | Preço por GB | Observações | Comprar |
| --- | --- | --- | --- | --- | --- | --- |
| Residencial | Intro | 5 GB | US$ 5 | US$ 1,00 | Pacote de entrada para novos usuários | [assinar o Intro residencial](https://bit.ly/dataimPulse) |
| Residencial | Basic | 50 GB | US$ 50 | US$ 1,00 | Pool de 90M+ IPs, 195 países | [assinar o Basic residencial](https://bit.ly/dataimPulse) |
| Residencial | Advanced | 1 TB | US$ 800 | US$ 0,80 | Desconto de volume de 20% | [assinar o Advanced residencial](https://bit.ly/dataimPulse) |
| Residencial | Custom | 5 TB+ | A partir de US$ 4.000 | Negociável | Configuração personalizada | [falar sobre volume residencial](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | US$ 5 | US$ 0,50 | Nível mais barato da tabela | [assinar o Intro datacenter](https://bit.ly/dataimPulse) |
| Datacenter | Basic | 100 GB | US$ 50 | US$ 0,50 | Sessões concorrentes ilimitadas | [assinar o Basic datacenter](https://bit.ly/dataimPulse) |
| Datacenter | Advanced | 1 TB | US$ 450 | US$ 0,45 | Desconto de volume | [assinar o Advanced datacenter](https://bit.ly/dataimPulse) |
| Datacenter | Custom | 5 TB+ | A partir de US$ 2.250 | Negociável | Configuração personalizada | [falar sobre volume datacenter](https://bit.ly/dataimPulse) |
| **Móvel** | Intro | 2,5 GB | US$ 5 | US$ 2,00 | 3G/4G/5G/LTE, rotação e sessão fixa | [começar com 2,5 GB de proxy móvel](https://bit.ly/dataimPulse) |
| **Móvel** | Basic | 25 GB | US$ 50 | US$ 2,00 | Mesmos recursos do Intro, mais volume | [assinar o Basic móvel](https://bit.ly/dataimPulse) |
| **Móvel** | Advanced | 1 TB | US$ 1.600 | US$ 1,60 | Inclui gerente de conta dedicado | [assinar o Advanced móvel](https://bit.ly/dataimPulse) |
| **Móvel** | Custom | 5 TB+ | A partir de US$ 8.000 | Negociável | Configuração corporativa | [falar sobre volume móvel](https://bit.ly/dataimPulse) |
| Residencial premium | Intro | 1 GB | US$ 5 | US$ 5,00 | Pool de maior qualidade, resposta abaixo de 50 ms | [assinar o Intro premium](https://bit.ly/dataimPulse) |
| Residencial premium | Basic | 10 GB | US$ 50 | US$ 5,00 | Gerente de conta pessoal | [assinar o Basic premium](https://bit.ly/dataimPulse) |
| Residencial premium | Advanced/Custom | 1 TB+ | A partir de US$ 4.000 | US$ 4,00 | Todos os direcionamentos disponíveis | [falar sobre o premium](https://bit.ly/dataimPulse) |

Duas observações que ajudam a ler a tabela. O desconto de volume de 20% aparece de forma consistente no nível de 1 TB nas linhas residencial e móvel, o que significa que o preço por GB cai justamente quando o volume justifica economizar. E o móvel é o único tipo em que o nível de entrada oferece menos tráfego pelo mesmo US$ 5: 2,5 GB em vez dos 5 GB do residencial, exatamente porque o GB móvel custa o dobro.

## Cobertura, localização e o caso brasileiro

A DataImpulse declara um pool de mais de 16 milhões de IPs móveis distribuídos por 195 localidades, com tipos de rede 3G, 4G, 5G e LTE. O direcionamento por país está incluído no preço base. Cidade, estado, CEP e ASN são add-ons pagos.

Isso define bem o que dá e o que não dá para fazer. Se o projeto é verificar como um anúncio aparece no Rio de Janeiro, checar preço em marketplace com localização brasileira, monitorar SERP a partir de São Paulo ou rodar contas que precisam parecer usuários móveis comuns, o direcionamento por país resolve, e o por cidade resolve com custo extra.

Se o projeto precisa de um IP brasileiro fixo, que permaneça exatamente o mesmo por dias, dentro de uma sessão longa de login, a conta muda. Pool rotativo por GB não foi desenhado para isso. Nesse cenário, o formato correto é alugar uma porta dedicada mensal, o que explica por que provedores de proxy 4G dedicado no Brasil cobram na casa de US$ 46 a US$ 99 por mês por um único endereço. Você troca flexibilidade por estabilidade, e paga por tempo em vez de por volume.

text
Fluxo em duas etapas, para quem tem os dois tipos de demanda:
1. Pool móvel por GB -> validação, scraping, verificação de anúncio, testes de QA
2. Porta dedicada mensal -> sessões longas de login, contas que exigem IP fixo


## Como comprar, passo a passo

O processo inteiro leva poucos minutos e não exige contato com vendas.

1. **Criar a conta.** Dá para usar Google, GitHub ou LinkedIn, ou preencher o formulário com nome, senha e uma seleção de caso de uso. A verificação vem por e-mail.
2. **Escolher o tipo de proxy.** No painel, aparecem quatro cartões: residencial, datacenter, móvel e residencial premium. O móvel é o que interessa aqui.
3. **Definir a quantidade.** Digite o volume em GB e o preço é calculado em tempo real. O mínimo é US$ 5, que no móvel equivale a 2,5 GB.
4. **Pagar.** Cartão via Stripe e cripto via Cryptomus (Bitcoin, Ethereum, USDT e Litecoin) aparecem como as vias principais. Análises independentes também citam PayPal, transferência bancária, Alipay, Apple Pay e Google Pay, com disponibilidade variando por região.
5. **Gerar a lista de proxies.** No painel você escolhe país, modo de rotação, protocolo, formato de saída e quantidade. A lista sai na hora, com uma string cURL que atualiza conforme você mexe nas configurações.
6. **Configurar a autenticação.** Usuário e senha ou lista de IPs autorizados, nos dois casos.
7. **Conectar.** Rotação por requisição usa a porta 823 para HTTP/HTTPS e 824 para SOCKS5. Sessões fixas usam portas entre 10000 e 20000.

👉 [abrir o painel, criar a conta e gerar a lista de proxies](https://bit.ly/dataimPulse)

## Os limites que não aparecem na página de vendas

Essa parte costuma ser o motivo de reclamações em qualquer provedor de proxy móvel, então vale ler antes de pagar.

**Não existe plano gratuito.** O acesso começa em US$ 5, sem camada de teste grátis. O que existe é garantia de reembolso de 7 dias nos planos Intro, válida para pagamentos com cartão e desde que menos de 80% do tráfego já tenha sido consumido. Compra em cripto no plano Intro não é reembolsável.

**Sessão fixa não é garantia de duração.** Sessões aderentes duram em média 30 minutos e podem ser configuradas até 120 minutos, mas a DataImpulse deixa claro que não controla isso: os IPs vêm de usuários reais, e quando o dispositivo de origem fica offline, a conexão roda automaticamente para o próximo IP disponível. Em teste de suporte independente publicado pelo HostAdvice, o agente de chat confirmou exatamente essa mecânica, com resposta em cerca de 7 minutos por um atendente humano identificado. Se o seu script exige a mesma sessão por horas, planeje o tratamento de rotação desde o início.

**Direcionamento avançado custa o dobro.** Cidade, estado, CEP e ASN consomem aproximadamente o dobro do tráfego no residencial. Em volume alto, isso muda o custo efetivo por requisição bem-sucedida.

**Não há latência publicada.** A empresa divulga taxa de sucesso de 99,51% e uptime, mas não publica um número de tempo de resposta médio. Isso pesa contra em comparações com provedores que assumem um valor de latência em contrato.

**O desconto de volume só aparece no 1 TB.** Para quem consome 50 GB ou 100 GB, o preço por GB fica estável, sem queda progressiva.

**O perfil de uso importa mais que o preço unitário.** Se metade das requisições for bloqueada, o custo real por dado coletado é o dobro do que está na tabela. Um pool mais caro com taxa de sucesso alta pode sair mais barato no fim.

## Onde o proxy móvel é exagero

Datacenter sai por US$ 0,50/GB e residencial por US$ 1/GB dentro da mesma conta. Isso permite escalonar por dificuldade do alvo em vez de comprar o nível mais caro por precaução.

- Páginas públicas, bases abertas e sites sem proteção anti-bot: datacenter resolve.
- E-commerce, SERP, marketplaces com reputação de ASN: residencial resolve, com pool de 90M+ IPs em 195 países.
- Aplicativos móveis, plataformas mobile-first e sistemas que exigem padrão de tráfego de celular: aí o móvel passa a ser o nível mais barato que ainda funciona.

Vale registrar o que a DataImpulse não é, para evitar expectativa errada: não é revenda de ISP estático, não é API gerenciada de scraping e não é proxy web gratuito. Necessidades de IP fixo de longa duração e de desbloqueio gerenciado ficam fora do escopo dela.

## Perguntas frequentes

**Precisa de assinatura ou contrato mensal?**
Não. A cobrança é por uso, no modelo de recarga. Os GB comprados permanecem na conta até serem consumidos, sem reset mensal.

**O tráfego expira?**
Não. É o principal diferencial do modelo, e resolve o problema de pacotes que zeram no fim do mês quando o projeto está parado.

**Proxy móvel funciona no Brasil?**
O direcionamento por país está incluído no preço base e a cobertura declarada alcança 195 localidades. Direcionamento por cidade ou região dentro do Brasil entra como add-on pago, com consumo dobrado.

**Dá para testar de graça?**
Não há camada gratuita. O caminho de menor risco é começar pelos 2,5 GB por US$ 5 e, se o pagamento for no cartão, usar a garantia de 7 dias do plano Intro.

**Quais protocolos são suportados?**
HTTP, HTTPS e SOCKS5, nos quatro tipos de proxy.

**Qual a diferença real entre móvel e residencial?**
O IP móvel vem de torre de celular e é atribuído por operadora; o residencial vem de conexão de banda larga doméstica. A diferença de reputação explica tanto a resistência a bloqueio quanto o preço maior.

**Como autenticar?**
Usuário e senha ou lista de IPs autorizados.

## O que decidir agora

Se o objetivo é testar proxy móvel com gasto baixo e sem compromisso mensal, o caminho é comprar o pacote mínimo, direcionar para o país certo e medir a taxa de sucesso nos seus próprios alvos antes de escalar. Tráfego que não expira permite fazer exatamente isso: usar 800 MB hoje, deixar o resto parado duas semanas e continuar depois, sem perder nada.

Se o projeto cresce para centenas de GB, o nível de 1 TB com desconto de 20% passa a fazer sentido, e no móvel ele ainda traz gerente de conta dedicado. Abaixo disso, comprar volume maior só para "garantir" é comprar GB que talvez fiquem encostados.

👉 [comparar os planos e começar pelos 2,5 GB de proxy móvel por US$ 5](https://bit.ly/dataimPulse)
