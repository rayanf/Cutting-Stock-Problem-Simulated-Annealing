# Cutting-Stock-Problem-Simulated-Annealing
Solving the Cutting Stock Problem via implementing Simulated Annealing.

## Usage
Just define your function and call Problem class with your parametrs, and then train it.
```python
solve = Problem(T = 1
            , coolingRate = 0.9
            , stockLength = stockLength
            , markovLength = 3
            , orders = req
            , stopCriterion = 1000)
rolls, ans = solve.train()
```

## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
