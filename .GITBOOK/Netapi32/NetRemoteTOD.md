## NetRemoteTOD

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetRemoteTOD(
   string UncServerName,
   out IntPtr Buffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/lmremutl/nf-lmremutl-netremotetod)
