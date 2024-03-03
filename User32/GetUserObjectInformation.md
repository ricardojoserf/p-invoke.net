## GetUserObjectInformation

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetUserObjectInformation(
   IntPtr hObj,
   int nIndex,
   IntPtr pvInfo,
   uint nLength,
   out uint lpnLengthNeeded
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getuserobjectinformationa)
