# Coin change calculator

**CS50 C exercise** · A CS50 C exercise that finds the minimum number of US quarters, dimes, nickels and pennies for a non-negative amount of cents.

## Build and use

```sh
clang 'Coin Change Calculator.c' -lcs50 -o change
./change
```

The executable uses the example or prompts shown in the source.

## Implementation note

Greedy choice is optimal for these denominations; the input comes from the interactive prompt.

Source: [`Coin Change Calculator.c`](Coin%20Change%20Calculator.c). [License](LICENSE).
