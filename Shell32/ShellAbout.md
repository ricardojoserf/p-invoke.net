## ShellAbout

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int ShellAbout(
   IntPtr hWnd,
   string szApp,
   string szOtherStuff,
   IntPtr hIcon
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shellaboutw)
