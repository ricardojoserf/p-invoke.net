## BluetoothSetServiceState

```
[DllImport("Irprops.dll", SetLastError = true)]
public static extern uint BluetoothSetServiceState(
   IntPtr hRadio,
   ref BLUETOOTH_DEVICE_INFO pbtdi,
   ref Guid pGuidService,
   uint dwServiceFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothsetservicestate)
