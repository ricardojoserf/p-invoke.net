## SaferiIsExecutableFileType

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SaferiIsExecutableFileType(
   uint dwCheckFlags,
   IntPtr wzImageFilePath,
   IntPtr dwOutFlags
);
```

Microsoft documentation: (TODO)
