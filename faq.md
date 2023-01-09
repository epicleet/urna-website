---
layout: page
title: Perguntas frequentes
permalink: /faq/
---

Esta página responde perguntas frequentes sobre possíveis formas de melhorar o nosso sistema eleitoral.

## O que é o voto impresso? Para que ele serve?

Hoje, a urna brasileira só registra os votos em memória eletrônica. Isso gera vários problemas: essas memórias podem ser regravadas, o eleitor não enxerga o que é escrito nelas e, mesmo se enxergasse, seria necessário conhecimento técnico para entender.

O voto impresso é uma proposta de, além de usar a memória eletrônica, registrar os votos também em papel. Não é necessário conhecimento técnico para ler um número impresso em um papel. Por isso, essa forma de registro permite que todos os eleitores, mesmo pessoas leigas em tecnologia, possam participar da auditoria do processo eleitoral.

## Voto impresso é uma falha de segurança no processo eleitoral? Ele viola o sigilo do voto?

**Não**. Foi muito propagada a mentira de que o voto impresso seria um comprovante levado para casa pelo eleitor. Na verdade, o eleitor jamais toca no voto impresso, muito menos conseguiria levá-lo para fora da seção eleitoral.

Uma vez digitado o número do candidato, a máquina imprime e mostra o voto para o eleitor dentro de uma janela hermeticamente fechada. Após confirmar que o papel realmente contém o seu voto, o eleitor aperta a tecla CONFIRMA, fazendo com que a máquina corte o papel e deposite-o em uma urna. Se houver algum problema, o eleitor pode apertar a tecla CORRIGE, fazendo com que a máquina imprima uma marca no papel indicando que ele é inválido antes de cortá-lo.

Se a impressão apresentar divergências com relação ao seu voto, o eleitor pode demonstrá-las para o mesário sem prejudicar seu sigilo, justamente pela possibilidade de usar a tecla CORRIGE.

