## ExtEscape

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int ExtEscape(
   IntPtr hdc,
   int nEscape,
   int cbInput,
   IntPtr lpszInData,
   int cbOutput,
   IntPtr lpszOutData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extescape)
