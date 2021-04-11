# useFetch Hook

## Ejemplo de uso

```
import useFetch from "path/useFetch";
....
const miComponente = () => {
  // Endpoint API
  const url = "https://domain.com/api/posts";

  const { data: null, loading: true, error: null } = useFetch(url);
  ...
};

...
```