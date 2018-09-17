---
layout: page
title: Perguntas frequentes
permalink: /faq/
---

## O que é o voto impresso? Para que ele serve?

Hoje, a urna brasileira só registra os votos em memória eletrônica. Isso gera vários problemas: essas memórias podem ser regravadas, o eleitor não enxerga o que é escrito nelas e, mesmo se enxergasse, seria necessário conhecimento técnico para entender.

O voto impresso é uma proposta de, além de usar a memória eletrônica, escrever os votos também em papel. Não é necessário conhecimento técnico para ler um número impresso em um papel. Por isso, essa forma de registro permite que todos os eleitores, mesmo pessoas leigas em tecnologia, possam participar da auditoria do processo eleitoral.

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

## Se o próprio TSE projetou um modelo de voto impresso, por que eles são contra a adoção da medida?

Não conhecemos as políticas internas do TSE, então qualquer hipótese que levantássemos seria pura especulação. O fato é que, como a medida foi suspensa pelo Judiciário, o TSE vê como papel institucional defender incondicionalmente o sistema atual. Realmente, é importante que os eleitores confiem no processo eleitoral para que uma democracia funcione. Mas vemos como uma inversão de valores confiar cegamente no sistema a ponto de impedir a evolução para soluções mais seguras.

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

O projeto Você Fiscal motivou o TSE a incluir códigos QR nos boletins de urna, que facilitam a leitura dos totais de cada seção, e evitam um árduo trabalho manual para aquisição de dados que era necessário com o Você Fiscal. Com isso, uma outra equipe criou o [Apura Fácil](http://cartadenoticias.com.br/2016/09/app-desenvolvido-em-ipatinga-permite-apuracao-paralela-das-eleicoes/), um aplicativo capaz de ler esses códigos. Este ano, uma equipe do CMind desenvolveu um aplicativo similar para [Totalização Paralela das Eleições 2018](https://play.google.com/store/apps/details?id=com.marcocarvalho.Totalizador_2018). Assim, a equipe original do Você Fiscal considerou seus objetivos cumpridos e deixou que outras pessoas continuassem esse trabalho. O grande desafio para qualquer entidade disposta a realizar uma fiscalização nesses moldes é projetar uma técnica de amostragem que produza resultados com significância estatística para uma base de dados voluntária, problema ainda em aberto.

## Blockchain nas urnas eletrônicas resolve o problema?

**Não**. Blockchain serve para garantir que, uma vez registrada uma informação, ela nunca mais seja alterada. Mas se você não souber que a informação está correta no momento em que ela for registrada, de nada adianta garantir que ela não será alterada posteriormente.

Quando você faz uma compra com bitcoins no seu computador, a blockchain garante que uma vez que você transferiu aquelas moedas para a loja, você nunca mais poderá alegar que não transferiu, e portanto não poderá gastar as mesmas moedas para fazer outra transação. O propósito da blockchain é esse. É para isso que ela foi criada, e não para te proteger de criminosos que queiram roubar seu dinheiro. Se o seu computador estiver infectado com malware, ele pode muito bem registrar na blockchain uma transação incorreta, que transfira o dinheiro para um criminoso em vez de transferir para a loja.

Com votação, a situação se agrava, pois a transação na blockchain precisa ser sigilosa. Você inclui seu voto em um registro imutável mas, para proteger o sigilo, você depois não deve ser capaz de verificar o destinatário. Como [verificar](https://freedom-to-tinker.com/2017/09/12/blockchains-and-voting/) que seu voto foi destinado ao candidato correto? Ao contrário do roubo de bitcoins, que você acabaria percebendo, aqui você jamais saberia que seu voto foi desviado.

Imagine agora o problema inverso: de alguma maneira, você conseguiu inserir o registro corretamente e de forma sigilosa mas, depois de algum tempo, alguém descobre como quebrar o método que foi utilizado para garantir esse sigilo. Como a informação está registrada para sempre na blockchain, agora você nunca mais pode alegar que não votou naquele candidato.

## Mas já não há países utilizando blockchain em eleições?

*Não exatamente*. Em Serra Leoa, houve uma [iniciativa independente](http://en.rfi.fr/africa/20180315-sierra-leone-tests-blockchain-technology-tallying-election-results) similar ao Você Fiscal e ao Apura Fácil, que coletava os totais de seções eleitorais para conferir a contagem final. Uma das diferenças com relação às iniciativas brasileiras é que eles usavam uma blockchain como uma base de dados pública e imutável para armazenar esses dados. Nós concordamos que esse é um bom uso para a tecnologia de blockchain, afinal os totais de seções eleitorais são dados públicos.

Outra diferença é que Serra Leoa não utiliza votação eletrônica. Os totais de seções eleitorais foram contabilizados a partir da apuração de cédulas tradicionais em papel.
