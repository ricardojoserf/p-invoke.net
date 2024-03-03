## NtQueryObject

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryObject(
   IntPtr ObjectHandle,
   OBJECT_INFORMATION_CLASS ObjectInformationClass,
   IntPtr ObjectInformation,
   uint ObjectInformationLength,
   out uint ReturnLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntqueryobject)
