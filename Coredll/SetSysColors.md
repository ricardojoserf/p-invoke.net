## SetSysColors

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool SetSysColors(
   int cElements,
   int[] lpaElements,
   int[] lpaRgbValues
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setsyscolors)
