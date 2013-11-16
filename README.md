## Equipe: Everton, Gabriel, Lucas

## Grupo 06 - Placas-mãe

* [Fundamentos e definições](#fundamentos-e-definições)
* [Fabricantes principais](#fabricantes-principais)
* [Constituição básica](#constituicao-basica)
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






