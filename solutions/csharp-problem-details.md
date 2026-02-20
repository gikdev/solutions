# C# Problem Details

```cs
builder.Services.AddExceptionHandler<GlobalExceptionHandler>();
builder.Services.AddProblemDetails();
// then
app.UseExceptionHandler();
app.UseStatusCodePages();
```
