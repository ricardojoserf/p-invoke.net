## ReadPwrScheme

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool ReadPwrScheme(
   IntPtr UserRootPowerKey,
   ref Guid SchemeGuid,
   ref IntPtr pScheme
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-readpwrscheme)
