# RESUMO1-AZURECLOUD-DIO
Primeiro resumo sobre os fundamentos da Cloud Azure da Microsoft

Devido ao alto custo de aquisição e manutenção de equipamentos de computação, a ambiente Cloud acaba sendo uma estratégia muito importante, principalmente, para grandes e médias empresas. 
No ambiente CLOUD, a empresa (contratante) não gasta com infraestrutura e manutenção; o gasto é com o serviço utilizado.

O sistema de Cloud possui 3 modelos:
- ON PREMISE (Privado), quando os equipamentos estão armazenados no LOCAL de responsabilidade da empresa;
- CLOUD (Público), quando os equipamentos são de Data Centers espalhados por todo o Mundo; e
- HÍBRIDO (HYBRID), quando a empresa utiliza dos benefícios de nuvem privada e nuvem pública de forma concomitante.

Existem 4 tipos de uso para o ambiente de Cloud:
- IaaS (Infrastructure as a Service) – Infraestrutura como Serviço
Oferece recursos básicos de computação, como servidores, armazenamento, redes e sistemas operacionais, de forma virtualizada e sob demanda.
Exemplos: Amazon EC2 (AWS), Microsoft Azure Virtual Machines, Google Compute Engine.

- PaaS (Platform as a Service) – Plataforma como Serviço
Fornece uma plataforma completa para desenvolvimento, execução e gerenciamento de aplicações sem a necessidade de gerenciar a infraestrutura subjacente. Inclui sistemas operacionais, bancos de dados, servidores web, etc.
Exemplos: Google App Engine, Microsoft Azure App Service.

- SaaS (Software as a Service) – Software como Serviço
Disponibiliza softwares prontos, acessíveis via internet, sem necessidade de instalação ou manutenção pelo usuário. O provedor gerencia tudo: desde infraestrutura até atualizações e segurança.
Exemplos: Gmail, Microsoft 365, Salesforce.

- FaaS (Function as a Service) – Função como Serviço (ou computação serverless - sem servidor)
Permite que os desenvolvedores escrevam e implantem código em forma de funções, sem se preocupar com a infraestrutura ou com a necessidade de manter servidores. A cobrança ocorre com base no número de execuções e consumo de recursos.
Exemplos: AWS Lambda, Google Cloud Functions, Azure Functions.

Os provedores de nuvem, como Azure, AWS e GCP, estruturam sua infraestrutura física de forma a oferecer serviços com alta disponibilidade, baixa latência e resiliência. Para isso, usam Regions e Zones pelo Mundo, distribuindo sua infraestrutura de formas estratégicas.

- Regions (Regiões): São grandes áreas geográficas onde os provedores de nuvem mantêm seus data centers físicos. Cada Region é composta por um ou mais data centers agrupados para fornecer serviços de forma localizada.
- Zones (Zonas de Disponibilidade): São subconjuntos dentro de uma Region. Cada Zone representa um ou mais data centers físicos, mas separados e independentes em termos de energia, rede e refrigeração.

As Regions e Zones são importantes, principalmente, pelos seguintes motivos:
- Latência: escolher uma região próxima ao cliente reduz o tempo de resposta.
- Compliance: algumas empresas precisam armazenar dados em determinadas regiões por questões legais.
- Alta disponibilidade: distribuir recursos entre zonas evita indisponibilidades em caso de falhas.
- Resiliência: aplicações distribuídas entre múltiplas zonas são mais resistentes a desastres.


Benefícios da Nuvem (Cloud)

- Alta Disponibilidade:
Capacidade dos serviços na nuvem de permanecerem acessíveis e funcionais mesmo diante de falhas em parte da infraestrutura. É garantido usando a redundância de sistemas e a distribuição entre múltiplas regiões e zonas de disponibilidade, minimizando interrupções e garantindo que aplicações estejam sempre acessíveis aos usuários.

- Escalabilidade:
Capacidade de aumentar ou diminuir os recursos computacionais conforme a necessidade.
Aplicação:
 - De forma manual ou automática (Auto Scaling).
 - Ampliando servidores, armazenamento ou largura de banda rapidamente.
