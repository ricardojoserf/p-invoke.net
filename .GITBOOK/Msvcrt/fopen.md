## fopen

```csharp
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, CharSet = CharSet.Ansi, SetLastError = true)]
public static extern IntPtr fopen(
   string filename,
   string mode
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/fopen-wfopen?view=msvc-170#:~:text=fopen%20accepts%20paths%20that%20are,at%20the%20time%20of%20execution.)
