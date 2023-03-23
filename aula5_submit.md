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
π Fname, Lname, Pname, Dno, Hours (σ works_on.Hours > 20 (employee ⨝ Ssn = works_on.Essn ((σ Pname = 'Aveiro Digital' project ) ⨝ Pnumber = Pno works_on)))
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
depCountByEssn = γ Essn; depCount <- count(Essn) (dependent)

depCountMoreThanTwo = σ depCount>2 (depCountByEssn)

EmpMoreThanTwoDeps = (employee) ⨝ Ssn=Essn (depCountMoreThanTwo)

π Fname, Minit, Lname (EmpMoreThanTwoDeps)
```


### *h)* 

```
... Write here your answer ...
```


### *i)* 

```
aveiroProj = σ Plocation='Aveiro' (project)

depsNotInAveiro = department ▷ σ Dlocation='Aveiro' (dept_location)

avProjWithDepNotInAv = aveiroProj ⨝ Dnumber=Dnum depsNotInAveiro

emp_WO_AvPrWDepNIAv = works_on ⨝ Pno=Pnumber (avProjWithDepNotInAv)

fullTable = employee ⨝ Ssn=Essn emp_WO_AvPrWDepNIAv

π Fname, Minit, Lname, Address (fullTable)
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
