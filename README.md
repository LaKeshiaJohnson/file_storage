# file_storage
NSS Ruby exercise 13

## Car Models
Use Ruby to build a console app that interacts with two files:

1. `car-makes`
2. `car-models`

### Car Makes
This file should contain just the names of several makes.
```
Toyota
Nissan
...
```

### Car Models
```
{first letter of make}={model name}
```

```
T=Camry
N=Altima
...
```

### Requirements

1. Create a single class that implements all functionality.
2. Create a method for reading the car makes file.
3. Create a method for reading the car models file.
4. Create a method that invokes the previous two methods and generates a hash.
	* The hash keys will be the make names.
	* The value for each key will be a list of model names.

```
{
    "Toyota" => ["Camry"],
    ...
}
```