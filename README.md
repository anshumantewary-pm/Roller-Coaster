# Roller Coaster

A beginner Python script that asks for your age and tells you whether you may ride the roller coaster.

## What it does

- **Input:** your age, as a whole number.
- **Logic:** the age is converted to `int`. If it is 18 or more, the rider is allowed; otherwise they are not.
- **Output:** a welcome line, then either `You may go the roller coaster:` or `You may not go the roller coaster:`.

The cut-off is inclusive, so an age of exactly 18 is allowed. Non-integer input (for example `17.5` or `abc`) raises a `ValueError`, since input is not validated.

## Concepts practised

- Reading user input with `input()`
- Type conversion with `int()`
- Comparison operators (`>=`)
- Conditional logic with `if` / `else`
- `print()` output

## How to run

Requires Python 3. The filename contains a space, so quote it:

```bash
python3 "Roller Coaster.py"
```

## Example sessions

```text
welcome to the roller coaster
What is your age?21
You may go the roller coaster:
```

```text
welcome to the roller coaster
What is your age?15
You may not go the roller coaster:
```

## Files

| File | Description |
| --- | --- |
| `Roller Coaster.py` | The age-check script |
| `README.md` | This file |

A beginner Python exercise in input and `if` / `else` decisions.

## Author

Anshuman Tewary · [GitHub](https://github.com/anshumantewary-pm) · [LinkedIn](https://www.linkedin.com/in/tewary-anshuman/)
