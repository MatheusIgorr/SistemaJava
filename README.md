# 📚 SistemaJava
O Sistema de Biblioteca é uma aplicação desenvolvida em Java com o objetivo de gerenciar um acervo de livros de forma simples e eficiente, utilizando um menu interativo via console. Este projeto foi concebido com foco em práticas de programação orientada a objetos, sendo uma excelente base para estudos ou futuras expansões.

🚀 Funcionalidades

✅ Cadastro de livros no sistema

✅ Listagem completa dos livros disponíveis

✅ Busca de livros por título ou autor

✅ Remoção de livros do acervo

✅ Interface interativa por linha de comando (CLI)

🛠️ Tecnologias e Ferramentas

Linguagem: Java (JDK 8 ou superior)

Ambientes recomendados: Eclipse, IntelliJ IDEA ou Visual Studio Code com extensão Java

Execução: Via terminal ou ambiente de desenvolvimento integrado (IDE)

💻 Estrutura do Projeto

css
Copiar
Editar
SistemaBiblioteca/
├── src/
│   ├── Livro.java          // Define os atributos e comportamentos de um livro
│   ├── Biblioteca.java     // Gerencia a coleção de livros (inclusão, exclusão, busca, listagem)
│   └── Main.java           // Ponto de entrada da aplicação e menu interativo
└── README.md
Livro.java: Classe modelo com os atributos principais de um livro, como título, autor e ano de publicação.

Biblioteca.java: Responsável por armazenar e manipular a coleção de livros, utilizando uma estrutura de dados adequada.

Main.java: Classe principal que executa a aplicação e exibe o menu de interação com o usuário.

✅ Como Executar

Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/sistema-biblioteca-java.git
Abra o projeto em sua IDE Java preferida.

Compile e execute a classe Main.java.

🎯 Exemplo de Execução

diff
Copiar
Editar
==== Sistema de Biblioteca ====
1 - Adicionar Livro
2 - Listar Livros
3 - Buscar Livro
4 - Emprestar Livro
5 - Devolver Livro
6 - Remover Livro
0 - Sair
📈 Possíveis Melhorias Futuras

Integração com banco de dados (JDBC)

Interface gráfica com JavaFX ou Swing

Persistência de dados em arquivos

Autenticação de usuários e controle de permissões

Emprego de padrões de projeto (ex: MVC)

Este projeto demonstra conceitos fundamentais de desenvolvimento em Java, sendo uma ótima introdução à modelagem de sistemas orientados a objetos e à construção de aplicações modulares e escaláveis.
