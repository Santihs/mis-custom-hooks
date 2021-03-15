# useForm

Ejemplo:
```
    const initialForm = {
        name: 'santiago',
        edad: 0,
        email: 'santihs.sanchez@gmail.com'
    }
    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```