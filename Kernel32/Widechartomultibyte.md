## Widechartomultibyte

```csharp
[DllImport("Kernel32.dll", CharSet = CharSet.Ansi, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool WideCharToMultiByte(uint CodePage,
   uint dwFlags,
   [MarshalAs(UnmanagedType.LPWStr)] string lpWideCharStr,
   int cchWideChar,
   [Out,
   MarshalAs(UnmanagedType.LPArray)] byte[] lpMultiByteStr,
   int cbMultiByte,
   IntPtr lpDefaultChar,
   IntPtr lpUsedDefaultChar
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/stringapiset/nf-stringapiset-widechartomultibyte)
