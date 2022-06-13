# COMO INSTALAR O WebODM - A ALTERNATIVA OPEN-SOURCE DEFINITIVA AO AGISOFT METASHAPE
(HOW TO INSTALL WebODM - THE ULTIMATE OPEN-SOURCE ALTERNATIVE TO AGISOFT METASHAPE)



**Este é um projeto em construção e tem como propósito exender ao público em geral um pouco do que é tratado na plataforma da GeoOne**




## INTRODUÇÃO:

<details>
     <summary>Clique Aqui para Expandir INTRODUÇÃO</summary>
  


  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>

# A collapsible section containing code
<details>
  <summary>Click to expand!</summary>
  
  ```javascript
    function logSometing(something) {
      console.log(`Logging: ${something}`);
    }
  ```
</details>

# How to structure
```
# A collapsible section with markdown
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>
```
**Two important rules:**
1. Make sure you have an **empty line** after the closing `</summary>` tag, otherwise the markdown/code blocks won't show correctly.
2. Make sure you have an **empty line** after the closing `</details>` tag if you have multiple collapsible sections.
-----------------------------------------------------------------------------------------



Neste artigo vamos tratar de como instalar o WebODM de forma totalmente gratuita - sendo este software a alternativa mais eficaz ao Agisoft Metashape, e o faremos nos principais Sistemas Operacionais(Windows, MacOS e Linux). Mas antes de procedermos o tutorial de instalação, permita-me mostrar-lhe a razão do WebODM ser tão importante para você, profissional da aerofotogrametria e para nós da GeoOne:

## O NOVO AMBIENTE DA AEROFOTOGRAMETRIA NO MERCADO DE TRABALHO PARA O PROFISSIONAL QUE ESTÁ COMEÇANDO E O LUGAR DO WEBODM

### DESAFIOS QUE QUEM SE INICIA NA AEROFOTOGRAMETRIA

É cada vez mais crescente a busca pela geração de produtos cartográficos através do uso de drones. O que realmente temos vivido é a explosão da procura pela utilização dos drones na engenharia devido ao arrefecimento dos altos custos que tinha a fotogrametria aérea, da praticidade e rapidez. Entretanto, dois problemas se tornam desafios a serem vencidos, especialmente para quem está iniciando no mercado de trabalho: o alto custo de softwares de processamento das imagens produzidas pelos drones e a garantida de que os produtos gerados atendam às exigências do Padrão de Exigência Cartográfica(PEC).

### SOLUÇÕES APRESENTADAS PELA GEOONE

