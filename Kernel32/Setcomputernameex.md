## Setcomputernameex

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetComputerNameEx(COMPUTER_NAME_FORMAT NameType,
   string lpBuffer
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-setcomputernameexa)
