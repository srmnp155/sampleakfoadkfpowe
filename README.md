# Calcus

A simple Flask-based calculator API supporting addition, subtraction, multiplication, and division.

## Endpoints

- POST /add
- POST /subtract
- POST /multiply
- POST /divide

Each endpoint expects a JSON payload with two numbers `a` and `b`.

Example:

```
POST /add
{
  "a": 5,
  "b": 3
}
```

Response:

```
{
  "result": 8
}
```
