## ExpandEnvironmentStrings

```csharp
[DllImport("kernel32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern uint ExpandEnvironmentStringsA(string lpSrc,
   StringBuilder lpDst,
   uint nSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/processenv/nf-processenv-expandenvironmentstringsa)