A [GeoOne](https://geoone.com.br/)vem atuando na solução destes dois problemas de forma brilhante e com resultados impressionantes, pois para o primeiro problema, isto é, para a questão do alto custo de softwares, encontramos no WebODM, QGIS e CLODCOMPARE, a solução completa. Já para a segunda questão, isto é, da precisão dos produtos, a [GeoOne](https://geoone.com.br/) tem uma metodologia pioneira e exclusiva, capaz de garantir a eficiência na entrega dos produtos em conformidade com o [PEC-PCD](https://www.youtube.com/watch?v=77i0kabRc0Y). Para tal, a [GeoOne](https://geoone.com.br/)vale-se de algoritmos e plugins desenvolvidos pelo professor [Leandro França](https://geoone.com.br/leandro-franca/) que possui sólida formação e vasta experiência nas áreas exigidas.

Hoje, não há mais razão para se dizer que essas barreiras citadas acima sejam impedimentos para os profissionais que precisam realizar trabalhos aerofotogramétricos, mesmo se esses profissionais forem recém chegados ao mercado de trabalho ou ainda estudantes. Na [GeoOne](https://geoone.com.br/blog/) é possível encontrar uma extensa gama de conteúdos para a realização de trabalhos práticos com bom embasamento teórico.

CONHECENDO OS DOIS PRINCIPAIS SOFTWARES QUE SÃO USADOS PELA GEOONE

Se você vai começar conosco nesta jornada, é preciso entendermos um pouco sobre a instalação dos dois principais softwares que suportam o trabalho da GeoOne na atualidade: WebODM e [QGIS](https://geoone.com.br/cursos/curso_gratis/). Sobre o QGIS, há um curso gratuito disponível na área de membros da GeoOne que pode levá-lo do Zero ao seu primeiro Mapa - [Clique Aqui](https://geoone.com.br/cursos/curso_gratis/)para acessá-lo. Já sobre o [WebODM](https://es.wikipedia.org/wiki/OpenDroneMap_/_ODM), podemos dizer que é o software [OpendDroneMap](https://es.wikipedia.org/wiki/OpenDroneMap_/_ODM)com sua interface gráfica, isto é, o OpenDroneMap com interface amigável ao usuário. O OpenDroneMap é um &quot;Software de fotogrametria de código aberto para processar fotos aéreas em mapas e modelos 3D&quot;. ele é capaz de entregar os mais cobiçados produtos aerofotogramétricos, inclusive o [Ortofotomosaico](https://pt.wikipedia.org/wiki/Aerofotogrametria#Ortofotografia). Numa aula no [Youtube](https://www.youtube.com/c/LeandroFran%C3%A7a/)com o título &quot;[Como processar um ortomosaico no WebODM](https://www.youtube.com/watch?v=ZDyX-zuvg9g&amp;t=633s)&quot;, o professor [Leandro](https://www.youtube.com/c/LeandroFran%C3%A7a/)ensina a fazer um processamento de imagens utilizando o WebODM.

Sabedores da importância do WebODM, vamos focar agora na sua instalação gratuita nos Sistemas Operacionais já citados:

1.
## ENCONTRANDO INFORMAÇÕES SEGURAS SOBRE O WebODM E OS REQUISITOS PARA SUA INSTALAÇÃO

  1.
### O SITE OFICIAL

Este é o link para o site oficial: [https://www.opendronemap.org/webodm](https://www.opendronemap.org/webodm)

No menu &quot;WebODM&quot;, você pode encontrar todas as instâncias do WebODM

![](RackMultipart20220609-1-dbstmi_html_f9bbdde9908ef60c.png)

Dê uma lida em todo o conteúdo que você conseguir. Caso não tenha familiaridade com o inglês, clique com o botão direito do mouse em alguma área do texto da página e escolha traduzir para o português.

  1.
### DOCUMENTAÇÕES OFICIAIS

No caso da instalação Manual(grátis) há dois tutoriais que podem ser seguidos segundo a documentação oficial:

1. [MANUAL DE INSTALAÇÃO MAIS ATUALIZADO](https://github.com/OpenDroneMap/WebODM/#getting-started)
2. [MANUAL DE INSTALAÇÃO MAIS EXPLICATIVO](https://docs.opendronemap.org/installation/#installation)

Para este tutorial, vamos usar o primeiro link para o Windows e o segundo para Linux e MacOS.

  1.
### REQUISITOS GERAIS PARA INSTALAÇÃO NOS PRINCIPAIS SISTEMAS OPERACIONAIS

Os requisitos para instalação do WebODM hoje (10-06-2022) podem ser resumidos da seguinte maneira, segundo a página oficial: [https://www.opendronemap.org/webodm/download](https://www.opendronemap.org/webodm/download) (A informação encontra-se no final desta página)

![](RackMultipart20220609-1-dbstmi_html_b6f876d84b712619.png)

Há algumas considerações sobre a informação acima:

- Os requisitos mínimos servem apenas para você conhecer o software(não é o objetivo deste tutorial). O critério preferível deve ser os Requisitos recomendáveis.
- Os requisitos descritos acima apreciam a instalação paga(fácil) que é muito melhor para quem possui Windows ou MacOS([Veja como instalar o WebODM nesse modo](https://youtu.be/PQK71p-xD0I)).

Um breve comparativo das duas formas de instalação (Paga vs Manual):

![](RackMultipart20220609-1-dbstmi_html_d5156418cdac6d.png)

1.
## WINDOWS(Windows 11 e 10)

  1.
### REQUISITOS E PREPARAÇÃO PARA INSTALAÇÃO

1.
#### Resumo dos Requisitos

**IMPORTANTE** : Estes requisitos podem mudar no decorrer da evolução do software, faz-se necessária, portanto, a verificação junto aos sites oficiais, tanto do [WebODM](https://www.opendronemap.org/webodm/download/), quanto dos listados abaixo.

BACK-END e SOFTWARES EXIGIDOS:

- [WSL 2](https://docs.microsoft.com/pt-br/windows/wsl/install) (subsistema Linux no Windows)
- [DOCKER DESKTOP](https://docs.docker.com/desktop/windows/install/)
- [GIT](https://git-scm.com/downloads)

SISTEMA:

- Windows 10 (acima). Lembrando que será necessária a virtualização do sistema e a instalação do backend WSL2 e isso exigirá, no caso do Windows 11 64-bit: Home ou Pro a versão 21H2 ou mais novo, ou Enterprise/Education com as versões 21H2 ou mais novo; no caso do Windows 10 64-bit: pode ser Home ou Pro 21H1 com a build 19043 ou mais alta, ou Enterprise/Education 20H2 com build 19042 mais nova.

HARDWARE:

- PC ou Notebook com processador de 64bits com possibilidade de virtualização.
- 16GB de memória RAM(recomenda-se mais, pois 4GB estará dedicado ao Docker Desktop).
- HD (preferivelmente um SSD) de 100GB acima(100GB é para processamentos pequenos).
- Atualmente _ **não** _ é exigido um Graphic Card(Placa de Vídeo).

  1.
### INSTALAÇÃO (MÉTODO MAIS SIMPLES)

  1.
### TESTE DE PROCESSAMENTO DE IMAGENS DE DRONE
1.
## LINUX(Ubuntu-Mint)

  1.
### REQUISITOS PARA INSTALAÇÃO
  2.
### INSTALAÇÃO PELO TERMINAL(MÉTODO MAIS SIMPLES)
  3.
### TESTE DE PROCESSAMENTO DE IMAGENS DE DRONE
2.
## MAC(Monterey)

  1.
### REQUISITOS PARA INSTALAÇÃO
  2.
### INSTALAÇÃO(MÉTODO MAIS FÁCIL)
  3.
### TESTE DE PROCESSAMENTO DE IMAGENS DE DRONE
3.
## LIVEODM(Linux - Um WebODM Portátil, mas sem gravação persistente)

  1.
### O QUE É UMA GRAVAÇÃO NÃO PERSISTENTE(Vantagens e Desvantagens)
  2.
### REQUISITOS PARA INSTALAÇÃO DO WebODM
  3.
### INSTALAÇÃO DO LIVEODM
  4.
### TESTE DE PROCESSAMENTO DE IMAGENS DE DRONE

## CONCLUSÃO







