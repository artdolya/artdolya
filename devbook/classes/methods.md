# Methods
## Methods with multiple arguments

### C#
```csharp
public double Summ(params double[] values)
{
    double result = 0;
    foreach(double val in values)
    {
        result += val;
    }
    return result; 
}
```

### JAVA
```java
public double Summ(double... values)
{
    double result = 0;
    for(double val: values)
    {
        result += val;
    }
    return result; 
}
```
