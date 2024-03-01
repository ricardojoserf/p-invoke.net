## OleSetMenuDescriptor

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int OleSetMenuDescriptor(
   HMENU hmenuCombined,
   IntPtr hwndFrame,
   IntPtr hwndActiveObject,
   ref OLEMENUGROUPWIDTHS lpMenuWidths
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-olesetmenudescriptor)
