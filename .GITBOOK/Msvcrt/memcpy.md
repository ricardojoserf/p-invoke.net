## memcpy

```csharp
[DllImport("msvcrt.dll", CallingConvention = CallingConvention.Cdecl, SetLastError = true)]
public static extern IntPtr memcpy(
   IntPtr dest,
   IntPtr src,
   size_t count
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/cpp/c-runtime-library/reference/memcpy-wmemcpy?view=msvc-170#:~:text=memcpy%20copies%20count%20bytes%20from,memmove%20to%20handle%20overlapping%20regions.&text=Make%20sure%20that%20the%20destination,the%20number%20of%20copied%20characters.)
