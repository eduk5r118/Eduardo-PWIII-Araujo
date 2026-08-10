# Eduardo-PWIII-Araujo
COMO CRIAR UM PROJETO SPRING BOOT:
existem três jeitos principais para criar um projeto spring boot eles são:
1 - spring initializer; 2 - IntelliJ; 3 - VS Code

Aqui está como criar de cada jeito:

PELO SPRING INITIALIZER:
1 - Acesse https://start.spring.io/
2 - configure o projeto:
  Você pode escolher o tipo de projeto, se é maven (suporta groovy, kotlin e java), se é Gradle - groovy (suporta apenas groovy)
  ou se é Gradle - kotlin (suporta apenas kotlin); você pode escolher a versão de spring boot incluindo as SNAPSHOTS, pode configurar 
  os metadados, a extensão do arquivo coompactado (.jar ou .war) e do arquivo extraído (.properties ou .YAML) e a versão do java.
3 - adicione as dependências:
  se for uma API: Spring Web
  se mexer com banco de dados: Spring Data JPA e MySQL Driver
4 - clique em GENERATE e vai ser criado o projeto compactado
5 - extraia o projeto

PELO INTELLIJ IDEA:
1 - abra o IntelliJ e clique em new project, selecione spring boot
2 - configure o projeto assim como é feito pelo spring initializer
3 - clique em next e crie as dependências
4 - clique em create e pronto, o projeto já é criado extraído sem necessidade de extrair.

PELO VS CODE:
1 - entre no VS Code e siga: Ctrl + Shift + P → Spring Initializr: Create a Maven Project
2 - configure o projeto e as dependências
3 - escolha a pasta de criação do projeto e pronto, ele já é criado sem necessidade de extração.
