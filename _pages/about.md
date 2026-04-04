---
permalink: /
title: "Portfólio sobre MVP inspecão visual automatizada para indústria"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
> **1.INTRODUÇÃO**

Este portfólio consolida a fase de Design Estratégico do projeto de **Mínimo Produto Viável (MVP)** voltado à realização de um sistema de inspeção visual automatizada.
O site detalha o mapeamento dos Stakeholders e a estruturação do modelo de negócio via **Business Model Canvas (BMC)** . Além disso, apresenta as análises de viabilidade econômica, fundamentadas em indicadores de **ROI (Retorno sobre Investimento)**, **Payback**, e o estudo de **Impacto Ambiental**, demonstrando o valor sistêmico e a sustentabilidade da proposta para o cenário industrial brasileiro.

>**2. JUSTIFICATIVA**

A identificação dos **Stakeholders** é uma etapa crítica nesta fase do projeto, pois o sucesso sistema de inspeção automatizada depende do alinhamento entre as expectativas técnicas e os interesses das partes envolvidas. Não basta o sistema funcionar, ele precisa ser aceito e gerar valor para quem utiliza ou financia.
Conforme a gestão de projetos, os stakeholders são grupos que afetam ou são afetados pelo MVP. Para o nosso sistema industrial, classificamos esses agentes em dois níveis: 
**Stakeholders Internos:** São aqueles que possuem vínculo direto com a operação, como os gerentes de produção e os operadores de linha.
**Stakeholders Externos:** Incluem agentes fora da estrutura organizacional, mas fundamentais para o ecossistema, como os fornecedores de hardware, órgãos reguladores de segurança e os clientes finais, que receberão produtos com maior garantia de qualidade.

No cenário do MVP do grupo, **internos** são (participam ativamente da execução e do ambiente do projeto):

 - Alunos 
 - Professores orientadores
 - Diretoria / Patrocinador

**Externos** (são impactados ou influenciam, mas não participam do dia a dia):

 - Fornecedores de componentes
 - Clientes do MVP
 - Órgãos reguladores (Inmetro, ISO, etc.)
 - Concorrentes
 - Comunidade acadêmica (outros pesquisadores)
 - Famílias dos alunos

## **Análise inicial de viabilidade do negócio**

A análise inicial de viabilidade do negócio do presente **Produto Mínimo Viável (MVP)** deve ser compreendida como uma etapa indispensável para verificar se a solução proposta, além de tecnicamente aplicável, apresenta potencial de retorno econômico e sustentabilidade operacional. No caso deste projeto, o MVP consiste em um sistema físico de inspeção visual automatizada destinado à identificação de falhas em peças ou produtos em ambientes industriais, utilizando câmera, sensores, processamento computacional e um mecanismo de segregação de itens não conformes. Conforme o portfólio do projeto, a proposta busca reduzir falhas humanas, retrabalho, desperdícios e perdas decorrentes de inspeções manuais pouco padronizadas, oferecendo uma solução de baixo custo relativo e com potencial de aplicação prática em linhas de produção. 
Diferentemente de uma análise limitada ao custo de montagem, a avaliação de viabilidade do MVP deve considerar também o ciclo de vida do hardware, abrangendo manutenção preventiva, substituição de componentes, possibilidade de danos, durabilidade esperada e custos de operação. Tal abordagem é especialmente relevante porque, em sistemas físicos de inspeção, o desempenho econômico não depende apenas da construção inicial do protótipo, mas também de sua capacidade de permanecer funcional ao longo do tempo com custos de suporte tecnicamente aceitáveis.

## **Impacto Ambiental (Sustentabilidade Operacional e Otimização de Recursos)**

O MVP atua diretamente na redução da entropia produtiva (desperdício de energia), transformando a precisão técnica em preservação ambiental.
**Mitigação de Resíduos Sólidos (Redução de Scrap):** A inspeção manual é inerentemente subjetiva e sujeita à fadiga, o que gera o descarte indevido de peças boas ou o processamento de peças ruins. Ao implementar uma métrica binária e constante, reduzimos drasticamente o desperdício de matéria-prima e o volume de resíduos industriais descartados.
**Eficiência Energética Sistêmica:** Detectar uma falha no Estágio 1 é uma estratégia de conservação de energia. Evitamos que uma unidade defeituosa percorra toda a linha, consumindo eletricidade, lubrificantes e desgaste mecânico de máquinas em estágios posteriores. É o conceito de "energia incorporada": não gastamos recursos em um produto que não chegará ao mercado.
Ciclo de Vida e Pegada de Carbono: Ao garantir que 100% dos produtos saiam em conformidade, otimizamos toda a cadeia logística. Menos devoluções significam menos transporte desnecessário e, consequentemente, uma menor pegada de carbono associada à logística reversa.

