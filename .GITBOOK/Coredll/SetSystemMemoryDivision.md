## SetSystemMemoryDivision

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int SetSystemMemoryDivision(
   int dwStorePages,
   int dwRamPages,
   int dwPageSize
);
```

