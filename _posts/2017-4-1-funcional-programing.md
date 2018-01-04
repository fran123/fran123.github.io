---
layout: post
title: You're up and running!
---

@FunctionInterface : son interfaces que solo tienen un metodo abstracto (SAM Interfaces) , si se declara mas un metodo el compilador te dará un error , puede tener metodos default
```
@FunctionalInterface 
public interface EmployeeRecordService { 
  public List<Employee> getEmployees(); 
}
```
