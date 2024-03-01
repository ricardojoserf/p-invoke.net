## CeFindNextRegChange

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool CeFindNextRegChange(
   IntPtr hChange,
   out uint lpdwChangeInfo,
   uint dwTimeout
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/previous-versions/bb416349(v%3Dmsdn.10))
