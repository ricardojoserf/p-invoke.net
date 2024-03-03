## NetUseAdd

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUseAdd(
   string UncServerName,
   uint Level,
   ref USE_INFO_2 Buf,
   out uint ParmError
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmuse/nf-lmuse-netuseadd)
