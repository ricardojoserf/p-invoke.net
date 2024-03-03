## BluetoothFindFirstDevice

```csharp
[DllImport("Irprops.dll", SetLastError = true)]
public static extern IntPtr BluetoothFindFirstDevice(
   ref BLUETOOTH_DEVICE_SEARCH_PARAMS pbtdsp,
   ref BLUETOOTH_DEVICE_INFO pbtdi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothfindfirstdevice)
