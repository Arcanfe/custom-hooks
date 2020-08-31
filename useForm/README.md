# Readme de useForm

useForm permite organizar la informacion de cualquier formulario a partir de la variable inicial proveida (objeto del formulario con el cual trabaja)

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };
    const [formValues, handleInputChange, reset] = useForm(initialForm);
```

useForm retorna el elemento con el que se trabaja, una funcion para modificar alguna de sus propiedades y una funcion de reseteo de los campos al valor original