# 0x02. Python - Async Comprehension
### Back-end programming Course of *Holberton School* at *ALX*. cover the `Python - Async Comprehension` language.

---
## Learning Objectives

*   How to write an asynchronous generator
*   How to use async comprehensions
*   How to type-annotate generators

---
### 0\. Async Generator

- Define a coroutine called `async_generator` takes no arguments. <br> Loop 10 times, each time wait 1 second, then yield a random number.
---

### 1\. Async Comprehensions

- Import `async_generator` from the previous task and then define a coroutine called `async_comprehension` takes no arguments. <br> Return 10 random numbers using async_generator.
---

### 2\. Run time for four parallel comprehensions

- Import `async_comprehension` from the previous file and define a `measure_runtime` coroutine that will execute `async_comprehension` four times in parallel using `asyncio.gather`. <br> Execute async_comprehension four times in parallel.
