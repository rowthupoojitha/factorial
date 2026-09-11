# Factorial in Java

A simple Java program to calculate the **factorial of a given number**.

## 📌 Description

The factorial of a non-negative integer `n` is the product of all positive integers from `1` to `n`.

### Formula

```text
n! = n × (n-1) × (n-2) × ... × 2 × 1
```

### Example

```text
5! = 5 × 4 × 3 × 2 × 1
5! = 120
```

## 💻 Technologies Used

* Java
* Scanner
* For Loop
* If-Else
* `long` data type

## 🚀 How to Run

### 1. Compile the program

```bash
javac Factorial.java
```

### 2. Run the program

```bash
java Factorial
```

## 📝 Example Output

```text
Enter a number: 5
Factorial of 5 is: 120
```

Another example:

```text
Enter a number: 7
Factorial of 7 is: 5040
```

## 🔍 How It Works

The program starts the factorial value at `1` and uses a `for` loop to multiply it by every number from `1` to the given number.

For example, when the input is `5`:

```text
1 × 2 × 3 × 4 × 5 = 120
```

Negative numbers are not allowed because factorial is defined only for non-negative integers.

## 📂 Project Structure

```text
factorial-java/
│
├── Factorial.java
├── .gitignore
└── README.md
```

## 📜 License

This project is created for learning and educational purposes.