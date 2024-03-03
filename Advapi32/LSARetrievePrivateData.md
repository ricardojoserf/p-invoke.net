## LSARetrievePrivateData

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint LSARetrievePrivateData(
   IntPtr PolicyHandle,
   ref LSA_UNICODE_STRING KeyName,
   out IntPtr PrivateData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/ntsecapi/nf-ntsecapi-lsaretrieveprivatedata)
