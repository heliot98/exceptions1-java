
# exceptions1-java

Projeto Java simples com foco em **tratamento de exceções**, abordando conceitos fundamentais como:

- Validação de regras de negócio
- Lançamento de exceções personalizadas
- Uso de `try-catch` para controle de fluxo
- Boas práticas no tratamento de erros

## 🧠 Objetivo

O projeto simula um sistema de **reservas de hotel**, onde o usuário insere datas de check-in e check-out. O sistema valida as datas e trata erros com mensagens apropriadas. Ele é usado como exercício para entender:

- Exceções padrão do Java (como `DateTimeParseException`)
- Exceções personalizadas (como `DomainException`)
- Propagação e captura de exceções

## 📂 Estrutura

```bash
exceptions1-java/
├── src/
│   ├── model/
│   │   └── Reservation.java       # Classe principal da lógica de reserva
│   └── application/
│       └── Program.java           # Classe com o método main
└── README.md
````

## ⚙️ Tecnologias e recursos utilizados

* Java 17+ (recomendado)
* `java.time.LocalDate` e `DateTimeFormatter`
* Tratamento de exceções (`try-catch`, `throw`)
* Orientação a objetos (encapsulamento e lógica de domínio)

## 🚀 Como executar

1. Clone o repositório:

```bash
git clone git@github.com:heliot98/exceptions1-java.git
```

2. Compile e execute com sua IDE (como Eclipse ou IntelliJ) ou no terminal:

```bash
cd exceptions1-java
javac src/application/Program.java
java application.Program
```

## 📌 Exemplos de uso

Durante a execução, o sistema solicitará:

```text
Room number: 200
Check-in date (dd/MM/yyyy): 20/07/2025
Check-out date (dd/MM/yyyy): 25/07/2025
```

Se o usuário tentar inserir uma data inválida (como check-out anterior ao check-in), o sistema informará o erro:

```text
Error in reservation: Check-out date must be after check-in date
```

## 📚 Aprendizados

Este projeto é ideal para quem deseja:

* Compreender o fluxo de exceções no Java
* Criar e lançar exceções personalizadas com mensagens claras
* Aplicar validações de lógica de negócios dentro de classes de domínio

## 👨‍💻 Autor

**Hélio Tarquínio**
Estudante de Análise e Desenvolvimento de Sistemas
[LinkedIn](https://www.linkedin.com/in/helio-tarquinio-66b894263) | [GitHub](https://github.com/heliot98)

---



