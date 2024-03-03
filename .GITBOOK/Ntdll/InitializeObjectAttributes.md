## InitializeObjectAttributes

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void InitializeObjectAttributes(
   ref OBJECT_ATTRIBUTES InitializedAttributes,
   IntPtr ObjectName,
   uint Attributes,
   IntPtr RootDirectory,
   IntPtr SecurityDescriptor
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ntdef/nf-ntdef-initializeobjectattributes)