## **Reflexo Econômico (Viabilidade Estratégica e Saúde Financeira)**

O custo de um erro aumenta exponencialmente conforme ele avança na cadeia (Regra de 10 de Myers), o que significa que o custo para corrigir um erro aumenta em dez vezes para cada etapa do ciclo detectado. Detectar o erro dentro da fábrica custa centavos; um recall ou uma devolução custa milhões e corrói a reputação da marca. O sistema atua como um seguro de fidelidade técnica, aqui, a engenharia se traduz em lucratividade e proteção de ativos, blindagem de marca e redução do custo da "não-qualidade":
**Vantagem Competitiva e Otimização de OpEx:** A automação da inspeção permite uma cadência produtiva superior com um custo operacional (OpEx) por unidade menor a longo prazo. Isso gera uma margem de manobra financeira para reinvestimento em Pesquisa e Desenvolvimento (P&D).
Rastreabilidade e Dados como Ativo: Além da inspeção, o sistema gera logs de dados. No mercado atual (2026), a informação é ouro. Ter o histórico de 100% da produção oferece uma camada de proteção jurídica e comercial contra falhas sistêmicas, atraindo investidores que buscam segurança e escalabilidade baseada em dados (Data-Driven).

## **Materiais e composição do hardware do MVP**

O sistema proposto é formado por um conjunto de componentes eletrônicos, mecânicos e computacionais que viabilizam a detecção da peça, a captura da imagem, o processamento do resultado da inspeção e a atuação física sobre o objeto analisado. De acordo com a tabela de hardware do projeto, os principais elementos do MVP são: microcontrolador, câmera, sensor de presença, atuador do tipo servo motor, sistema de iluminação controlada, indicadores visuais, computador ou processador, estrutura mecânica, protoboard com jumpers e fonte de alimentação. Cada um desses itens cumpre uma função específica na operação do sistema, assegurando a integração entre detecção, processamento e resposta automática. 
A escolha desses componentes evidencia uma estratégia de desenvolvimento orientada à acessibilidade e à modularidade. O uso de alternativas como Arduino Uno, Arduino Mega ou ESP32; webcam USB comum; sensor infravermelho; servo motor de baixo custo; LEDs indicadores; e estrutura em MDF, acrílico, alumínio ou peças impressas em 3D demonstra que o MVP foi concebido para ser tecnicamente viável no contexto acadêmico, sem exigir, nesta fase, equipamentos industriais de alto valor agregado. Essa modularidade também favorece a continuidade do projeto, uma vez que permite a substituição individual de módulos sem comprometer a arquitetura geral do sistema. 

## **Estimativa de custos de montagem inicial**

Para a análise preliminar de viabilidade, pode-se adotar uma projeção didática de custos com base na configuração de hardware descrita. Considerando uma montagem em escala de protótipo, com componentes de mercado acessíveis e estrutura simplificada, o custo direto do MVP pode situar-se entre R$ 1.000,00 e R$ 2.500,00, dependendo da qualidade dos materiais, da necessidade de aquisição de unidade computacional dedicada e do tipo de estrutura mecânica adotada.
Em um cenário intermediário, pode-se estimar o custo inicial do sistema em aproximadamente R$ 1.800,00, incluindo microcontrolador, câmera, sensor, servo motor, iluminação, indicadores visuais, cabeamento, fonte de alimentação, protoboard e materiais estruturais. Esse valor representa uma estimativa compatível com a proposta de MVP acadêmico, cuja finalidade é validar a solução antes de uma eventual expansão para versões mais robustas. Caso o projeto exija a compra exclusiva de notebook, Raspberry Pi ou estrutura mecânica mais resistente, esse custo poderá ser ampliado.
Sob a ótica financeira, esse investimento inicial é relativamente reduzido quando comparado a sistemas comerciais proprietários de inspeção visual industrial, o que favorece a atratividade do projeto enquanto solução de entrada ou prova de conceito.

## **Projeções de manutenção, reparos e custos recorrentes**

Para além do investimento inicial, a viabilidade do sistema depende da previsão de custos recorrentes associados à manutenção e aos reparos. Em um MVP com arquitetura modular e componentes de baixo custo, a manutenção tende a assumir papel central, pois a continuidade operacional do sistema depende da reposição pontual de itens sujeitos a falhas e desgaste.
No presente projeto, a manutenção preventiva pode abranger atividades como limpeza da lente da câmera, inspeção do sensor de presença, verificação da intensidade e posicionamento da iluminação, reaperto de elementos estruturais, reorganização de cabos, teste de alimentação elétrica e análise do funcionamento do servo motor. Tais procedimentos são particularmente importantes porque pequenas variações físicas, como deslocamento da câmera ou alteração da iluminação, podem comprometer o desempenho do algoritmo de visão computacional, mesmo que os componentes eletrônicos permaneçam energizados.
Em uma projeção didática, a manutenção preventiva e corretiva do sistema pode representar um custo anual entre R$ 200,00 e R$ 600,00, a depender da intensidade de uso, da frequência de testes e do ambiente de instalação. Em um cenário de referência, pode-se considerar uma despesa de R$ 400,00 por ano para manutenção periódica, acrescida de uma reserva estimada de R$ 300,00 para substituições eventuais de peças críticas, como servo motor, fonte de alimentação ou conjuntos de cabos. Nesse caso, o custo complementar ao investimento inicial seria de R$ 700,00 no primeiro ano.