Tem como vantagem, atender as variações de demanda sem comprometer a performance.

- Previsibilidade:
Facilidade em prever custos, desempenho e comportamentos do sistema na nuvem.
Dessa forma, as empresas tem as seguintes garantias:
 - Modelos claros de precificação (pay-as-you-go).
 - Ferramentas de monitoramento e relatórios.
Assim, permite melhorar o planejamento financeiro e operacional.

- Governança:
Conjunto de políticas, controles e processos que asseguram a utilização adequada dos recursos na nuvem.
Aplicação:
 - Definição de regras de acesso, segurança e compliance.
 - Uso de ferramentas para auditoria e rastreabilidade.
Vantagem:
Garante que os recursos sejam utilizados de forma segura, ética e em conformidade com regulamentações.

- Elasticidade:
Capacidade de ajustar automaticamente os recursos provisionados de acordo com a demanda, em tempo real.
Como funciona?
 - Diferente da escalabilidade que pode ser manual, a elasticidade ocorre automaticamente.
Vantagem:
Evita ociosidade ou sobrecarga de recursos, otimizando custos e desempenho.

- Confiabilidade:
Garantia de que os sistemas e serviços funcionarão conforme o esperado, mesmo diante de falhas ou problemas.
Aplicação:
 - Infraestruturas redundantes.
 - Planos de recuperação de desastres (Disaster Recovery).
Vantagem:
Confiança na continuidade dos negócios sem perdas significativas.

- Segurança:
Proteção dos dados, aplicações e infraestrutura contra ameaças e acessos não autorizados.
Implementação: 
 - Criptografia de dados.
 - Controles de acesso rigorosos.
 - Monitoramento e detecção de ameaças.
Vantagem:
Mitiga riscos de ataques cibernéticos e vazamento de informações.

- Gerenciabilidade:
Facilidade no gerenciamento, configuração e monitoramento de todos os recursos na nuvem.
Como é realizada?
 - Plataformas centralizadas de gestão.
 - Automação de tarefas administrativas (deploy, backup, atualizações).
Vantagem:
Reduz esforço operacional, melhora a eficiência e evita erros humanos.

CapEx e OpEx

Outro grande benefício da computação em nuvem é a otimização dos custos e das despesas operacionais das empresas, tornando-se um aspecto fundamental e constantemente avaliado para garantir eficiência financeira e promover a redução de gastos.

CapEx (Capital Expenditure) – Despesa de Capital
São os gastos com bens duráveis e investimentos de longo prazo, como a compra de servidores, infraestrutura física, data centers, licenças de software, etc.

No modelo tradicional (on-premises):
 - As empresas precisam adquirir toda a infraestrutura necessária antecipadamente.
 - Envolve alto investimento inicial.
 - Responsabilidade total pela manutenção, atualização e segurança dos equipamentos.

Desvantagens:
 - Imobiliza capital.
 - Pode gerar custos excessivos com recursos subutilizados ou obsoletos.

OpEx (Operational Expenditure) – Despesa Operacional
São os gastos relacionados à operação contínua de um serviço ou sistema, como pagamento de energia elétrica, manutenção, salários, ou no caso da nuvem, o uso sob demanda.

Com a computação em nuvem:
 - O modelo se torna predominantemente OPEX.
 - As empresas pagam somente pelo que utilizam.
 - Não há necessidade de grandes investimentos iniciais.
 - Reduz os custos com manutenção e atualizações, já que são responsabilidade do provedor de nuvem.

Vantagens:
 - Flexibilidade financeira.
 - Facilidade para ajustar os custos conforme a necessidade.
 - Redução de riscos financeiros com infraestrutura.


A plataforma Azure da Microsoft possui uma assinatura como Estudante, que disponibiliza um valor para que o aluno realize vários testes em laboratório e desenvolva suas habilidades.

Dessa forma, percebemos como o ambiente em nuvem é fundamental para impulsionar o crescimento tecnológico. A escalabilidade, o gerenciamento e a segurança que oferece permitem que as empresas estejam cada vez mais preparadas para expandir suas operações e maximizar seus lucros, aliando o avanço tecnológico à expertise de profissionais altamente capacitados.

