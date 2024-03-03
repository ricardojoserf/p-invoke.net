## SetUserObjectInformation

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetUserObjectInformation(
   IntPtr hObj,
   int nIndex,
   [In] byte[] pvInfo,
   uint cbInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setuserobjectinformationw)
