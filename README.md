# UE4VehicleBP_t500rs

## 適用の仕方 (How to apply)
- t500rs をつなぐ (Connect t500rs)
- New Project - Blueprint - Vehicle のテンプレートを選択してプロジェクトを作る (New Project - Blueprint - Select Vehicle template and create project)
- Config/DefaultInput.ini を上書きする (Overwrite Config/DefaultInput.ini)

## やったこと (What I have done)
- DefaultInput.ini
    - Raw Input の設定を追加した (Added Raw Input settings)
~~~
[/Script/RawInput.RawInputSettings]
...
+DeviceConfigurations=(VendorID="0x044F",ProductID="0xB65E",AxisProperties=((Key=GenericUSBController_Axis1,Offset=-0.500000),(Key=GenericUSBController_Axis2,bInverted=True,Offset=1.000000),(Key=GenericUSBController_Axis3,bInverted=True,Offset=1.000000),(Key=GenericUSBController_Axis4,bInverted=True,Offset=1.000000),(bEnabled=False,Key=GenericUSBController_Axis5),(bEnabled=False,Key=GenericUSBController_Axis6),(bEnabled=False,Key=GenericUSBController_Axis7),(bEnabled=False,Key=GenericUSBController_Axis8)),ButtonProperties=((Key=GenericUSBController_Button1),(Key=GenericUSBController_Button2),(Key=GenericUSBController_Button3),(Key=GenericUSBController_Button4),(Key=GenericUSBController_Button5),(Key=GenericUSBController_Button6),(Key=GenericUSBController_Button7),(Key=GenericUSBController_Button8),(Key=GenericUSBController_Button9),(Key=GenericUSBController_Button10),(Key=GenericUSBController_Button11),(Key=GenericUSBController_Button12),(Key=GenericUSBController_Button13),(Key=GenericUSBController_Button14),(Key=GenericUSBController_Button15),(Key=GenericUSBController_Button16),(Key=GenericUSBController_Button17),(Key=GenericUSBController_Button18),(Key=GenericUSBController_Button19),(Key=GenericUSBController_Button20)))
~~~
