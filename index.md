# Header 1 - Entity Framework Core in Action 2.0 John P Smith
## Basics
### Light (asnotracking) vs default change tracker 
#### 1 light - something
##### 2 default - something
###### 6th level header

![anquie style photo](https://i.pinimg.com/564x/a5/74/74/a574746fc3831b1044009a04a2aedd92.jpg)

```csharp
Enumerable.Range(1,100)
  .Select(x => new { 
     x, 
     -x})
  .ToList()
  .ForEach(x => Console.WriteLine($" x.ToString() "));
```
