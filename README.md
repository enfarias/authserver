# Authserver Application

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-%2325A162.svg?style=for-the-badge&logo=junit5&logoColor=white)

Este é o componente de servidor de autenticação (`Authserver`), desenvolvido como uma aplicação robusta baseada em **Spring Boot**. O ecossistema foi projetado para centralizar e gerenciar o fluxo de segurança, autenticação e autorização de usuários.

---

## 🚀 Tecnologias Utilizadas

* **Java 17+**: Linguagem base para o desenvolvimento do ecossistema.
* **Spring Boot**: Framework principal para acelerar o setup e a execução da aplicação.
* **JUnit Jupiter (JUnit 5)**: Framework nativo utilizado para a automação de testes unitários e de integração.

---

## 🛠️ Estrutura do Código Analisado

O projeto inicia com as seguintes classes fundamentais:

* `AuthserverApplication.java`: A classe de entrada (Entry Point) que inicializa o contexto do Spring Boot através do método `main`.
* `AuthserverApplicationTests.java`: A classe de testes integrados que valida se o contexto da aplicação (`ApplicationContext`) é carregado com sucesso, garantindo a integridade inicial das configurações.

---

## 🏁 Como Executar o Projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
* [JDK 17](https://www.oracle.com/java/technologies/downloads/) ou superior.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/enfarias/authserver.git](https://github.com/enfarias/authserver.git)
   cd authserver
   ```
2. **Execute a aplicação:**
   ```bash
   ./gradlew bootRun
   ```
3. **Execute os testes automatizados:**
   ```bash
   ./gradlew test
   ```
   
---

## 🧪 Suíte de Testes

A aplicação conta com validações automatizadas integradas ao ciclo de build. Para rodar especificamente o teste de carregamento de contexto analisado:

```bash
./gradlew test --tests "com.devsuperior.authserver.AuthserverApplicationTests"
```

> 💡 **Nota:** O teste `contextLoads()` garante que todas as dependências, beans e configurações de ambiente mapeadas pelo Spring Boot estão prontas para subir sem falhas críticas de infraestrutura.
