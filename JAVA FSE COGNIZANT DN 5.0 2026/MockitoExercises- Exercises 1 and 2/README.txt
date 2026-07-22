# Mockito Exercises 1 & 2

This repository contains the solutions for **Exercise 1: Mocking and Stubbing** and **Exercise 2: Verifying Interactions** from the **Cognizant Digital Nurture (DN) 5.0 Java Full Stack Engineer Upskilling Program**.

## Technologies Used

- Java 17
- Maven
- JUnit 5
- Mockito

## Project Structure

```
MockitoExercises
│
├── pom.xml
├── .gitignore
│
└── src
    ├── main
    │   ├── java
    │   │   └── com.example.mockito
    │   │       ├── ExternalApi.java
    │   │       └── MyService.java
    │   └── resources
    │
    └── test
        └── java
            └── com.example.mockito
                └── MyServiceTest.java
```

## Exercise 1 – Mocking and Stubbing

**Objective**
- Create a mock object using Mockito.
- Stub the `getData()` method to return a predefined value.
- Validate the service response using JUnit assertions.

**Mockito Concepts Used**
- `mock()`
- `when()`
- `thenReturn()`
- `assertEquals()`

---

## Exercise 2 – Verifying Interactions

**Objective**
- Verify that the mocked object's `getData()` method is invoked when the service method is executed.

**Mockito Concepts Used**
- `verify()`



**Author**

**Aaryan Gupta**