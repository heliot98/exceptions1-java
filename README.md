
````markdown
# exceptions1-java

Projeto Java com foco em **tratamento de exceções**.  
Java project focused on **exception handling**.

---

## 🧠 Objetivo | Purpose

**PT-BR:**  
Este projeto simula um sistema de **reservas de hotel**, onde o usuário informa as datas de check-in e check-out. O sistema valida as datas e trata erros utilizando exceções personalizadas.

**EN:**  
This project simulates a **hotel reservation system**, where the user provides check-in and check-out dates. The system validates the dates and handles errors using custom exceptions.

---

## 📂 Estrutura | Structure

```bash
exceptions1-java/
├── src/
│   ├── model/
│   │   └── Reservation.java       # Lógica de reserva | Reservation logic
│   └── application/
│       └── Program.java           # Método main | Main method
└── README.md
````

---

## ⚙️ Tecnologias e Recursos | Technologies and Tools

* Java 17+
* `java.time.LocalDate`, `DateTimeFormatter`
* Tratamento de exceções (`try-catch`, `throw`)
  Exception handling (`try-catch`, `throw`)
* Orientação a objetos | Object-oriented programming

---

## 🚀 Como Executar | How to Run

1. Clone o repositório | Clone the repository:

```bash
git clone git@github.com:heliot98/exceptions1-java.git
```

2. Compile e execute com sua IDE ou via terminal:
   Compile and run using your IDE or via terminal:

```bash
cd exceptions1-java
javac src/application/Program.java
java application.Program
```

---

## 📌 Exemplo de Uso | Usage Example

```text
Room number: 200
Check-in date (dd/MM/yyyy): 20/07/2025
Check-out date (dd/MM/yyyy): 25/07/2025
```

**Erro tratado | Handled error:**

```text
Error in reservation: Check-out date must be after check-in date
```

---

## 📚 Aprendizados | What You’ll Learn

✅ Criar e lançar exceções personalizadas
✅ Validate lógica de negócio com tratamento de erro
✅ Dominar `try-catch` em Java
✅ Practice custom exception creation
✅ Validate business rules with error handling
✅ Understand `try-catch` structure in Java

---

## 👨‍💻 Autor | Author

**Hélio Tarquínio**
Estudante de Análise e Desenvolvimento de Sistemas
Systems Analysis and Development student

[LinkedIn](https://www.linkedin.com/in/helio-tarquinio-66b894263) | [GitHub](https://github.com/heliot98)

---

> Projeto desenvolvido como parte dos estudos em Java e tratamento de exceções.
> Project developed as part of Java and exception handling studies.

```

