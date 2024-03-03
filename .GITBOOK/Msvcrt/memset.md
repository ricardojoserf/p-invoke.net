## memset

```csharp
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, SetLastError = true)]
public static extern IntPtr memset(
   IntPtr dest,
   int c,
   size_t count
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/memset-wmemset?view=msvc-170)
