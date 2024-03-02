## memmove

```
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, SetLastError = true)]
public static extern IntPtr memmove(
   IntPtr dest,
   IntPtr src,
   size_t count
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/memmove-wmemmove?view=msvc-170)
