## GetActivePwrScheme

```csharp
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool GetActivePwrScheme(
   IntPtr UserRootPowerKey,
   ref IntPtr ActivePolicyGuid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-getactivepwrscheme)
