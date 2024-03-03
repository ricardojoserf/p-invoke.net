## Setconsoletitle

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetConsoleTitle(string lpConsoleTitle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/console/setconsoletitle)
