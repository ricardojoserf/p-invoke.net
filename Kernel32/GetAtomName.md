## GetAtomName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetAtomName(
   ushort nAtom,
   StringBuilder lpBuffer,
   int nSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getatomnamew)