## **Vida útil, prazo de utilização e necessidade de substituições**

No contexto deste projeto, não se recomenda tratar o sistema como um produto com prazo de validade fixo, mas sim como um conjunto técnico com vida útil dependente da intensidade de uso, da qualidade da instalação e da manutenção realizada. Assim, a durabilidade do MVP deve ser interpretada a partir do comportamento individual de seus componentes.
O microcontrolador, os LEDs indicadores, parte da estrutura mecânica e o processador tendem a apresentar maior longevidade, desde que protegidos de sobretensão, umidade, calor excessivo e impactos físicos. A câmera, o sensor de presença e o sistema de iluminação possuem durabilidade intermediária, mas podem sofrer perda de desempenho em razão de poeira, desalinhamento, oscilação luminosa ou falhas de conexão. O servo motor, por sua vez, configura-se como o componente de maior desgaste previsível, em razão de sua atuação repetitiva no mecanismo de segregação das peças. Esse item está sujeito a fadiga mecânica, perda de torque, folgas e travamentos, podendo demandar substituição com maior frequência do que os demais elementos.
A existência de alternativas equivalentes para vários componentes representa um fator positivo para a viabilidade do negócio. O projeto admite diferentes opções de microcontroladores, câmeras e plataformas de processamento, o que reduz o risco de dependência de um único fornecedor ou modelo. Dessa forma, a substituição de componentes por alternativas compatíveis tende a ser operacionalmente simples e economicamente administrável. 

## **Riscos de danos operacionais no hardware**

Em sistemas físicos aplicados à inspeção visual, os danos não decorrem apenas de falhas internas dos dispositivos, mas também das condições do ambiente de operação. Entre os principais riscos de dano ao hardware do MVP podem ser destacados o superaquecimento, a instabilidade da alimentação elétrica, a quebra ou deformação da estrutura mecânica, o desgaste do servo motor, o desalinhamento da câmera, a incidência de poeira sobre lentes e sensores, e os maus contatos em protoboard e jumpers.
Esses fatores tornam-se ainda mais relevantes em ambientes industriais, nos quais vibração, partículas suspensas, calor, umidade e resíduos de processo podem acelerar o desgaste dos componentes. Por essa razão, mesmo tratando-se de um MVP acadêmico, é recomendável adotar medidas mínimas de proteção, como fixação rígida da câmera, organização do cabeamento, isolamento parcial dos circuitos, controle da iluminação externa e reforço da estrutura de suporte. Tais cuidados aumentam a confiabilidade do protótipo e reduzem a frequência de intervenções corretivas, melhorando, consequentemente, sua viabilidade econômica ao longo do uso.

## **Projeção econômica do ciclo de vida do MVP**

A avaliação financeira do MVP torna-se mais consistente quando incorpora o custo total estimado do primeiro ano de operação. Considerando-se, para fins didáticos, um investimento inicial de R$ 1.800,00, acrescido de R$ 400,00 de manutenção anual e R$ 300,00 de substituições eventuais, obtém-se um custo total aproximado de R$ 2.500,00 no primeiro ano de uso.
Supondo-se que a utilização do sistema seja capaz de evitar perdas equivalentes a R$ 500,00 por mês, por meio da redução de refugo, retrabalho e falhas de inspeção, o benefício econômico anual alcançaria R$ 6.000,00. Nessa hipótese, o sistema geraria saldo positivo já no primeiro ano de operação, o que constitui um indicativo favorável de viabilidade financeira.
Essa projeção é compatível com a natureza do projeto, pois o valor economizado não depende necessariamente de grandes escalas de produção. Mesmo em operações moderadas, pequenas reduções mensais de perdas acumulam resultados relevantes ao longo do ano, especialmente quando o custo de manutenção do hardware permanece sob controle.

## **Indicadores financeiros aplicados ao projeto**

Para mensurar a atratividade econômica do MVP, podem ser empregados os indicadores de retorno sobre investimento, prazo de retorno e margem de lucro.
O Retorno sobre Investimento (ROI) permite verificar a eficiência econômica do capital aplicado e pode ser calculado da seguinte forma:
**ROI (%) = [(Ganho Obtido – Investimento Total) / Investimento Total] × 100**

