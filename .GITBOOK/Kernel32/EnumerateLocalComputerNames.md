## EnumerateLocalComputerNames

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumerateLocalComputerNames(
   COMPUTER_NAME_FORMAT NameType,
   uint dwFlags,
   ref uint nSize
);
```

