## GetThreadTimes

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetThreadTimes(
   IntPtr hThread,
   out FILETIME lpCreationTime,
   out FILETIME lpExitTime,
   out FILETIME lpKernelTime,
   out FILETIME lpUserTime
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getthreadtimes)
