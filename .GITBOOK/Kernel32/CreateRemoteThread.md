## CreateRemoteThread

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr CreateRemoteThread(
   IntPtr hProcess,
   IntPtr lpThreadAttributes,
   uint dwStackSize,
   IntPtr lpStartAddress,
   IntPtr lpParameter,
   uint dwCreationFlags,
   IntPtr lpThreadId
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-createremotethread)
