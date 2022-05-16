# ENGENHARIA DE SOFTWARE

## Crise de Software - problemas

### 1. As estimativas de prazo e de custo frequentemente são imprecisas

- "Não dedicamos **tempo para coletar dados** sobre o processo de desenvolvimento de software."

- "Sem **nenhuma indicação sólida de produtividade**, não podemos avaliar com precisão a eficácia de novas _ferramentas, métodos ou padrões_" - ex: análise de ponto de função.

- Resulta em definições "a olho".

### 2. Insatisfação do cliente com o sistema concluído

- "Os projetos de desenvolvimento de software normalmente são efetuados apenas com um **vago indício** das exigências do cliente". - _comunicação fraca com o cliente_

### 3. A qualidade de software às vezes é menos que adequada

- Só recentemente começam a surgir conceitos quantitativos sólidos de garantia de qualidade de software.

- Ex: Microsoft - _avaliação de níveis de erros_ (versões: Alfa, Beta, Candidata, Final ou Comercial).

### 4. O software existente é muito difícil de manter

- A tarefa de **manutenção** devora o orçamento destinado ao software.

- A facilidade de manutenção não foi enfatizada como um critério importante.

## Causas dos problemas associados à crise de software

### 1.  Próprio caráter do software

- O software é um elemento de sistema lógico e não físico. Consequentemente o sucesso é medido pela qualidade de uma **única entidade** e não pela qualidade de muitas entidades manufaturadas.

- **O software não se desgasta, mas se deteriora**.

- Hardware: a qualidade é medida no final.

- Software: a qualidade deve ser medida por partes.

### 2. Falhas das pessoas responsáveis pelo desenvolvimento de software

- Gerentes sem **nenhuma experiência** em software.

- Profissionais da área de software têm **pouco treinamento formal** em novas técnicas para o desenvolvimento de software.

- Resistência a mudanças.

### 3. Mitos do Software

- Propagaram desinformação e confusão.

- Administrativos
- Cliente
- Profissional

#### (ADMINISTRATIVOS)

#### Mito 1

- Já temos um manual repleto de padrões e procedimentos para a construção de software.

- Isso não oferecerá ao meu pessoal tudo o que eles precisam saber?

#### Realidade 1

- Será que o manual é usado?

- Os profissionais sabem que ele existe?

- Ele reflete a prática moderna de desenvolvimento de software?

- Ele é completo?

#### Mito 2

- Meu pessoal tem **ferramentas** de desenvolvimento de software de **última geração**; afinal lhes compramos os mais novos computadores.

#### Realidade 2

- É preciso muito mais do que os mais recentes computadores para se fazer um desenvolvimento de software de alta qualidade. Ex: ferramentas CASE

#### Mito 3

- Se nós estamos atrasados nos prazos, podemos adicionar mais programadores e tirar o atraso.

#### Realidade 3

- O desenvolvimento de software **não é um processo mecânico** igual à manufatura. Acrescentar pessoas em um projeto torna o ainda **mais atrasado**.

- Pessoas podem ser acrescentadas, mas somente de uma **forma planejada**.

### (CLIENTE)

#### Mito 1

- Uma declaração geral dos objetivos é suficiente para se começar a escrever programas - podemos preencher os detalhes mais tarde.

#### Realidade 1

- Uma **definição inicial ruim** é a principal causa de fracassos dos esforços de desenvolvimento de software.

- É fundamental uma **descrição formal** e detalhada do domínio da informação, função, desempenho, interfaces, restrições de projeto e critérios de validação.

- Definição dos requisitos funcionais.

#### Mito 2

- Os requisitos de projeto modificam-se continuamente, mas as mudanças podem ser facilmente acomodadas, porque o sofware é flexível.

#### Realidade 2

- Uma **mudança**, quando solicitada **tardiamente** num projeto, pode ser maior do que a ordem de magnitude mais dispendiosa da mesma mudança solicitada nas fases iniciais.

