## UuidFromStringA

```csharp
[DllImport("rpcrt4.dll", SetLastError = true)]
public static extern int UuidFromStringA(
   byte[] StringUuid,
   out Guid Uuid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/rpcdce/nf-rpcdce-uuidfromstringa)
