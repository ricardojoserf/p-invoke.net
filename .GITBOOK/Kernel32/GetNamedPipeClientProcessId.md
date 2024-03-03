## GetNamedPipeClientProcessId

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetNamedPipeClientProcessId(
   SafePipeHandle hNamedPipe,
   out uint clientProcessId
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getnamedpipeclientprocessid)
