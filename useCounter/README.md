# useCounter Hook

## Ejemplo de uso

```
import useCounter from "path/useCounter";
....
const miComponente = () => {
  const { counter, increment, decrement, reset } = useCounter(10);
  ...
};

...
```

También recibe valores por defecto:
```
useCounter();
```