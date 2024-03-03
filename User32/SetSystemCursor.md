## SetSystemCursor

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetSystemCursor(
   IntPtr hcur,
   uint id
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setsystemcursor)
