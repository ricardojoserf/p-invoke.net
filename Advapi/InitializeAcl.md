## InitializeAcl

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeAcl(
   IntPtr pAcl,
   uint nAclLength,
   uint dwAclRevision
);
```

Microsoft documentation: (TODO)
