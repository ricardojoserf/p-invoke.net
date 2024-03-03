## GetThreadSelectorEntry

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetThreadSelectorEntry(
   IntPtr hThread,
   uint dwSelector,
   out LDT_ENTRY lpSelectorEntry
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getthreadselectorentry)
