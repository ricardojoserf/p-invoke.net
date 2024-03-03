## NetShareEnum

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetShareEnum(
   string servername,
   uint level,
   out IntPtr Buffer,
   uint prefmaxlen,
   out uint entriesread,
   out uint totalentries,
   ref uint resume_handle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netshareenum)
