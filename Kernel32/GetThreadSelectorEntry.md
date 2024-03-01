## GetThreadSelectorEntry

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetThreadSelectorEntry(
   IntPtr hThread,
   uint dwSelector,
   out LDT_ENTRY lpSelectorEntry
);
```

Microsoft documentation: (TODO)