- **MAGNITUDE DAS MUDANÇAS**

| FASES          | CUSTO DE MANUTENÇÃO |
| :---           | :----:              |
| Definição      | 1X                  |
| Desenvolvimento| 1.5 - 6X            |
| Manutenção     | 60 - 100X           |

### (PROFISSIONAL)

#### Mito 1

- Assim que escrevemos o programa e o colocarmos em funcionamento nosso trabalho estará completo.

#### Realidade 1

- Os dados da indústria indicam que entre 50 e 70% de todo esforço gasto num programa serão despendidos depois que ele for entregue pela primeira vez ao cliente.

#### Mito 2

- Enquanto não tiver o programa "funcionando", eu não terei realmente nenhuma maneira de avaliar sua qualidade.

#### Realidade 2

- Um programa funcionando é somente uma parte de uma Configuração de Software que inclui todos os itens de informação produzidos durante a construção e manutenção do software.

## Engenharia de Software: What the Hell is this?

- A engenharia de Software é uma área **MUITO NOVA!**

- Engenharia de Software: "A aplicação de uma abordagem sistemática, disciplinada e possível de ser medida para o desenvolvimento, operação e manutenção do software". (IEEE).

- Engenharia de Software: "O desenvolvimento e a aplicação da ciência, matemática, técnicas, métodos, metodologias e ferramentas para o desenvolvimento e manutenção econômica de software de qualidade previsível e controlável, operando de modo econômico em máquinas e ambientes reais".

# Ciclo de Vida

- A Engenharia de Software se preocupa com o software como **produto**. Como todo produto industrial, o software tem um ciclo de vida.

- Ele é concebido a partir da **percepção de uma necessidade**.

- É desenvolvido, transformando-se em um conjunto de itens entregue a um cliente.

- Entra em operação, sendo usado dentro de algum processo de negócio, e sujeito a atividades de manutenção, quando necessário.

- É retirado de operação, ao final de sua vida útil.

## Ciclo de Vida - Conceitos

- É considerado o **intervalo de tempo** decorrido desde o momento da **concepção** de um software até sua **obsolescência**.

- É identificado como um **conjunto de fases** ou **etapas** que representam uma evolução desde o nascimento da necessidade de criação de um software até a sua descontinuidade ou morte.

## Objetivo

- Sugerir uma **ordenação das atividades** existentes no **desenvolvimento e manutenção de software**.

- Agregar qualidade: Boa qualidade no processo de desenvolvimento e no produto final de um software está relacionado com a escolha do modelo de ciclo de vida a ser adotado.

## Elementos das Fases

- O que identifica uma etapa ou fase do ciclo de vida não é o seu nome, e sim a caracterização dos seguintes elementos:

![Fase de desenvolvimento](/img/Fases%20de%20desenvolvimento.PNG)

## O Modelo "Codifica-Remenda"

- É o ciclo de vida mais caótico.

- Partindo apenas de uma especificação, os desenvoledores começam imediatamente a codificar, remendando à medida que os erros vão sendo descobertos.

- Esse modelo não exige nenhuma sofisticação técnica ou gerencial.

- É um modelo de alto risco, impossível de gerir e que não permite assumir compromissos confiáveis.

![Codifica-Remenda](/img/Codifica%20Remenda.PNG)

## O Modelo "Cascata"

- Encoraja a especificação do sistema de início.

- Capacita o gerente a caminhar progressivamente e descobrir possíveis erros.

- Os produtos das fases anteriores são utilizados como base para as outras fases.

- Demanda a produção de uma série de documentos no decorrer do processo.

- Não indicado para sistemas co mgrande interação com o usuário.

- O modelo cascata é de baixa visibilidade para o cliente, que só recebe o resultado final do projeto.

### Análise de requisitos de software

- Coleta dos requisitos em nível do sistema.

- Identificação dos serviços e metas a serem atingidos.

