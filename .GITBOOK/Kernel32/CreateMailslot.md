## CreateMailslot

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeMailslotHandle CreateMailslot(
   string lpName,
   uint nMaxMessageSize,
   uint lReadTimeout,
   IntPtr lpSecurityAttributes
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-createmailslota)
