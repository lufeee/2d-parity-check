# 2d parity check

for studing algo

this is now check and correct only 1bit.

## ParityEvenCheck2D
Before
```
{
  {1, 1, 0, 0, 0},
  {0, 0, 1, 1, 1},
  {1, 1, 1, 1, 0},
  {1, 1, 0, 0, 0},
  {1, 1, 0, 1},
}
```
After
```
{
  {1, 1, 0, 0, 0},
  {0, 0, 1, 0, 1},
  {1, 1, 1, 1, 0},
  {1, 1, 0, 0, 0},
  {1, 1, 0, 1},
}
```


## ParityOddCheck2D
Before
```
{
  {1, 1, 0, 0, 0},
  {0, 0, 1, 0, 0},
  {1, 1, 1, 1, 1},
  {1, 1, 0, 0, 1},
  {0, 0, 1, 1},
}
```
After
```
{
  {1, 1, 0, 1, 0},
  {0, 0, 1, 0, 0},
  {1, 1, 1, 1, 1},
  {1, 1, 0, 0, 1},
  {0, 0, 1, 1},
}
```

