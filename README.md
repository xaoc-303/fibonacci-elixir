# fibonacci-elixir

[![Build Status](https://travis-ci.org/xaoc-303/fibonacci-elixir.svg?branch=master)](https://travis-ci.org/xaoc-303/fibonacci-elixir)

## recursive if-else

| v | # | 30 | 35 | 40 | 45 |
| --- | --- | --- | --- | --- | --- |
| 1.9.2 | [Elixir](./fibo.ex) (compiled) | 0.03089700 | 0.33613100 | 3.82416200 | 40.77350300 |
| | [Total](https://github.com/xaoc-303/fibonacci) | | | | |

## optimization

| v | # | 30 | 35 | 40 | 45 |
| --- | --- | --- | --- | --- | --- |
| 1.9.2 | [Elixir](./fibo.ex) (compiled) | 0.00184500 | 0.00180000 | 0.00181200 | 0.00182200 |
| | [Total](https://github.com/xaoc-303/fibonacci) | | | | |

## run

```
mix escript.build
time ./fibo f1 30
time ./fibo f1t 30
time ./fibo f2 30
time ./fibo f2t 30
```
