# Guia de Uso do Maven

Este guia tem como objetivo documentar os passos básicos para utilizar o Maven em um projeto Java.

## Criando um novo projeto

Para criar um novo projeto com o Maven, execute o seguinte comando no terminal:

```
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
```

## Compilando o projeto

Para compilar o projeto, utilize o comando:

```
mvn package
```

## Executando o projeto

Para executar o projeto, utilize o seguinte comando:

```
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App
```

## Gerando um site

É possível gerar um site para o projeto utilizando o comando:

```
mvn site
```

## Acessando o site gerado

Após gerar o site, você pode acessá-lo abrindo o arquivo `index.html` localizado na pasta `target/site` do seu projeto.
