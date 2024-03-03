## ExtEscape

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int ExtEscape(
   IntPtr hdc,
   int iEscape,
   int cjInput,
   IntPtr lpInData,
   int cjOutput,
   IntPtr lpOutData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-extescape)
