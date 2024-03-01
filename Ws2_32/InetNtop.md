## InetNtop

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern IntPtr InetNtop(
   int Family,
   IntPtr pAddr,
   IntPtr pStringBuf,
   int StringBufSize
);
```

Microsoft documentation: (TODO)
