## BluetoothGetRadioInfo

```csharp
[DllImport("Irprops.dll", SetLastError = true)]
public static extern uint BluetoothGetRadioInfo(
   IntPtr hRadio,
   ref BLUETOOTH_RADIO_INFO pRadioInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/bluetoothapis/nf-bluetoothapis-bluetoothgetradioinfo)
