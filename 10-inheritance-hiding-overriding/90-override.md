# override

- use `virtual` and `override`
- `override` is extension
- `override` is optional

```
public override string GetAmount(){
    base.GetAmount();
    return "Amount" + 1500;
}
```

# override vs. hide method

- hide method do NOT call parent method
- override call parent method and extend the method
