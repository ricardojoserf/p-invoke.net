## NetFileClose

```csharp
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetFileClose(
   string ServerName,
   uint FileId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netfileclose)
