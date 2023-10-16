# NONE-Ask
? (Ask, None-Ask) is a NONE dialect that allows the user to input numbers and strings and calculate basic expressions

## Name
The name "?" or "Ask" refers to the command "?" ("Ask"), with which the user's input can be accessed in "Ask".

## Syntax
The syntax is the same as in NONE, only that there are some additional commands.

```?``` asks for an input, ```!``` outputs an input value.

### Memory system
Ask has a memory for two numbers and one string. A number input always alternately overwrites the memory for the two numbers. So if Number 1 (N1) was last overwritten, Number 2 (N2) will now be overwritten.

### Commands
```+``` after ```?``` or ```!``` stands for a number, ```-``` stands for a string. ```!++``` calls a numerical value, ```!+-``` a calculation.

| ? | Description |
| ------------- | ------------- |
| ?+ | Asks for a number input |
| ?- | Asks for a string input |
| !+ | Returns N1 and N2 |
| !++ | Returns N1 |
| !++- | Returns N2 |
| !+- | Returns N1 + N2 |
| !+-+ | Returns N1 - N2 |
| !+-- | Returns N1 * N2 |
| !+-++ | Returns N1 / N2 |
| !- | Returns the string |

To output the ```!``` values, type ```p``` after the command.

Example: ```!+--p```
