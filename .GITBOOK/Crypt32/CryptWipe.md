## CryptWipe

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern void CryptWipe(
   IntPtr pv,
   uint cb
);
```