Aplicando-se os valores da projeção anterior, tem-se:

**ROI (%) = [(6.000 – 2.500) / 2.500] × 100 = 140%**

Esse resultado indica que, ao final do primeiro ano, o sistema seria capaz de gerar retorno líquido equivalente a 140% do valor investido, o que sugere forte potencial de viabilidade, ainda que em caráter estimativo.
O payback, por sua vez, representa o tempo necessário para recuperação do investimento:

**Payback = Investimento Total / Economia Mensal**

Logo:

**Payback = 2.500 / 500 = 5 meses**

Isso significa que o valor investido no sistema seria recuperado em aproximadamente cinco meses, prazo que pode ser considerado favorável para uma solução de automação de pequeno porte.
A margem de lucro, caso o MVP venha a ser futuramente ofertado como produto, pode ser estimada pela fórmula:

**Margem de Lucro (%) = (Lucro Líquido / Receita Total) × 100**

Admitindo-se uma hipótese de comercialização do sistema por R$ 4.500,00, com custo total de montagem, ajustes, instalação e suporte inicial de R$ 3.000,00, o lucro líquido por unidade seria de R$ 1.500,00, resultando em:

**Margem de Lucro = (1.500 / 4.500) × 100 = 33,3%**

Esse percentual demonstra que a solução pode apresentar lucratividade razoável, mesmo considerando despesas de suporte e substituição de componentes ao longo da operação inicial.

## **Síntese da viabilidade inicial do negócio**

Com base nas projeções apresentadas, observa-se que a viabilidade inicial do negócio associado ao MVP do sistema de inspeção visual mostra-se promissora. O projeto parte de um investimento relativamente baixo, utiliza componentes acessíveis e substituíveis, admite manutenção simplificada e apresenta potencial para reduzir perdas produtivas por meio da automação da inspeção.
A análise do ciclo de vida do hardware evidencia que os custos de reparo, manutenção e substituição, embora existentes, não tendem a comprometer de forma significativa a atratividade econômica da proposta. Ao contrário, por se tratar de uma arquitetura modular, os eventuais problemas operacionais podem ser resolvidos de forma pontual, sem exigir a substituição integral do sistema.
Desse modo, conclui-se que o MVP apresenta indícios favoráveis de viabilidade técnica e econômica, especialmente como solução de caráter acadêmico e experimental voltada à validação de mercado. Ainda assim, ressalta-se que as estimativas monetárias aqui utilizadas possuem caráter didático e preliminar, devendo ser refinadas em etapas posteriores do projeto, com base na aquisição efetiva dos materiais, nos resultados dos testes e no desempenho real do sistema em condições mais próximas do ambiente industrial.

## **Mapeamento de Canais**

A eficácia do sistema de inspeção visual automatizada depende da escolha de canais que facilitem não apenas a venda, mas também a demonstração técnica e o suporte contínuo. Com base no refinamento do Business Model Canvas (BMC), a equipa estruturou a distribuição do MVP através de cinco canais estratégicos:
**A. Canais Digitais e Conveniência (B2C/Varejo)**

Marketplace Industrial: Este canal funcionará como um ambiente virtual e digital contínuo, focado na conveniência para pequenos produtores e clientes de varejo. Através de plataformas de e-commerce especializadas, o cliente poderá adquirir os Kits de Upgrade de forma direta e autónoma.
Demonstrações Piloto e Webinars: Utilização de conteúdos digitais para apresentar a "ciência da medição" e a facilidade de montagem do hardware modular, reduzindo a barreira de entrada para quem ainda utiliza processos manuais.
**B. Canais de Relacionamento e Parcerias (B2B)**

Feiras e Eventos Técnicos: Participação em eventos físicos e temporários focados em networking e experiência de marca. Estes espaços são vitais para o mercado B2B (Empresa para Empresa), permitindo que diretores e gerentes de produção interajam com o hardware em tempo real.
Parcerias com Integradores de Sistemas: Este canal foca-se na escala industrial. Através de parcerias com empresas de automação já estabelecidas, o nosso MVP pode ser integrado como um módulo complementar em linhas de produção complexas, aproveitando a infraestrutura de vendas e suporte desses parceiros.
Incubadoras e Ecossistema PUC-SP: Utilização do ambiente académico e de inovação para validar o produto junto de parceiros tecnológicos e outros investigadores, garantindo que o sistema acompanhe a evolução da Indústria 4.0.
**C. Suporte e Pós-Venda**

O relacionamento não termina na entrega do hardware. Conforme estabelecido no modelo de receitas, o canal de suporte técnico mensal garante a retenção do cliente e a atualização contínua dos algoritmos de IA, transformando o canal de comunicação num ativo de fidelização.
