# JavaExercises

Projeto Java Maven configurado para Java 20, otimizado para GitHub Codespaces.

## Requisitos

- Java 20
- Maven 3.x

## Como usar no Codespaces

1. Clique em "Code" > "Open with Codespaces" > "New codespace"
2. Aguarde o container ser criado com Java 20 e Maven
3. Execute os comandos Maven normalmente

## Comandos Maven

```bash
# Compilar o projeto
mvn compile

# Executar testes
mvn test

# Criar o pacote JAR
mvn package

# Executar a aplicação principal
mvn exec:java
```

## Estrutura do projeto

```
├── pom.xml                          # Configuração Maven
├── src/
│   ├── main/java/com/exercises/     # Código fonte
│   └── test/java/com/exercises/     # Testes
└── .devcontainer/
    └── devcontainer.json            # Configuração Codespaces
```