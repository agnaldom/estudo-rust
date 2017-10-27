# Estudo da Liguagem de Programação Rust
Resumo do livro: https://coreh.github.io/rust-book-pt-br/

Rust é uma linguagem de programação focada em segurança, eficiência e concorrência. Seu design lhe permite criar programas com o desempenho e controle de uma linguagem de baixo nível, mas com as abstrações poderosas de uma linguagem de alto nível.

Rust executa a maioria das suas verificações de segurança e decisões de gerenciamento de memória em tempo de compilação, para que o desempenho de execução do seu programa não seja impactado.

# Hello, Cargo!

Cargo is Rust’s build system and package manager, and Rustaceans use Cargo to manage their Rust projects because it makes a lot of tasks easier.

# Creating a Project with Cargo

`$ cargo new hello_cargo --bin`
`$ cd hello_cargo`

# Variáveis e Mutabilidade

Por padrão variáveis em Rust são imutáveis.

Quando uma variável é imutável, assim que um valor passa a estar vinculado ao seu nome é impossível alterá-lo. Para ilustrar, vamos gerar um novo projeto chamado variaveis [sic] no seu diretório projetos, usando o comando cargo new --bin variaveis.

Em seguida, no diretório variaveis que acabou de ser criado, abra src/main.rs 
