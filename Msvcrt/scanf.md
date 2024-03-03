## scanf

```csharp
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, CharSet = CharSet.Ansi, SetLastError = true)]
public static extern int scanf(
   string format,
   params object[] args
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/scanf-scanf-l-wscanf-wscanf-l?view=msvc-170)
