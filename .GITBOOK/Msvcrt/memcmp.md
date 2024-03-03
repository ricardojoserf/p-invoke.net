## memcmp

```csharp
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, SetLastError = true)]
public static extern int memcmp(
   IntPtr ptr1,
   IntPtr ptr2,
   size_t num
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/memcmp-wmemcmp?view=msvc-170)
