## WSAEnumNameSpaceProviders

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSAEnumNameSpaceProviders(
   ref uint lpdwBufferLength,
   IntPtr lpnspBuffer
);
```

