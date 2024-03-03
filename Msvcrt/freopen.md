## freopen

```csharp
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, CharSet = CharSet.Ansi, SetLastError = true)]
public static extern IntPtr freopen(
   string filename,
   string mode,
   IntPtr stream
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/freopen-wfreopen?view=msvc-170)
