## CeFindNextRegChange

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeFindNextRegChange(
   IntPtr hChange,
   out uint lpdwChangeInfo,
   uint dwTimeout
);
```

