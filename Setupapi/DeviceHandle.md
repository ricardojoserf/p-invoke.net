## DeviceHandle

```csharp
[DllImport("setupapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr DeviceHandle(
   IntPtr DeviceInfoSet,
   ref DeviceInterfaceData InterfaceData,
   IntPtr DeviceInstancePath,
   uint Flags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dxva2api/nf-dxva2api-idirect3ddevicemanager9-opendevicehandle)
