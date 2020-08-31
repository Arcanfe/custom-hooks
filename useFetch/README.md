# Readme de useFetch

useFetch permite realizar el llamado a cualquier API, a partir de la url proveida

Ejemplo de uso:
```
    const url = 'http://endpointdeAPI.abc';
    const {data: null, loading: true, error: null} = useFetch(url);
```

useFetch retorna la data obtenida, un booleano que indica si termino o no de realizar la llamada, y si obtuvo algun error