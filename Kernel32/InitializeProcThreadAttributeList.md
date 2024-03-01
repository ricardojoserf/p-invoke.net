## InitializeProcThreadAttributeList

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeProcThreadAttributeList(
   IntPtr lpAttributeList,
   int dwAttributeCount,
   int dwFlags,
   ref IntPtr lpSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-initializeprocthreadattributelist)
