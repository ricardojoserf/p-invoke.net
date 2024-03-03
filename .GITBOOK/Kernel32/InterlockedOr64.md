## InterlockedOr64

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U8)]
public static extern ulong InterlockedOr64(
   ref long Destination,
   long Value
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winnt/nf-winnt-interlockedor64)
