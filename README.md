# Tutorial Mavem e Graddle

## Maven: 
1. Conceitos básicos do Maven:
   - O que é Maven e como ele facilita o gerenciamento de projetos Java.
   - Estrutura de um projeto Java com Maven (src/main/java, src/test/java, etc.).
  
2. POM (Project Object Model):
   - Compreensão detalhada do arquivo pom.xml.
   - Como declarar dependências e suas versões.
   - Configuração de plugins específicos para projetos Java (ex.: maven-compiler-plugin para definir a versão do Java).
  
3. Dependências e Gerenciamento:
   - Como buscar e adicionar dependências em projetos Java.
   - Configuração de repositórios de dependências.
   - Gerenciamento de escopos de dependências (ex.: compile, test, provided).

4. Ciclo de vida de build do Maven:
   - Fases do ciclo de vida, como validate, compile, test, package, verify, install, deploy.
   - Execução de comandos Maven (mvn compile, mvn test, mvn package, etc.).
  
5. Testes Automatizados:
   - Configuração do maven-surefire-plugin para rodar testes unitários.
   - Relatórios de testes e integração com frameworks como JUnit e TestNG.

6. Plugins importantes para Java:
   - maven-compiler-plugin para configurar a versão do Java.
   - maven-surefire-plugin para testes.
   - maven-jar-plugin para empacotar o projeto como JAR.

7. Perfis de Build:
   - Configuração de perfis para diferentes ambientes (ex.: desenvolvimento, produção).
   - Parâmetros customizados para perfis.
  
8. Execução de Aplicações Java:
   - Uso do exec-maven-plugin para executar a aplicação.
   - Empacotamento com maven-assembly-plugin ou maven-shade-plugin para criar JARs executáveis.
  
9. Integração com IDEs:
    - Importação e configuração de projetos Maven em IDEs populares como IntelliJ IDEA e Eclipse.

## Gradle 
1. Conceitos básicos do Gradle:
   - O que é Gradle e por que ele é popular em projetos Java.
   - Estrutura de um projeto Java usando Gradle (build.gradle, src/main/java, etc.).

2. Scripts de Build:
   - Escrever e entender scripts de build em Groovy e Kotlin DSL.
   - Configuração básica em build.gradle.

3. Gerenciamento de Dependências:
   - Declaração de dependências em projetos Java (implementation, testImplementation).
   - Configuração de repositórios de dependências (ex.: Maven Central).

4. Tarefas no Gradle:
   - O que são tarefas e como criar tarefas customizadas.
   - Comandos Gradle para compilar e executar (gradle build, gradle test).

5. Plugins essenciais:
   - java plugin para compilar e construir projetos Java.
   - Plugins adicionais como application para criar JARs executáveis.

6. Configuração de Compilação:
   - Configuração de versões de Java em build.gradle.
   - Uso do tasks.withType(JavaCompile) para ajustar parâmetros de compilação.

7. Testes com Gradle:
   - Configuração de testes automatizados e execução com gradle test.
   - Relatórios de teste e integração com frameworks como JUnit.

8. Criação de JAR Executável:
   - Uso do plugin application para facilitar a execução de aplicações Java.
   - Configuração do jar task para criar JARs com dependências.

9. Build Cache e Paralelismo:
    - Utilização do cache de build para otimizar a compilação.
    - Configuração para builds paralelos em projetos Java grandes.
  
10. Integração com IDEs:
    - Configuração e importação de projetos Gradle em IntelliJ IDEA e Eclipse.
    - Ajustes de build e sincronização com a IDE. 