- Identificada a qualidade desejada para o sistema em termos de funcionalidade, desempenho, facilidade de uso, portabilidade...

- Preocupa-se em identificar **quais** requisitos sem se preocupar **como** eles serão implementados.

### Projeto

- Representação das funções do sistema em uma forma que possa ser transformada em um ou mais programas executáveis.

- Defini-se: estrutura de dados, arquitetura de software, detalhes procedimentais e caracterização de interface.

### Codificação

- O projeto deve ser traduzido numa forma legível por máquina. Se o projeto for executado detalhadamente, codificação pode ser executada mecanicamente.

### Teste

- Concentra-se nos aspectos **lógicos internos** do software (todas as instruções testadas), e nos **funcionais externos** (testes para descoberta de erros).

- Pode incluir inspeção de código, para checagem de padrões de codificação, estilo de programação, verificação de desempenho.

- Testes de unidades (módulos) e de integração.

### Manutenção

- O software sofrerá mudanças depois que for entregue ao cliente. Ocorrerão mudanças porque erros foram descobertos, porque o software deve ser adaptado a fim de acomodar mudanças em seu ambiente externo, ou porque o cliente exige acréscimos funcionis ou de desempenho.

## O Modelo "Prototipação Rápida Descartável"

- Fornece rapidamente uma versão para ser utilizada e avaliada pelo usuário.

- Não a necessidade de se satisfazer todos os requisitos do produto final desde o início.

- Facilita o desenvolvimento de produtos onde não se conhece totalmente o problema.

- O usuário não consegue especificar de uma forma clara os requisitos do sistema.

- Pode ser usado quando o sistema possuir muito interação com o usuário e se deseja avaliar a interface.

## O Modelo "Prototipação"

- O desenvolvedor pode estar incerto sobre a eficiência de um algoritmo, adaptação de um sistema operacional ou sobre a forma da interação homem-máquina.

- O protótipo se concentra em fazer experimentos com os requisitos do usuário que não estão bem entendidos e envolve projeto, implementação e teste, mas não de maneira formal ou completa.

![Prototipação](/img/Prototipacao.PNG)

## O Modelo "Iterativo"

### Definição

- É uma estratégia de planejamento de retrabalho em que o tempo de revisão e melhorias de aprtes do sistema é pré-definido.

- A saída de uma iteração é examinada para modificação, e especialmente para revisão dos objetivos das iterações sucessivas.

### Paradigma

- O sistema deve ser desenvolvido de forma incremental, sendo que cada incremento vai adicionando ao sistema novas capacidades funcionais, até a obtenção do sistema final, sendo que, a cada passo realizado, modificações podem ser introduzidas.

- vantagem destta abordagem é a facilidade em testar o sistemaq, uma vez que a realização de testes em cada nível de desenvolvimento é, sem dúvida, mais fácil do que testar o sistema final.

- Além disso, como na prototipação, a obetenção de um sistema, mesmo incompleto num dado nível, pode oferecer ao cliente interessantes informações que sirvam de subsídio para a melhor definição de futuros requisitos do sistema.

![Iteração](/img/Iteracao.PNG)

- O âmbito do sistema não é alterado, mas o seu detalhe vai aumentando em iterações sucessivas.

![Iteração](/img/Iteracao2.PNG)

## O Modelo "Incremental"

- Os requisitos são conhecidos

- Não se quer implementar todo o sistema de uma vez (sistema dividido em subsistemas ou módulos).

- Escolhem-se prioridades de implementação. Fatores como tempo e disponibilidade de recursos e pessoal podem influenciar nas prioridades.

- Deseja ter rapidamente uma versão operacional mesmo que não tenha todas as funções.

- A cada ciclo uma nova versão operacional do sistema será produzida.

- É uma estratégia de planejamento estagiado em que várias partes do sistema são desenvolvidas em paralelo, e integradas quando completas.

