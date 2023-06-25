# Projeto Sistema de Lembretes

Meu projeto de Sistema de Lembretes é uma aplicação web que consiste em uma API RESTful desenvolvida em Java com Spring Boot no back-end e um front-end em React. A API segue os padrões RESTful, permitindo operações em recursos através dos métodos HTTP. A linguagem Java é escolhida por sua popularidade e recursos de orientação a objetos. O Spring Boot simplifica o desenvolvimento fornecendo configuração automática. O React é utilizado para criar uma interface web bonita e interativa. O projeto segue o paradigma orientado a objetos, organizando o código em classes e objetos. No geral, o projeto combina tecnologias e padrões adequados para criar um sistema de lembretes funcional e agradável de usar.

### BACK-END E FRONT-END
#### BACK-END: 
* Linguagens utilizadas
   * Java(Spring Boot): Escolhi ultilizar Java com o framework Spring Boot para o desenvolvimento do back-end pois é uma opção comumente adotada.O Java é conhecido por sua ampla adoção na indústria, suporte à orientação a objetos e vasta comunidade de desenvolvedores. O Spring Boot, por sua vez, simplifica o desenvolvimento de aplicativos web, fornecendo uma configuração automática e um conjunto de bibliotecas e ferramentas 
   * API seguindo os padrões RESTful: Ultilizei a abordagem RESTful  pois permite uma comunicação simples e eficiente entre o cliente e o servidor. Ao seguir os princípios REST, como recursos identificáveis, métodos HTTP adequados e retorno de respostas no formato JSON, o sistema se torna mais intuitivo e escalável.
* Banco de dados
   * Banco de dados H2: A escolha do banco de dados H2 foi uma opção adequada para o desenvolvimento inicial e testes do sistema de lembretes, pois é leve e não requer configuração complexa. No entanto, é importante considerar uma solução de banco de dados mais robusta para ambientes de produção, como MySQL, PostgreSQL ou MongoDB, dependendo dos requisitos do sistema.
#### FRONT-END:
* Linguagens utilizadas
   * React: O uso do React para o front-end foi uma escolha sólida, uma vez que permite criar interfaces de usuário interativas e reativas. O React possui uma comunidade ativa e oferece recursos poderosos, como componentização, gerenciamento de estado eficiente e renderização otimizada.
 * Styled Components: Escolhi utilizar Styled Components pois é uma abordagem moderna para estilizar componentes React, fornecendo uma maneira fácil de escrever estilos CSS no próprio componente. Essa abordagem mantém os estilos encapsulados e melhora a manutenção do código.
 * A definição de padrões de cores com base na identidade visual da empresa contribui para uma interface atraente e coesa.

## Instruções pra executar o sistema
#### BACK-END:
Entre no diretorio do back-end que se encontra em teste-dti\back-end

Verifique se você possui o Maven instalado em seu sistema. Se o Maven não estiver instalado, siga as instruções neste link para instalar o Maven no Windows: https://dicasdejava.com.br/como-instalar-o-maven-no-windows/
```
cd target
java -jar TesteDti-0.0.1-SNAPSHOT.jar
```
#### FRONT-END:
Entre no diretorio do front-end que se encontra em  teste-dti\front-end
```
npm install
npm run dev
```
* Após seguir essas instruções, o Sistema de Lembretes estará pronto para ser usado. Você poderá acessá-lo em seu navegador através do endereço fornecido pelo servidor de desenvolvimento do React. Certifique-se de que o servidor back-end também esteja em execução para que o front-end possa se comunicar corretamente com a API.
