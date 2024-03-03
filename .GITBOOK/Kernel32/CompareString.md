## CompareString

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern int CompareString(
   uint Locale,
   uint dwCmpFlags,
   string lpString1,
   int cchCount1,
   string lpString2,
   int cchCount2
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winnls/nf-winnls-comparestring)