Note que esse procedimento não é fruto de especulação nossa. O próprio TSE se preocupou com essas questões e [publicou um artigo](https://sbseg2017.redes.unb.br/wp-content/uploads/2017/04/20171109_ANAIS_SBSEG_2017_FINAL_E-BOOK.pdf#page=692) detalhando o funcionamento do modelo de voto impresso a ser adotado no Brasil.

## Mas se a impressora der problema, o voto do eleitor pode ficar exposto ao mesário. Esse é um motivo para não ter voto impresso?

**Não**. Da mesma forma que a impressora pode falhar, a urna também pode. Quem nunca presenciou o seu computador travando? Esse risco também existe utilizando uma urna com registro 100% eletrônico.

Note, também, que tanto na urna com registro 100% eletrônico como na urna com voto impresso, existe a tecla CORRIGE. A informação que ficaria congelada na urna durante um travamento não necessariamente corresponde à decisão final do eleitor.

## O voto impresso faz voltar todos os problemas de fraude que existiam com as cédulas de papel?

**Não**. O voto impresso não é uma cédula tradicional, mas sim uma nova forma de registro digital. A diferença é que ele é impresso em papel em vez de ser gravado somente em memória eletrônica, e por isso pode ser observado pelo eleitor a olho nu. Como ele é um registro digital, ele pode e deve contar com mecanismos digitais (tais como assinaturas) para evitar fraudes não especializadas, como as que eram comuns antes da introdução da Urna Eletrônica no Brasil.

Já em sua forma atual, o modelo de voto impresso [prototipado pelo TSE](https://sbseg2017.redes.unb.br/wp-content/uploads/2017/04/20171109_ANAIS_SBSEG_2017_FINAL_E-BOOK.pdf#page=692) torna detectáveis alguns tipos de fraude não especializada, como trazer de fora da seção papéis prontos com a numeração de algum candidato. Com pequenas melhorias, como a introdução de um componente não determinístico na assinatura digital, ele tornaria também detectável a fraude de substituir, acrescentar ou subtrair papéis de dentro da urna após o término da seção.

## É necessário contar todos os votos manualmente?

**Não**. A contagem pode e deve ser auxiliada por *scanners* ou equipamentos similares. O trabalho de um *scanner* pode ser facilmente observado por leigos para aferir que ele está funcionando corretamente, bem como pode ser gravado em vídeo. Por isso, é bastante claro que o auxílio de tecnologia **não prejudica** a compreensão do processo por leigos.

Também não é necessário recontar todos os votos do registro físico. A imensa maioria dos pesquisadores defende o uso de uma técnica chamada [RLA](https://doi.org/10.1109/MSP.2012.56), em que se realiza um cálculo estatístico para determinar quantos votos precisam ser recontados para comprovar a contagem eletrônica inicial com uma margem de erro segura. Um [artigo recente](https://cacm.acm.org/magazines/2021/6/252836-the-risks-of-election-believability-or-lack-thereof/fulltext) criticou o uso de RLA por que, apesar de seguro, ele pode ser difícil de entender para eleitores sem conhecimento de matemática. No entanto, permanece o consenso da maioria dos pesquisadores que o RLA é uma abordagem melhor que uma recontagem de todos os votos. Uma das grandes vantagens do RLA é que ele não faz saltar aos olhos pequenas divergências entre a contagem inicial e a contagem verificada, por exemplo a subtração de um ou dois votos do registro físico que nem chegariam a alterar o resultado final. Desta forma, o RLA evita atritos desnecessários entre cidadãos e autoridades eleitorais nas auditorias pós-eleição.

## Se o próprio TSE projetou um modelo de voto impresso, por que eles são contra a adoção da medida?

Não conhecemos as políticas internas do TSE, então qualquer hipótese que levantássemos seria pura especulação. O fato é que, como a medida foi suspensa pelo Judiciário, o TSE vê como papel institucional defender incondicionalmente o sistema atual. Realmente, é importante que os eleitores confiem no processo eleitoral para que uma democracia funcione e, de fato, **o processo atual (2022) não é escancarado o suficiente para nos preocuparmos com uma suposta fraude tecnológica iminente**. Mas vemos como uma inversão de valores confiar cegamente no sistema a ponto de impedir a evolução, no longo prazo, para soluções mais seguras e transparentes.

## A Urna Eletrônica armazena o Registro Digital do Voto (RDV). Ele já não permite recontagem de votos?

**Não**. O RDV é um registro em memória eletrônica gerado pela mesma urna e pelo mesmo software que realiza a contagem dos votos. Isso significa que, caso a urna seja comprometida, é fácil alterar ambos os registros de forma que concordem entre si.

Imagine um cofre em que uma grande soma de dinheiro é guardada. Para saber se o conteúdo foi alterado, basta contar o dinheiro e comparar com o saldo armazenado em um papel na sua carteira. Se os valores não forem iguais, significa que o saldo ou o conteúdo do cofre foram alterados.

Continuando no mesmo cenário, a Urna Eletrônica seria um cofre em que o saldo para conferência e o dinheiro são armazenados no mesmo local. Caso alguém consiga abrir o cofre, seria possível retirar o dinheiro e, simultaneamente, alterar o saldo escrito no papel para refletir o novo valor. Desta forma, seria difícil detectar que o cofre foi comprometido.

## A Urna Eletrônica é desconectada da internet (como uma torradeira elétrica). Ainda assim é possível hackeá-la?

**Sim**. A Urna Eletrônica é um dispositivo digital similar a um computador comum. Isso significa que é possível, sim, alterar o seu comportamento de forma não prevista. Este é o motivo pelo qual a proteção de um computador depende também de sua segurança física. Datacenters no mundo inteiro investem grandes somas em dinheiro para garantir que o acesso físico aos servidores só seja realizado por poucos profissionais de confiança.

O Teste Público de Segurança de 2017 [mostrou](https://doi.org/10.13140/RG.2.2.28590.82246/1) a possibilidade de um ataque às urnas sem necessidade de acesso à internet. Nesse ataque, o cartão de memória utilizado para instalação da urna foi infectado com um arquivo modificado que alterava o comportamento do software de votação. Nesse caso, o cartão de memória foi utilizado como vetor do ataque, e não a internet. Como cada cartão instala até 50 urnas, o ataque é escalável para impacto não-trivial em uma eleição.

Outros tipos de ataque também são possíveis a partir do acesso físico à urna eletrônica. Por exemplo, as urnas possuem portas USB, que podem potencialmente ser atacadas. Se consideramos que as urnas podem ter sido abertas e sabotadas antes da lacração, ou que os lacres possam ser falsificados, a superfície de ataque amplia-se ainda mais.

## O código da urna é inspecionado por pessoas qualificadas. Isso é suficiente para identificar falhas de segurança?

**Não**. Infelizmente não é possível identificar todos os bugs e falhas de segurança apenas com uma inspeção do código. Se isso fosse verdade, empresas no mundo inteiro não gastariam grandes somas em dinheiro testando seus softwares. Bastaria fazer uma auditoria e teríamos a garantia de um software seguro.

Esse desafio é agravado pela grande complexidade do software atualmente utilizado na urna. Como construímos programas com cada vez mais dependências externas, é impossível mapear e entender todo o comportamento do sistema. O código da urna eletrônica, por exemplo, contém milhões de linhas de código, o que torna *impossível* declarar o código livre de erros apenas com uma inspeção / auditoria.

Acreditar que basta analisar alguns pontos do sistema também é uma falácia. A falha de segurança a ser explorada pode estar localizada em um ponto distante das áreas críticas ou pode ser resultado de uma sequência complexa de ações.

## Todo mundo confia em bancos digitais. Por que não confiar na urna com registros 100% eletrônicos?

As pessoas utilizam o banco com confiança justamente por terem acesso a mecanismos de auditoria complementares. Por exemplo, quando pagamos um boleto no caixa eletrônico, ele imprime um comprovante. Ou, quando o pagamos pelo aplicativo do banco, podemos salvar o comprovante em um arquivo PDF. Caso o mesmo boleto seja cobrado posteriormente, o comprovante permite provar que a dívida não existe.

Você confiaria num banco em que, depois de pagar um boleto, o dinheiro simplesmente desaparecesse do seu saldo, sem que o destino daquele dinheiro ficasse ao menos registrado no seu extrato? O sistema eleitoral utilizado hoje no Brasil tem exatamente esse problema.

É bem verdade que, por ser necessário manter o sigilo do voto, a situação é um pouco diferente. Por exemplo, a urna não pode imprimir um comprovante para você levar para casa. Além disso, você não pode entrar com seu usuário e senha no site do TSE e baixar um PDF dizendo em qual candidato você votou.

A solução é gerar um comprovante anônimo, que não fique com o eleitor, mas que permaneça à disposição em uma urna para conferência dos valores registrados na memória eletrônica. É esse instrumento de auditoria que é chamado de voto impresso.

## O projeto Você Fiscal resolve o problema?

**Não**. O projeto [Você Fiscal](http://www.vocefiscal.org), atualmente inativo, propunha apenas fiscalizar a etapa de transmissão do total de votos de cada seção para a contagem final. Essa fiscalização é necessária, mas não é suficiente para garantir a integridade das eleições. Como hoje não é possível auditar votos individuais, o total de votos de cada seção pode estar contabilizado incorretamente antes mesmo da transmissão.

## Se o Você Fiscal é necessário (apesar de não ser suficiente), por que vocês não continuam mantendo o projeto?

O projeto Você Fiscal motivou o TSE a incluir códigos QR nos boletins de urna, que facilitam a leitura dos totais de cada seção, e evitam um árduo trabalho manual para aquisição de dados que era necessário com o Você Fiscal. Com isso, em 2016 uma outra equipe criou o [Apura Fácil](http://cartadenoticias.com.br/2016/09/app-desenvolvido-em-ipatinga-permite-apuracao-paralela-das-eleicoes/), um aplicativo capaz de ler esses códigos. Em 2018, uma equipe do [CMind](https://web.archive.org/web/20220121080549/http://pt.wikipedia.org/wiki/Comit%C3%AA_Multidisciplinar_Independente) desenvolveu um aplicativo similar para [Totalização Paralela das Eleições 2018](https://play.google.com/store/apps/details?id=com.marcocarvalho.Totalizador_2018). Assim, a equipe original do Você Fiscal considerou seus objetivos cumpridos e deixou que outras pessoas continuassem esse trabalho. O grande desafio para qualquer entidade disposta a realizar uma fiscalização nesses moldes é projetar uma técnica de amostragem que produza resultados com significância estatística para uma base de dados voluntária, problema ainda em aberto.

## Blockchain nas urnas eletrônicas resolve o problema?

**Não**. Blockchain serve para garantir que, uma vez registrada uma informação, ela nunca mais seja alterada. Mas se você não souber que a informação está correta no momento em que ela for registrada, de nada adianta garantir que ela não será alterada posteriormente.

Quando você faz uma compra com bitcoins no seu computador, a blockchain garante que uma vez que você transferiu aquelas moedas para a loja, você nunca mais poderá alegar que não transferiu, e portanto não poderá gastar as mesmas moedas para fazer outra transação. O propósito da blockchain é esse. É para isso que ela foi criada, e não para te proteger de criminosos que queiram roubar seu dinheiro. Se o seu computador estiver infectado com malware, ele pode muito bem registrar na blockchain uma transação incorreta, que transfira o dinheiro para um criminoso em vez de transferir para a loja.

Com votação, a situação se agrava, pois a transação na blockchain precisa ser sigilosa. Você inclui seu voto em um registro imutável mas, para proteger o sigilo, você depois não deve ser capaz de verificar o destinatário. Como [verificar](https://freedom-to-tinker.com/2017/09/12/blockchains-and-voting/) que seu voto foi destinado ao candidato correto? Ao contrário do roubo de bitcoins, que você acabaria percebendo, aqui você jamais saberia que seu voto foi desviado.

Imagine agora o problema inverso: de alguma maneira, você conseguiu inserir o registro corretamente e de forma sigilosa mas, depois de algum tempo, alguém descobre como quebrar o método que foi utilizado para garantir esse sigilo. Como a informação está registrada para sempre na blockchain, agora você nunca mais pode alegar que não votou naquele candidato.

Um tratamento muito mais detalhado sobre as limitações de blockchain para realizar eleições via Internet pode ser encontrado [aqui](https://educatedguesswork.org/posts/voting-blockchain/).

## Mas já não há países utilizando blockchain em eleições?

*Não exatamente*. Em Serra Leoa, houve uma [iniciativa independente](http://en.rfi.fr/africa/20180315-sierra-leone-tests-blockchain-technology-tallying-election-results) similar ao Você Fiscal e ao Apura Fácil, que coletava os totais de seções eleitorais para conferir a contagem final. Uma das diferenças com relação às iniciativas brasileiras é que eles usavam uma blockchain como uma base de dados pública e imutável para armazenar esses dados. Nós concordamos que esse é um bom uso para a tecnologia de blockchain, afinal os totais de seções eleitorais são dados públicos.

Outra diferença é que Serra Leoa não utiliza votação eletrônica. Os totais de seções eleitorais foram contabilizados a partir da apuração de cédulas tradicionais em papel.

## O uso de uma memória eletrônica que só pode ser gravada uma vez substitui o registro em papel?

**Não**. O registro em papel dá transparência ao processo eleitoral pois ele pode ser observado a olho nu pelo eleitor.

Quando as pessoas sugerem armazenar o voto em uma memória eletrônica [que não pode ser regravada](https://en.wikipedia.org/wiki/Write_once_read_many), elas estão pensando apenas no fato de que o papel torna evidente rasuras que aconteçam após ele ser impresso. Mas essa não é a única propriedade do papel. Tão importante quanto isso é permitir que o eleitor veja que o voto que está sendo registrado é o que ele deseja. As pessoas não conseguem observar elétrons correndo em fios, mas a maioria das pessoas consegue ler os números dos candidatos escritos em um papel.

Recentemente, o GRITA! propôs o [VAIDE](https://archive.is/xpyKr), um dispositivo USB externo à urna que receberia os votos e os guardaria em uma memória própria. O VAIDE não disponibilizaria à urna um comando para regravar votos, apenas um comando para acrescentar novos votos, dessa forma ele comportaria-se como uma dessas [memórias não regraváveis](https://en.wikipedia.org/wiki/Write_once_read_many). Primeiramente, é importante ressaltar que não se trata de uma ideia nova. Em 2001, Guimarães *et al.* já haviam proposto o [SELA](http://www2.ic.uff.br/~michael/sela.pdf) que, além de impedir a regravação dos votos, era mais completo que o VAIDE por apresentar ao eleitor uma cópia do número digitado na urna, comprovando que a urna transmitiu o candidato correto ao dispositivo externo.

<img src="{{ "/assets/images/sela.jpg" | prepend: site.baseurl }}" alt="Protótipo do SELA">

Apesar de ter parecido uma boa ideia há mais de 20 anos atrás, o [problema do SELA](https://youtu.be/wGS2nGDjHx0?t=575) é que ainda seria necessário confiar que o software do dispositivo externo não possui erros de programação nem vulnerabilidades, pois não é possível observar diretamente a olho nu os dados que estão sendo gravados em memória. Já o VAIDE, por mais que seja uma proposta mais recente, apresenta ainda mais problemas que o SELA, pois não é possível saber ao menos se o dispositivo externo recebeu pela USB o mesmo voto apresentado na tela da urna. Por exemplo, o ataque que demonstramos no TPS 2017, sem precisar de nenhuma modificação, passaria totalmente despercebido em uma urna com VAIDE.

## O uso de um sistema verificável fim a fim resolve o problema?

Recentemente, o TSE [anunciou](https://www.tse.jus.br/comunicacao/noticias/2022/Maio/equipes-do-tse-e-da-usp-trabalham-na-inovacao-do-sistema-eletronico-de-votacao) que está trabalhando na implementação do método fim a fim em parceria com pesquisadores da academia. Trata-se de uma iniciativa louvável que, se bem implementada, tem grande potencial de melhorar o nosso processo eleitoral e torná-lo finalmente [independente de software](https://people.csail.mit.edu/rivest/RivestWack-OnTheNotionOfSoftwareIndependenceInVotingSystems.pdf). A verificação fim a fim pode ou não ser acoplada a um registro físico. Em países que adotam votações pela internet, como a Estônia, não é utilizado registro físico pois, como a votação não é presencial, isso não faria sentido. Já em votações presenciais, a recomendação de pesquisadores é que, além de se emitir um código de rastreamento para verificação fim a fim, seja gerado um registro físico às claras, para tornar o processo eleitoral mais compreensível para pessoas leigas, que não entendem a matemática da verificação fim a fim. Essa preocupação é levada em conta pelos protótipos de sistemas verificáveis fim a fim destinados ao uso em votações presenciais existentes na literatura, como o [Wombat](https://wombat.factcenter.org).
