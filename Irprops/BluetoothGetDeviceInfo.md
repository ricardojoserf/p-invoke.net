## BluetoothGetDeviceInfo

```csharp
[DllImport("Irprops.dll", SetLastError = true)]
public static extern uint BluetoothGetDeviceInfo(
   IntPtr hRadio,
   ref BLUETOOTH_DEVICE_INFO pbtdi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothgetdeviceinfo)
