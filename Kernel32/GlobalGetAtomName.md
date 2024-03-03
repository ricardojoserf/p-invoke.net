## GlobalGetAtomName

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GlobalGetAtomName(
   ushort nAtom,
   StringBuilder lpBuffer,
   int nSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-globalgetatomnamew)
