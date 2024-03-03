## IsTextUnicode

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool IsTextUnicode(
   IntPtr lpBuffer,
   int cb,
   ref int lpi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-istextunicode)
