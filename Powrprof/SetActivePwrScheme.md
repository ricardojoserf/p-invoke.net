## SetActivePwrScheme

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool SetActivePwrScheme(
   IntPtr UserRootPowerKey,
   ref Guid SchemeGuid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-setactivepwrscheme)
