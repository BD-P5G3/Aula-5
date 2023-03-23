# BD: Guião 5


## ​Problema 5.1
 
### *a)*

```
Write here your answer e.g:
π Pname, Pnumber, Ssn, Fname, Minit, Lname (project ⨝ Pnumber=Pno (employee ⨝ Ssn=Essn works_on))
```


### *b)* 

```
π Fname, Minit, Lname (σ Super_ssn=21312332 (employee))
```


### *c)* 

```
π Pname, totalHours ((γ Pno; totalHours <- sum(Hours) (works_on)) ⨝ Pnumber=Pno (project))
```


### *d)* 

```
π Fname (employee ⟕ Ssn=Essn (π Essn, Hours (σ (Pno=1 ∧ Hours>20) (works_on))))
```


### *e)* 

```
π Fname, Minit, Lname (employee ⋉ (π Ssn (employee) - π Essn (works_on)))
```


### *f)* 

```
onlyF = (σ Sex='F' (employee))
fSalaryPerDepartment = γ Dno; averageSalary <- avg(Salary) onlyF

π Dname, averageSalary (department ⨝ Dno=Dnumber fSalaryPerDepartment)
```


### *g)* 

```
... Write here your answer ...
```


### *h)* 

```
... Write here your answer ...
```


### *i)* 

```
... Write here your answer ...
```


## ​Problema 5.2

### *a)*

```
... Write here your answer ...
```

### *b)* 

```
... Write here your answer ...
```


### *c)* 

```
... Write here your answer ...
```


### *d)* 

```
... Write here your answer ...
```


## ​Problema 5.3

### *a)*

```
... Write here your answer ...
```

### *b)* 

```
... Write here your answer ...
```


### *c)* 

```
... Write here your answer ...
```


### *d)* 

```
... Write here your answer ...
```

### *e)* 

```
... Write here your answer ...
```

### *f)* 

```
... Write here your answer ...
```
