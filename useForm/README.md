# useForm Hook

## Ejemplo de uso

```
import useForm from "path/useForm";
....
const miComponente = () => {

  // No debe ser exactamente asi pero es un ejemplo de estado inicial:
  const initialForm = {
    name: "",
    email: "",
    age: 0,
    active: false
  };

  const [ formValues, handleInputChange, reset ] = useForm(initialForm);

  ...

};

...
```