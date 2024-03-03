## StgSetTimes

```csharp
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgSetTimes(
   [MarshalAs(UnmanagedType.LPWStr)] string lpszName,
   ref FILETIME pctime,
   ref FILETIME patime,
   ref FILETIME pmtime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/coml2api/nf-coml2api-stgsettimes)
