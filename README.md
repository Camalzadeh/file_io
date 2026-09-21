# Java File I/O

Reads an employee list from a text file, answers a set of queries over it, and
writes each answer back out as its own report file. Java Lessons, task 9.

## What it covers

- Parsing a delimited text file into objects, and handling the malformed lines.
- Writing results with `BufferedWriter`, one report per query.
- Combining file I/O with the Stream API - the queries themselves are pipelines.

## Running it

```bash
javac -d out src/*.java
java -cp out Main
```

The program reads `src/employees.txt` and writes its reports next to it.

## Layout

- `src/employees.txt` - the input dataset.
- `src/Employee.java`, `src/Departments.java`, `src/Positions.java` - the model.
- `src/Main.java` - reading, the queries, and the report writers.
- `src/tests/` - output captured from earlier runs, kept for comparison.
