## Updateprocthreadattribute

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool UpdateProcThreadAttribute(IntPtr lpAttributeList,
   uint dwFlags,
   uint64_t Attribute,
   IntPtr lpValue,
   IntPtr cbSize,
   IntPtr lpPreviousValue,
   IntPtr lpReturnSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-updateprocthreadattribute)
