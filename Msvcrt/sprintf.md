## sprintf

```
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, CharSet = CharSet.Ansi, SetLastError = true)]
public static extern int sprintf(
   IntPtr buffer,
   string format,
   params object[] args
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/cpp/c-runtime-library/reference/sprintf-sprintf-s)
