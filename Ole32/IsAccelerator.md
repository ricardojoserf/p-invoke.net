## IsAccelerator

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int IsAccelerator(
   IUnknown pAccel,
   uint cAccelEntries,
   [MarshalAs(
   UnmanagedType.LPArray)] uint[] lpMsg,
   out uint lpwCmd
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/oleidl/nf-oleidl-isaccelerator)
