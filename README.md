## Equipe: Everton, Gabriel, Lucas

## Grupo 06 - Placas-mãe

* [Fundamentos e definições](#fundamentos-e-definições)
* [Fabricantes principais](#fabricantes-principais)
* [Constituição básica](#constituição-basica)
    * Slots, chipset, gerador de clock, super I/O, controlador de teclado, ROM, bateria, soquetes de memória, etc
* [Atualização da BIOS](atualizacao-da-bios)
* [Modelos e tipos](modelos-e-tipos)

---

#Fundamentos e definições

### Introdução
Placas-mãe não são apenas o Hardware que agrupa interface e componentes, é o hardware que têm mais influência em um computador quando falamos em estabilidade e possibilidades de expansões.

No ínicio, as placas-mãe serviam simplesmente como uma interface agrupadora de componentes, uma placa de circuito sem vida própria. A medida que novas tecnologias foram surgindo, mais e mais componentes passaram a ser integrados à placa-mãe, fazendo com que as placas-mãe ganhassem uma posição de destaque no cenário de computadores.

Placas de rede, áudio, vídeo, entre outros periféricos passaram a ser integrados em placas-mãe, ou seja, interfaces onboard. Inicialmente, placas-mãe com periféricos onboard enfrentaram um certo preconceito, já que, componentes offboard possuiam melhor qualidade e durabilidada. Isso mudou a partir do momento em que os fabricantes perceberam que teriam mais lucros se investissem em componentes de qualidade, e assim, placas-mãe com "tudo onboard" virou um padrão, principalmente no mercado de computadores de baixo custo.

Com o advento de novas tecnologias e processadores, tais como a série Intel Core ix (i3, i5, i7) da 2ª geração (Sandy Bridge), as placas-mãe perderam alguns componentes onboard, como chipsets, video integrados, entre outros. Apesar disso, as placas-mãe não perderam seu brilho, e, escolher uma boa placa-mãe é uma tarefa que requer muita atenção.

---

### Definição

Uma placa-mãe é a principal placa de circuito impreso de um computador, e outros sistemas expansíveis e não expansíveis. Ela mantém muitos dos principais componentes eletrônicos do sistema, como o CPU, memórias, placas de vídeo, entre outros conectores e perífericos.

O PCB (Printed Circuit Board), ou placa de circuito impresso, é uma “chapa” que é composta por fenolite, fibra de vidro, filme de poliéster, filmes específicos à base de diversos polímeros, entre outros materiais. Possui a superfície cobertura por uma fina película de cobre, prata, ligas à base de ouro, níquel entre outros, nas quais são impresso os circuitos condutores onde serão fixados os componentes eletrônicos.
Atualmente, placas-mãe modernas possuem PCBs com várias camadas, aumentando a estabilidade e durabilidade das mesmas.

---

### História

Antes dos processadores, os computadores eram grandes Mainframes, seus componentes eram conectados por um “backplane” (grupo de conectores elétricos) atráves de fios.
Com o surgimento dos processadores, memórias e outros periféricos, isso mudou.

Durante a década de 80 e 90, com o aumento do número da função dos periféricos, o modelo de agrupamento de periféricos através de um PCB se tornou mais ecônomico.

* 1981 - IBM “Planar” Breadboard
> Foi a primeira placa-mãe usada em um PC

* 1984 - IBM Personal Computer AT
> IBM trouxe o AT (Advanced technology), foi o nascimento do formato AT, padrão em desktops de mesa

* 1986 - Nascimento da Gigabyte
> Atualmente uma das maiores empresas do ramo, formada por Yeh Pei-Cheng, em Taiwan

* 1987 - Nascimento da Elitegroup Form
> Atualmente conhecido como ECS

* 1989 - Asus é fundada
> Nasce uma pequena companhia Taiwanesa, formada por ex empregados da Acer. A ideia do nome veio da mitologia grega, o ser mitológico Pegasus. Atualmente é a maior empresa do ramo de placas-mãe.

* 1993 - Intel PAGA (Plastic pin grid array)
> Sistema de auxílio para circuitos integrados

* 1995 - Intel lança o novo formato ATX
> A maior mudança no ramo de placas-mãe desde o formato AT em 1984. Esse novo formato resolveu muitos problemas de espaço e dimensões do layout das placas-mãe


* 1997 - Intel começa a fabricar placas-mãe
> Intel cria sua própria divisão de fabricação de placas-mãe

* 1998 - Novo formato, Micro ATX
> Este novo formato foi o primeiro a regredir em questões de dimensões, perfeito para gabinetes menores

* 2001 - Novo formato, Mini ITX by VIA
> Os mesmos recursos das placas ATX, porém com dimensões reduzidas

* 2005 - Intel Technology Extended
> Projeto da Intel que visa aumentar a eficiência enérgetica dos componentes

* 2007 - ASUS
> Depois de uma série de sucesso financeiro, a ASUS se torna a maior fabricante de placas-mãe

* 2009 - Novo formato, Mobile ITX by VIA
> O menor formato de placa-mãe atualmente, apenas 60mm x 60mm

---

### Formatos (Form factors)

|Formato| Dimensões|
|-------|:--------:|
|AT | 350mm x 305mm |
|Baby-AT | 330mm x 216mm |
|BTX | 325mm x 266mm |
|ATX | 305mm x 244mm |
|EATX | 305mm x 330mm |
|LPX | 330mm x 229mm |
|mBTX | 264mm x 267mm |
|NLX | 254mm x 228mm |
|Ultra ATX | 244mm x 367mm |
|mATX | 244mm x 244mm |
|DTX | 244mm x 203mm |
|FlexATX| 229mm x 19mm |
|Mini-DTX | 203mm x 170mm |
|EBX | 203mm x 146mm |
|Mini-ITX | 170mm x 170mm |
|EPIC | 165mm x 165mm |
|Mini ATX | 150mm x 150mm |
|ESM | 149mm x 71mm |
|Nano-ITX | 120mm x 120mm |
|COM Express | 125mm x 95mm |
|ESMexpress | 125mm x 95mm |
|ETX/XTX | 114mm x 95mm |
|Pico-ITX | 100mm x 72mm |
|PC/104 | 95mm x 90mm |
|ESMini | 95mm x 55mm |
|Qseven | 70mm x 70mm |
|mobile-ITX | 60mm x 60mm |
|CoreExpress | 58mm x 65mm |


#Fabricantes principais

### Fabricantes atuais

####Asus
Asus é atualmente a maior fabricante de placas-mãe. Fundada entre 1989 e 1990 em Taiwan por ex-empregados da Acer.

Conta com várias linhas de placas-mãe, para diversos segmentos. Se destaca entre o público entusiasta, com a série ROG (Republic of Gamers) e TUF (The Ultimate Force). Ambas pussuem componentes de altíssima qualidade, garantindo alto poder de overclock e estabilidade.

Além de placas-mãe, a empresa fabrica monitores, placas de vídeo, notebooks, tablets, modems, entre outros.

####ASRock
Empresa com sede em Taiwan, fundada em 2002 por Ted Hsu, um dos fundadores da Asus. Atualmente pertence ao grupo Pegatron Corporation.

É a 3ª maior fabricante de placas-mãe.

####Biostar
Empresa com sede em Taiwan, fundada em 1986.

A marca é um pouco desconhecida do mercado "comum", sendo mais conhecida pelo público entusiasta.

Atualmente é a 5ª maior fabricante de placas-mãe.

####ECS
A 6ª maior fabricante de placas-mãe.

Fundada em Taiwan em 1987, até pouco tempo a empresa tinha seu principal foco em placas de baixo custo para mercados emergentes. Atualmente tem investido no segmento entusiasta.

####EVGA
Empresa mais conhecida pelo ramo de placas de vídeo, a EVGA foi fundade em 1999 e sua sede fica no estado da Califórnia - EUA.

Focada em soluções entusiastas, atualmente tem uma participação discreta no mercado de placas-mãe.

####Foxconn
A maior fabricante de componentes eletrônicos do mundo. Além de fabricar suas próprias placas-mãe, é responsável por fabricar diversos componentes de outras empresas, como slots de memória, slots PCI-e, entre outros.

Em 2009 a reputação da empresa foi manchada, devido a problemas nos sockets Intel 1156 das placas-mãe com chipset Intel P55. Apesar dos problemas terem sido corrigidos, diversos fabricantes de placas-mãe decidiram usar sockets de outra marca (Lotes e Tyco AMP) em suas placas-mãe.

####Gigabyte
A segunda maior fabricante de placas-mãe. Fundada em 1986, com sede em Taiwan.

A empresa foca no mercado intermediário, oferecendo diversas placas-mãe com excelente custo-benefício.

####Intel
A Intel começou a fabricação de placas-mãe em 1997. Do contrário do mercado de CPUs, onde a empresa domina a arquitetura X86, no ramo de placas-mãe a empresa não tem feito um trabalho muito bom.

Há rumores de que em breve a Intel encerre a produção de placas-mãe.

####MSI
A 4ª maior fabricantes de placas-mãe. Fundada em 1986 em Taiwan.

Ao lado da Asus, é a empresa que mais têm investido no mercado entusiasta, oferecendo excelente soluções para os consumidores.

####Sapphire
Empresa fundada em 2001 com sede em Hong Kong. Participação discreta no mercado de placas-mãe, focando atualmente no mercado de placas de vídeo.

---

###Fabricantes que faliram

Abaixo, segue uma lista de fabricantes que fizeram sucesso no mercado de placas-mãe, porém, por razões diversas, faliram ou pararam sua produção.

* Abit
* Chaintech
* BFG
* DFI
* EPoX
* Soyo
* Universal Abit

---

###Fabricantes não tão conhecidos

Existem muitos outros fabricantes de placas-mãe, que por muitas pessoas são desconhecidos. O motivo disso é o fato de fabricaram placas-mãe para outros segmentos, como por exemplo segmentos industriais, notebooks, etc.

* Acer
* Jetway
* AOpen
* Lanner
* Trenton
* Tyan
* VIA

---

#Constituição básica

Uma placa-mãe é composta por diversos outros componentes interligados entre si. Talvez por isso, ela é a parte do computador que pode apresentar mais falhas.

Basicamente uma placa-mãe é formada por um PCB, slots de memórias, socket do CPU, slots PCI-e, portas SATA, saídas de áudio, entre outros.

Abaixo, vamos listar os principais componentes de uma placa-mãe moderna, e dar uma pequena explicação sobre eles.

###PCB
O PCB (Printed Circuit Board) ou placa de circuito impresso, é a placa onde são soldados os demais componentes. O PCB é composto por fenolite, fibra de vidro, filme de poliéster, filmes específicos à base de diversos polímeros, entre outros materiais. Possui a superfície cobertura por uma fina película de cobre, prata, ligas à base de ouro, níquel entre outros, nas quais são impresso os circuitos condutores onde serão fixados os componentes eletrônicos.

Um PCB de uma placa-mãe atual, é composto por cerca de 4 a 10 camadas, sendo que cada camada possui parte das trilhas necessárias, e posteriormente unidas através de pontos de solda estrategicamente posicionados.

Como o PCB é um dos componentes de mais baixa tecnologia, é bastante comum que sua produção seja terceirizada em países onde a mão de obra é barata (China), por isso é comum placas-mãe com PCBs "Made in China".

![PCB Asus Gryphon Z87](http://archive.benchmarkreviews.com/images/reviews/motherboards/gryphon-z87/ASUS-GRYPHON-Motherboard-PCB-Back-Intel-Z87-mATX.jpg)

###Socket CPU
O socket do CPU é onde o CPU é acomodado na placa-mãe. Antigamente, todos os processadores tinham o mesmo set de pinos que poderiam conectar o CPU na placa-mãe, chamados de PGA (Pin Grid Array). Estes pinos eram encaixados num socket chamado **socket 7**. Isso significava que qualquer processador poderia ser usado em qualquer placa-mãe.

Atualmente, os sockets são divididos por plataforma (AMD e Intel).

AMD ainda usa sockets PGA, enquanto que a Intel migrou para os novos LGA (Land Grid Array) , também conhecidos como socket T. A principal diferença e vantagem do LGA, é que os pinos fazem parte do socket, e não do CPU, fazendo com que o problema de pinos entortados ficassem cada vez mais raros.

Os principais sockets atuais são:

####AMD

* AM3
* G34 (Servidores)
* G32 (Servidores)
* AM3+
* FM1
* FM2

####Intel

* LGA 1155
* LGA 1150
* LGA 1366
* LGA 2011
* rPGA 988A (Notebooks)
* LGA 1248 (Servidores)
* LGA 1567 (Servidores)

![Socket Intel LGA 1150](http://i1-news.softpedia-static.com/images/news2/Intel-LGA-1150-Socket-Will-Be-Compatible-with-2014-Broadwell-CPUs-Report-2.jpg)

###Chipsets
Os chipsets são um conjunto de circuitos integrados que são responsáveis por fazer a comunicação entre o CPU e todos os outros componentes.

Até pouco tempo, placas-mãe possuiam dois principais chipsets, o Northbridge e Southbridge. 

O Northbridge era o responsável por fazer a comunicação e controle entre CPU, memória RAM, slots PCI-e. Atualmente, em placas-mãe modernas, o Northbridge não mais existe, já que esse trabalho fica a cargo do próprio CPU. O processo de fabricação de CPUs foi melhorando com o passar dos anos, atualmente temos CPUs usando o processo de fabricação de 22nm, sendo assim possível, incorporar no DIE do CPU um chipset substituto do Northbridge.

Processadores AMD possuem o controlador de memória imbutido no CPU, assim como os Intel, a diferença é que não possuem controladores PCI-e, fazendo com que placas-mãe para processadores AMD ainda terem o Northbridge.e

O Southbridge é o responsável por fazer a conexão de "baixa velocidade", tais como USB, Sata, BIOS e super I/O.

Os principais fabricantes de chipsets atualmente são, AMD, Intel, VIA e SiS. A Nvidia parou sua fabricação de chipsets em 2009

###Barramentos PCI Express, PCI

####PCI
Ao longo da história da plataforma PC, tivemos uma extensa lista de barramentos, começando com o ISA de 8 bits, usado nos primeiros PCs, passando pelo ISA de 16 bits, MCA, EISA, e VLB, até finalmente chegar no barramento PCI, que sobrevive até os dias de hoje.

O PCI é um barramento de 32 bits, que opera a 33 MHz, resultando em uma banda total de 133 MB/s, compartilhada entre todos os periféricos ligados a ele. O PCI trouxe recursos inovadores (para a época), como o suporte a plug-and-play e bus mastering e, comparado com os barramentos antigos, ele é relativamente rápido. O grande problema é que ele surgiu no começo da era Pentium, quando os processadores ainda trabalhavam a 100 MHz. Hoje em dia temos processadores quad-core se aproximando da casa dos 4 GHz e ainda assim ele continua sendo usado, com poucas melhorias.

####PCI Express
PCI Express foi criado em 2004, por uma parceria entre Intel, IBM, HP e Dell, o objetivo principal era substituir o PCI, AGP entre outros, trazendo maior velocidade, taxa de transfêrencia e largura de banda. Seu uso mais notável é com placas de vídeo. Atualmente encontra-se na versão 3.0 (985 MB/s (8 GT/s) ou seja, um PCIe x16 (16 linhas) possui 15.75 GB/s (128 GT/s) ).

O PCI Express é também um barramento serial e não um barramento paralelo, como o PCI. Antigamente, os circuitos eletrônicos eram muito lentos, por isso a solução para criar barramentos mais rápidos era adicionar mais trilhas e transmitir vários bits de cada vez. Exemplos de barramentos paralelos são as portas paralelas, usadas pelas impressoras antigas, as portas IDE e também o próprio barramento PCI.

Existem 4 tipos de slots PCI Express, que vão de x1 a x16. Estes números indicam quantas linhas de dados são utilizadas pelo slot e, consquentemente a largura de banda disponível.

![image](http://e.cdn-hardware.com.br/static/20110304/41c5a236.jpg)

Cada linha PCI Express utiliza 4 pinos de dados (dois para envio de dados, e dois para recepção de dados), que operam em modo full-duplex, podendo transmitir e receber dados simultaneamente.

Atualmente, existem duas versões de PCI Express sendo usadas, o PCI Express 2.0 e o PCI Express 3.0, sendo que este último vem se tornando cada vez mais comum, fazendo com que os PCI Express 2.0 desapareçam em breve.

O PCI Express 2.0 existe desde 2007 e oferece 500 MB/s por linha, ou seja, um PCI Express x16 consegue fornecer até 8 GB/s de largura de banda.

O PCI Express 3.0 fora lançado em novembro de 2010, conta com 985 MB/s por linha, sendo assim, um PCI Express x16 consegue fornecer até 15.75 GB/s de largura de banda.

Em novembro de 2011, o PCI-SIG (Peripheral Component Interconnect Special Interest Group) anunciou as especificações do PCI Express 4.0, que contará com 1969 MB/S por linha, totalizando 31.51 GB/s de largura de banda em um PCI Express x16.
