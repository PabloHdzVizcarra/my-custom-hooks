# useForm

Example:
```
  const initialState = {
    name: '',
    age: 0,
    email: ''
  }
  const [ formValues, handleInputChange, reset ] = useForm(initialState);
```

remember the hook returns the elements as an array [ ] so when you make the destructure of the return don't make mistakes.
