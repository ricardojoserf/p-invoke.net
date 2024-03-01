## InitializeObjectAttributes

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern void InitializeObjectAttributes(
   ref OBJECT_ATTRIBUTES InitializedAttributes,
   IntPtr ObjectName,
   uint Attributes,
   IntPtr RootDirectory,
   IntPtr SecurityDescriptor
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/wdm/ns-wdm-_object_attributes)
