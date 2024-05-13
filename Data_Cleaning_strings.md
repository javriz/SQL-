# Data Cleaning Strings SQL

## Basic steps 
## 1. Capitalization 

``` 
select initcap('string');
```

## 2. Uniform lenght of the string
  Lpad('string' , length_required, fill_with)
```
select lpad('123',5,0);
```
## 3. Remove extra spaces from the string
replace('string', to_replace, replace_with)
```
select replace('string',' / ' , '/');
```

