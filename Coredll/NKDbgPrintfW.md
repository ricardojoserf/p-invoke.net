## NKDbgPrintfW

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int NKDbgPrintfW(
   string lpszFormat,
   params object[] args
);
```

