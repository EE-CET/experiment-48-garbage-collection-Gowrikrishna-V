# Experiment 48: Garbage Collection

## Problem Statement

Write a program to demonstrate garbage collection in Java.
Create a class with a `finalize()` method that prints "Garbage Collected".
In the main method, create an object, assume it is null (or make it eligible for GC), and call the garbage collector.

## Input Format

* No input.

## Output Format

* `Garbage Collected`

### Example 1

**Input:**

```text
No input
```

**Output:**

```text
Garbage Collected
```

**Note:** The output depends on the JVM actually running the garbage collector. Using `System.gc()` requests it, but does not guarantee it immediately. However, for this lab, we expect the message to appear.
