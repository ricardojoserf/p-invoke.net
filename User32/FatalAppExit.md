## FatalAppExit

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern void FatalAppExitA(uint uAction,
   string lpMessageText
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/errhandlingapi/nf-errhandlingapi-fatalappexita)
