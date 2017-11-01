# Introdução à Linguagem Rust

* Instalando e configurando Rust

  [Documentação Oficial](https://www.rust-lang.org/pt-BR/install.html)
* Conhecendo a linguagem de programacação Rust

"Rust nasceu de um projeto do funcionário do Mozilla, Graydon Hoare. Logo em seguida, no ano de 2009 a Mozilla abracou  o projeto e teve anunciado o mesmo em 2010. Rust, que nasceu compilada por um compilador escrito em Ocaml, logo em seu primeiro ano de ida já havia mudado de compilador, passando então a utilizar o famoso rustc (utilizando LLVM no back-end)" - Mozilla Brasil

Rust é uma liguagem de programção focada principalmente em:
    * Segurança sem coletor de lixo.
    * Concorrência sem disputa de dados.
    * Abstração sem overhed.

Seu design habilita a criação de programas que possuem alta performace e controle de uma linguagem baixo-nível, porém com as abstração poderosa de uma linguagem de alto-nível. Essas propriedades fazem Rust ser indicada para programadores que possuem experiência em linguagem como C e estão procurando por uma alternativa mais segura, assim como aqueles que vem de linguagens como o Python que procurarm formas de escrever códigos que rodam melhor sem sacrificar a expressividade.

Rust realiza a maioria das medidas de segurança e decusões de controle de memória em tempo de compilação, fazendo com que a performance de execução não seja afetada. Isso é útil em diversos casos que outras lingguagens não são boas: programas com requisitos de espaço e tempo previsiveis, inseridas em outras linguagens, e escrever código baixo-nível, como drivers de dispositivos e sistemas operacionias.

Em Rust  não existem ponteiros nulos ou ponteiros soltos, impossibilitando falhas de segmentação. Rust gerencia memória e recursos automaticamente, sem necessitar de um coletor de lixo.

A linguagem impede corridas de dados entre threads pois não é possivel que duas threads possam modificar um mesmo valor ao mesmo tempo. Para que umas referência possa ser compartilhada entre várias threads, ela deve ser somente leitura. Existem diversas técnicas seguras de comunicação entre threads.

Rust permite um alto grau de abstração através do sistema de traits, que são interfaces que podem ser implementadas separadamente da declaração de um tipo. Tipos genéricos são utilizados extensamente.
