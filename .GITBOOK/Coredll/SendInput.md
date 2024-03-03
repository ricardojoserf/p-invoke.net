## SendInput

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern int SendInput(
   int nInputs,
   INPUT[] pInputs,
   int cbSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendinput)
