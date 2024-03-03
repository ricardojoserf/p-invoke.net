## BluetoothEnumerateInstalledServices

```csharp
[DllImport("Irprops.dll", SetLastError = true)]
public static extern uint BluetoothEnumerateInstalledServices(
   IntPtr hRadio,
   ref BLUETOOTH_DEVICE_INFO pbtdi,
   ref uint pcServices,
   [Out] Guid[] pGuidServices
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothenumerateinstalledservices)
