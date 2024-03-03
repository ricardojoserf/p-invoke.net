## QueryPerformanceCounter

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int QueryPerformanceCounter(
   out long lpPerformanceCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/profileapi/nf-profileapi-queryperformancecounter)
