## CreateEnvironmentBlock

```csharp
[DllImport("userenv.dll", SetLastError = true)]
public static extern bool CreateEnvironmentBlock(
   out IntPtr lpEnvironment,
   IntPtr hToken,
   bool bInherit
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-createenvironmentblock)
