## GetCurrentHwProfile

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetCurrentHwProfile(
   ref HARDWARE_PROFILE lpHwProfileInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getcurrenthwprofilea)