- Desenvolver todo o sistema com uma integração única.

- A noção de processo incremental corresponde à ideia de "aumentar **pouco a pouco** o âmbito do sistema.

![Incremental](/img/Incremental.PNG)

- Como as funções priotitárias são entregues primeiro e os incrementos são integrados a elas, é inevitável que as funções de sistemas mais importantes passem pela maior parte dos testes. Isso significa que é menos provável que os clientes encontrem falhas de software na parte mais importante do sistema.

## O Modelo "Espiral"

- **Também conhecido como Paradigma de Boehm**.

- Engolba as melhores características do ciclo de vida clássico e da prototipação, adicionando um novo elemento - a **análise de risco** - que não existe nos outros paradigmas.

- **Riscos são circunstâncias adversas que podem atrapalhar o processo de desenvolvimento e a qualidade do produto a ser desenvolvido**.

- O paradigma, representado pela espiral, define quatro atividades principais representadas pelos quadrantes: **Planejamento, Análise dos Riscos, Engenharia e Avaliação do Cliente**

- Versões progressivamente mais completas do software são construídas.

- O produto e desenvolvido em uma serie de iterações.

- Cada nova iteração corresponde a uma volta na espiral.

- Isso permite construir produtos com prazos curtos, com novas características e **recursos** que são **agregados** na medida em que a experiência descobre suas necessidades.

- As atividades de manutenção são usadas para **identificar problemas**, seus registros fornecem dados para definir os **requisitos das próximas liberações**.

- O principal problema do ciclo de vida em espiral é que ele **requer gestão muito sofisticada** para ser previsível e confiável.

## O Modelo "Prototipagem Evolutiva"

- É uma variante do modelo em espiral.

- A espiral é usada não para desenvolver o produto completo, mas para **construir uma série de versões provisórias** que são chamadas de protótipos.

- Em vez de ter as atividades de **especificação, desenvolvimento e validação** em separado, todo esse trabalho é realizado concorrentemente com um rápido feedback por meio dessas atividades.

- Os protótipos cobrem cada vez mais requisitos, até que se atinja o produto desejado.

- A prototipagem evolutiva permite que os requisitos sejam definidos progressivamente, e apresenta alta flexibilidade e visibilidade para os clientes.

- Requer gestão sofisticada e o desenho deve ser de excelente qualidade, para que a estrutura do produto não se degenere ao longo dos protótipos.

## Técnicas de Quarta Geração

- Abrange um amplo conjunto de ferramentas de software que tem uma coisa em comum: cada uma delas possibilita que o desenvolvedor especifique alguma característica do software num nível elevado.

- O ambiente de desenvolvimento inclui as seguintes ferramentas: Linguagens para consulta de banco de dados, geração de relatórios, manipulação de dados, interação e definição de interfaces, geração de códigos e etc.

![técnicas de quarta geração]()

### Atividades

#### Obtenção dos Requisitos

- Cliente descreve os requisitos.

- Requisitos são traduzidos para protótipo.

#### Cliente pode estar inseguro

- Cliente pode ser incapaz de especificar as informações corretamente.

- Linguagens de 4ª geração não são suficientemente sofisticadas.

### Vantagens de Problemas

#### Proponentes

- Redução do tempo de desenvolvimento (Aumento da Produtividade).

#### Oponentes

- Ferramentas de 4ª geração não são mais fáceis de usar que as linguagens de programação.

- Código resultante é ineficiente.

- Manutenção questionável.

### Combinando Paradigmas

![Combinando Paradigmas]()

## O Modelo "RUP"

![Modelo RUP]()

### Ciclo de vida RUP

![Ciclo de vida RUP]()

- Cada fase é então subdividida em iterações:

![Iterações RUP]()

- Um conjunto de artefatos (release) é gerado a cada iteração.

#### Características do Modelo Iterativo

- O desenvolvimento iterativo produz um executável.

- Ciclos de desenvolvimento.
