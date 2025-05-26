# 🧠 Java Interview Questions Guide [24-25]

Welcome to the **Java Interview Prep Guide**! This document contains categorized and detailed questions that will help you revise or prepare for your next interview. The questions span across Core Java, Spring Framework, Microservices, Databases, and Coding Problems.

---

## 📚 Table of Contents

- [1. Core Java](#1-core-java)
- [2. Spring & Spring Boot](#2-spring--spring-boot)
- [3. Microservices](#3-microservices)
- [4. Databases](#4-databases)
- [5. Coding Questions](#5-coding-questions)

---

## 1. Core Java

<details>
<summary>Click to expand Core Java Questions 🔽</summary>

### ✅ Java 17 Features
- Record classes, Sealed classes, Text Blocks, Pattern Matching in Switch

### ✅ String Handling
- Why are Strings immutable in Java?
- Difference between `String`, `StringBuffer`, and `StringBuilder`
- When to use `StringBuffer` and `StringBuilder`?
- How many objects created? 
  ```java
  String s = "abc";
  String b = new String("bac");
  ```
- Output and explanation:
  ```java
  String a = "str";
  String b = a;
  a = "modify";
  System.out.println(b); // Output?
  ```

### ✅ Immutability and Memory
- How to create a custom immutable class?
- How to handle mutable fields (like `List`, `Date`) in immutable classes?
- Why do we need immutable classes?
- `intern()` method in `String` usage
- When to use `double`, `float`, and `BigDecimal`
- Java Memory Model
- Wrapper Classes
- Heap vs Constant Pool
- GC Algorithms (e.g. G1 GC)
- Static String variables — memory implications
- Memory Leaks — causes and detection

### ✅ OOP Concepts
- Abstract class vs Interface
- Is Java 100% OOP?
- Core OOP Principles: Inheritance, Encapsulation, Abstraction, Polymorphism
- Call by Value or Reference?
- Access Modifiers: `protected`, `static`, `final`, `private`

### ✅ Exception Handling
- Checked vs Unchecked
- Overriding and Exceptions: [GeeksForGeeks Explanation](https://www.geeksforgeeks.org/exception-handling-with-method-overriding-in-java/)

### ✅ Concurrency & Collections
- Thread lifecycle, ways to create threads
- Inter-thread communication (`wait`, `notify`, `notifyAll`)
- Deadlock example
- Executor Framework, Callable vs Runnable
- Synchronization (methods, blocks, static)
- CountDownLatch & CyclicBarrier
- `wait` vs `sleep`

### ✅ Collections and Internals
- Internal working of `HashMap`, `Set`
- `equals()` and `hashCode()` contract
- `Comparator` vs `Comparable`
- `HashMap` vs `Hashtable`
- FailFast vs FailSafe Iterators
- `CopyOnWriteArrayList`, `ConcurrentHashMap`
- Serialization, `transient`, `Externalizable`

### ✅ Design & Java 8+
- Design Patterns: Singleton, Factory, Builder, etc.
- Singleton — breaking scenarios & solutions
- SOLID Principles
- Java 8 Features: Stream API, Optional, Lambda, Method References
- Functional Interfaces (`Function`, `Predicate`, etc.)
- Default methods in interfaces (Diamond problem)
- `map` vs `flatMap`
- `stream()` vs `parallelStream()`
- Custom Annotations

</details>

---

## 2. Spring & Spring Boot

<details>
<summary>Click to expand Spring Questions 🌱</summary>

### ✅ Core Concepts
- Why Spring? Latest version used?
- IOC & Dependency Injection
- Spring vs Spring Boot
- Migration issues (Spring Boot 2.x → 3.x)
- `@SpringBootApplication`

### ✅ Annotations & Config
- `@Controller` vs `@RestController`
- Global Exception Handling with `@ControllerAdvice`
- `@ConfigurationProperties` for property binding
- `@Bean` vs `@Component`
- Stereotype annotations: `@Component`, `@Service`, `@Repository`
- `@Async`, CompletableFuture
- `@Autowired`, `@Qualifier`, `@Primary`

### ✅ Tools & Utilities
- Spring Actuator
- Swagger (OpenAPI)
- Exclude embedded server config
- Multi-DataSource config
- Schedulers

### ✅ HTTP & Validation
- `PUT`, `PATCH`, `POST` differences
- `@PathVariable` vs `@RequestParam`
- Custom Validations
- Transactions
- Spring Profiles

</details>

---

## 3. Microservices

<details>
<summary>Click to expand Microservices Questions ☁️</summary>

### ✅ Architecture
- Explain your architecture
- Service Registry/Discovery (Eureka)
- Monolith vs Microservice
- Migration strategies

### ✅ Patterns
- Saga Pattern
- Circuit Breaker (Resilience4j)
- Bulkhead

### ✅ Observability
- Distributed Tracing with Zipkin

### ✅ Communication
- Sync (REST), Async (Kafka, RabbitMQ)
- Kafka vs RabbitMQ
- Kafka Concepts:
  - GroupId, Topic, Partition, Zookeeper, Fault Tolerance, Replication
  - Kafka Setup Steps

### ✅ Practices
- Idempotency
- Branching Strategy
- Peer Reviews

</details>

---

## 4. Databases

<details>
<summary>Click to expand Database Questions 🗃️</summary>

### ✅ SQL & Relational
- Databases used (SQL/NoSQL)
- Indexing, Clustered Indexing
- Joins in SQL
- ACID Properties
- Normalization: 1NF, 2NF, 3NF
- Isolation Levels

### ✅ Performance Tuning
- Select only required columns
- Joins > Subqueries
- Logical partitioning & Sharding
- Indexing best practices

### ✅ NoSQL
- Experience with NoSQL?
- Does NoSQL support ACID?

### ✅ Spring Data JPA
- Advantages
- Entity Mapping
- Lazy vs Eager loading

</details>

---

## 5. Coding Questions

<details>
<summary>Click to expand Java Coding Challenges 💻</summary>

### Java 8 Based
- Frequency of characters in a `String`
- Sort `HashMap<Integer, String>`
- Filter even & odd numbers in a single stream
- Iterate `HashMap`
- Reverse sentence using Java 8:
  ```java
  "Today is Sunday" -> "yadoT si yadnuS"
  ```

### Threading
- Deadlock example with Threads

### Data Structures
- Custom `ArrayList` using Arrays
- Sort user-defined objects

### Algorithms
- Two Sum
- Unique Substrings
- All combinations of a string: `A`, `B`, `C`, `AB`, `BC`, `ABC`
- Find Median of Array

### SQL
- Query to find duplicates
- Query to find 2nd highest salary

</details>

---

## 📌 Contribution

Want to add more questions or improve the formatting? Feel free to open a PR or raise an issue.

## 📧 Connect

If you find this helpful, consider ⭐️ starring the repo and sharing it with others.

---

Happy Learning! ☕
