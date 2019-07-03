
# Device Name: **iHaper B1A RGB Bulb**

Important Information:
 * device manufacturer : **iHaper**
 * device model : **iHaper Color RGB A19 Light Bulb**
 * device firmware version : **1.0.1**
 * device hardware version : **1.0.1**
 * communication channel : **IP**
 * version of *homekit* library: **0.14.0.**

# Step 1 - discovery

## used command


```python
!python3 -m homekit.discover
```

    Name: TRADFRI gateway._hap._tcp.local.
    Url: http_impl://10.101.0.112:80
    Configuration number (c#): 519
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): FA:1B:E3:A7:9E:6E
    Model Name (md): TRADFRI gateway
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: Philips hue - 2687A7._hap._tcp.local.
    Url: http_impl://10.101.0.120:8080
    Configuration number (c#): 105
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): D6:A6:AF:B9:45:FC
    Model Name (md): BSB002
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: Xiaoyan HC - 789b41._hap._tcp.local.
    Url: http_impl://10.101.0.126:43501
    Configuration number (c#): 32
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 09:8b:8c:6a:31:58
    Model Name (md): xiaoyan home center
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: GLOCO-C152._hap._tcp.local.
    Url: http_impl://10.101.0.84:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 80:A5:89:C0:C1:52
    Model Name (md): GLOCO-500
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Sensor (Id: 10)
    
    Name: iHome SmartMonitor-A289F4._hap._tcp.local.
    Url: http_impl://10.101.0.102:80
    Configuration number (c#): 2
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 6D:3A:28:5E:56:A6
    Model Name (md): iSS50
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Sensor (Id: 10)
    
    Name: iHome SmartPlug-8DDFC4._hap._tcp.local.
    Url: http_impl://10.101.0.82:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 58:8C:E3:77:A5:EA
    Model Name (md): iSP8
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: iHome SmartPlug-8DBA3B._hap._tcp.local.
    Url: http_impl://10.101.0.87:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 83:67:9A:43:9E:49
    Model Name (md): iSP8
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: ConnectSense Outlet 2 01786E._hap._tcp.local.
    Url: http_impl://10.101.0.124:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 17:0F:14:F9:C6:5D
    Model Name (md): CS-SO-2
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: iHome SmartPlug-C4CF6A._hap._tcp.local.
    Url: http_impl://10.101.0.83:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 0E:AA:CE:2B:35:71
    Model Name (md): iSP8
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: iHaper-B1A-0483A0._hap._tcp.local.
    Url: http_impl://10.101.0.116:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B0:8D:54:FD:2B:13
    Model Name (md): B1A
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Koogeek-LS1-1FF6B0._hap._tcp.local.
    Url: http_impl://10.101.0.60:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 8C:DB:AC:08:E5:68
    Model Name (md): LS1
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: LaserEgg2-C42ED9._hap._tcp.local.
    Url: http_impl://10.101.0.88:80
    Configuration number (c#): 2
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 7E:14:DE:BE:17:4A
    Model Name (md): LE-200
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Sensor (Id: 10)
    
    Name: Switch 00041606._hap._tcp.local.
    Url: http_impl://10.101.0.166:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 60:AD:28:14:1D:40
    Model Name (md): IDEV0001
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Switch (Id: 8)
    
    Name: Joshua’s Main Light._hap._tcp.local.
    Url: http_impl://10.101.0.74:80
    Configuration number (c#): 10
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 3C:E0:EE:CC:24:A2
    Model Name (md): LIFX BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: VOCOlinc-LS1-0c657f._hap._tcp.local.
    Url: http_impl://10.101.0.70:80
    Configuration number (c#): 11
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 84:A0:82:FA:A2:02
    Model Name (md): VOCOlinc-LS1-0c657f
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Aqara Hub-A779._hap._tcp.local.
    Url: http_impl://10.101.0.125:4567
    Configuration number (c#): 16
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:E0:B3:76:FD:0F
    Model Name (md): Aqara Hub-1900
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: VOCOlinc-Flowerbud-0d19f1._hap._tcp.local.
    Url: http_impl://10.101.0.133:80
    Configuration number (c#): 14
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): C8:93:D2:13:47:7D
    Model Name (md): VOCOlinc-Flowerbud-0d19f1
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Humidifier (Id: 22)
    
    Name: Games Flood Two._hap._tcp.local.
    Url: http_impl://10.101.0.89:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 56:E3:17:08:12:94
    Model Name (md): LIFX Pls BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: VOCOlinc-PM2-0bbd7c._hap._tcp.local.
    Url: http_impl://10.101.0.79:80
    Configuration number (c#): 12
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): DF:E1:49:D0:38:86
    Model Name (md): VOCOlinc-PM2-0bbd7c
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: Light Panels 50:d2:b7._hap._tcp.local.
    Url: http_impl://10.101.0.73:6517
    Configuration number (c#): 6
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 82:9C:E8:3B:94:EF
    Model Name (md): NL22
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: ArloBaby1A._hap._tcp.local.
    Url: http_impl://10.101.0.171:5051
    Configuration number (c#): 22
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): EA:14:B6:A5:EA:47
    Model Name (md): ABC1000
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: VOCOlinc-L1-0c0c35._hap._tcp.local.
    Url: http_impl://10.101.0.180:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 14:AA:01:0B:F1:B8
    Model Name (md): VOCOlinc-L1-0c0c35
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Games Flood Four._hap._tcp.local.
    Url: http_impl://10.101.0.63:80
    Configuration number (c#): 9
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 13:5D:2B:A5:84:5E
    Model Name (md): LIFX Pls BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: VOCOlinc-PM3-0be650._hap._tcp.local.
    Url: http_impl://10.101.0.77:80
    Configuration number (c#): 19
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:5F:A4:BD:D8:69
    Model Name (md): VOCOlinc-PM3-0be650
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: CviLux-AirPurifier-A0BC._hap._tcp.local.
    Url: http_impl://10.101.0.137:80
    Configuration number (c#): 2
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 2C:85:91:11:99:96
    Model Name (md): FHH106
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Air Purifier (Id: 19)
    
    Name: Healthy Home Coach._hap._tcp.local.
    Url: http_impl://10.101.0.66:5001
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B4:35:6E:AA:39:5D
    Model Name (md): Healthy Home Coach 
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Sensor (Id: 10)
    
    Name: Games Flood One._hap._tcp.local.
    Url: http_impl://10.101.0.90:80
    Configuration number (c#): 8
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): C9:D2:EE:D2:5A:6D
    Model Name (md): LIFX BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Plants._hap._tcp.local.
    Url: http_impl://10.101.0.76:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 70:26:C0:BC:31:7F
    Model Name (md): LIFX Pls BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Omna 180Cam HD - 790D._hap._tcp.local.
    Url: http_impl://10.101.0.92:5011
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B8:00:CC:07:9B:0F
    Model Name (md): DSH-C310
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: MiDeskLampPro-1712._hap._tcp.local.
    Url: http_impl://10.101.0.67:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 8B:19:1B:BE:76:B1
    Model Name (md): MJTD02YL
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Lifx Master Bedroom Strip._hap._tcp.local.
    Url: http_impl://10.101.0.65:80
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 74:54:0F:8C:F7:9A
    Model Name (md): LIFX Z
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: VOCOlinc-L1-0c28cc._hap._tcp.local.
    Url: http_impl://10.101.0.138:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 64:15:00:89:E1:2B
    Model Name (md): VOCOlinc-L1-0c28cc
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Flood  Master Bedroom._hap._tcp.local.
    Url: http_impl://10.101.0.64:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 43:98:C2:91:83:5F
    Model Name (md): LIFX BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: LifX Strip Top._hap._tcp.local.
    Url: http_impl://10.101.0.110:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B6:1B:12:3E:43:B2
    Model Name (md): LIFX Z
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: MiBedsideLamp2-17DD._hap._tcp.local.
    Url: http_impl://10.101.0.108:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): F8:4C:F5:1D:A1:B1
    Model Name (md): MJCTD02YL
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: iHaper-L3-9C5931._hap._tcp.local.
    Url: http_impl://10.101.0.144:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): BE:91:7F:F9:32:4E
    Model Name (md): L3
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Eve Light Strip BC58._hap._tcp.local.
    Url: http_impl://169.254.17.82:80
    Configuration number (c#): 2
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 19:9A:41:EA:25:CF
    Model Name (md): Eve Light Strip 20EAS9901
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: iDevices Outdoor Switch._hap._tcp.local.
    Url: http_impl://10.101.0.104:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): AE:E4:D8:DC:12:2F
    Model Name (md): IDEV0004
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Switch (Id: 8)
    
    Name: Netatmo Welcome._hap._tcp.local.
    Url: http_impl://10.101.0.150:5001
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 67:C5:2B:9E:59:47
    Model Name (md): Welcome
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: My Office LIFX Beam._hap._tcp.local.
    Url: http_impl://10.101.0.106:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): ED:C7:A8:46:62:EA
    Model Name (md): LIFX Beam
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Main Floor._hap._tcp.local.
    Url: http_impl://10.101.0.168:1200
    Configuration number (c#): 14
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 99:2C:C7:72:F0:A2
    Model Name (md): ecobee4
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Thermostat (Id: 9)
    


## result **✔**

```
Name: iHaper-B1A-0483A0._hap._tcp.local.
Url: http_impl://10.101.0.116:80
Configuration number (c#): 1
Feature Flags (ff): Supports HAP Pairing (Flag: 1)
Device ID (id): B0:8D:54:FD:2B:13
Model Name (md): B1A
Protocol Version (pv): 1.1
State Number (s#): 1
Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
Category Identifier (ci): Lightbulb (Id: 5)
```

# Step 2 - unpaired identify
## used command


```python
!python3 -m homekit.identify -d B0:8D:54:FD:2B:13
```

## result **✔ **

iHaper Light Bulb Flashes Flashes

# Step 3 - initialize controller storage

## used command


```python
!python3 -m homekit.init_controller_storage -f ihapercolorbulb
```

## result **✔**

# Step 4 - pairing

## used command


```python
!python3 -m homekit.pair -d B0:8D:54:FD:2B:13 -p 830-02-273 -a Device -f ihapercolorbulb
```

    Pairing for "Device" was established.


## result **✔**

~~~
{
  "Device": {
    "AccessoryPairingID": "B0:8D:54:FD:2B:13",
    "AccessoryLTPK": "72ed9eaaf09558e1ff8dd16701d9727cad5ed07123f15476939569baf2219e97",
    "iOSPairingId": "a78755e4-2144-484b-8529-da655bbf0bb7",
    "iOSDeviceLTSK": "f998334c458c60d3dcff5a1d3183e1ac0acd8a5a33aa1446b546d35ac1df37f2",
    "iOSDeviceLTPK": "4bbec6efec4cf89ddc4e77741e10661408d20f1cb11f89f463b6ca0ad05b5395",
    "AccessoryIP": "10.101.0.116",
    "AccessoryPort": 80,
    "Connection": "IP",
    "accessories": [
      {
        "aid": 1,
        "services": [
          {
            "type": "0000003E-0000-1000-8000-0026BB765291",
            "iid": 1,
            "characteristics": [
              {
                "type": "00000014-0000-1000-8000-0026BB765291",
                "iid": 2,
                "perms": [
                  "pw"
                ],
                "format": "bool"
              },
              {
                "type": "00000020-0000-1000-8000-0026BB765291",
                "iid": 3,
                "perms": [
                  "pr"
                ],
                "value": "iHaper",
                "format": "string"
              },
              {
                "type": "00000021-0000-1000-8000-0026BB765291",
                "iid": 4,
                "perms": [
                  "pr"
                ],
                "value": "B1A",
                "format": "string"
              },
              {
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 5,
                "perms": [
                  "pr"
                ],
                "value": "iHaper-B1A-0483A0",
                "format": "string"
              },
              {
                "type": "00000030-0000-1000-8000-0026BB765291",
                "iid": 6,
                "perms": [
                  "pr"
                ],
                "value": "UNGB021843003731",
                "format": "string"
              },
              {
                "type": "00000052-0000-1000-8000-0026BB765291",
                "iid": 7,
                "perms": [
                  "pr"
                ],
                "value": "1.0.1",
                "format": "string"
              },
              {
                "type": "00000053-0000-1000-8000-0026BB765291",
                "iid": 8,
                "perms": [
                  "pr"
                ],
                "value": "1.0.1",
                "format": "string"
              }
            ]
          },
          {
            "type": "000000A2-0000-1000-8000-0026BB765291",
            "iid": 9,
            "characteristics": [
              {
                "type": "00000037-0000-1000-8000-0026BB765291",
                "iid": 10,
                "perms": [
                  "pr"
                ],
                "value": "1.1.0",
                "format": "string"
              }
            ]
          },
          {
            "type": "00000043-0000-1000-8000-0026BB765291",
            "iid": 11,
            "primary": true,
            "characteristics": [
              {
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 12,
                "perms": [
                  "pr"
                ],
                "value": "Light",
                "format": "string"
              },
              {
                "type": "00000025-0000-1000-8000-0026BB765291",
                "iid": 13,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "value": true,
                "format": "bool"
              },
              {
                "type": "00000008-0000-1000-8000-0026BB765291",
                "iid": 14,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "value": 100,
                "format": "int",
                "unit": "percentage",
                "maxValue": 100,
                "minValue": 0,
                "minStep": 1
              },
              {
                "type": "00000013-0000-1000-8000-0026BB765291",
                "iid": 15,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "value": 0,
                "format": "float",
                "unit": "arcdegrees",
                "maxValue": 360,
                "minValue": 0,
                "minStep": 1
              },
              {
                "type": "0000002F-0000-1000-8000-0026BB765291",
                "iid": 16,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "value": 0,
                "format": "float",
                "unit": "percentage",
                "maxValue": 100,
                "minValue": 0,
                "minStep": 1
              }
            ]
          },
          {
            "type": "151909D0-3802-11E4-916C-0800200C9A66",
            "iid": 17,
            "hidden": true,
            "characteristics": [
              {
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 18,
                "perms": [
                  "pr"
                ],
                "value": "firmware update",
                "format": "string"
              },
              {
                "type": "151909D1-3802-11E4-916C-0800200C9A66",
                "iid": 19,
                "perms": [
                  "pw"
                ],
                "format": "string"
              },
              {
                "type": "151909D6-3802-11E4-916C-0800200C9A66",
                "iid": 20,
                "perms": [
                  "pr",
                  "ev"
                ],
                "value": 0,
                "format": "int",
                "maxValue": 10,
                "minValue": -10,
                "minStep": 1,
                "description": "firmware status"
              }
            ]
          }
        ]
      }
    ]
  }
}
~~~

# Step 5 - paired identify

## used command


```python
!python3 -m homekit.identify -f ihapercolorbulb -a Device
```

## result  **✔**

iHaper Bulb Flashes

# Step 6 - get accessories

## used command


```python
!python3 -m homekit.get_accessories -f ihapercolorbulb -a Device
```

    1.1: >accessory-information<
      1.2:  () >identify< [pw]
      1.3: iHaper () >manufacturer< [pr]
      1.4: B1A () >model< [pr]
      1.5: iHaper-B1A-0483A0 () >name< [pr]
      1.6: UNGB021843003731 () >serial-number< [pr]
      1.7: 1.0.1 () >firmware.revision< [pr]
      1.8: 1.0.1 () >hardware.revision< [pr]
    1.9: >service<
      1.10: 1.1.0 () >version< [pr]
    1.11: >lightbulb<
      1.12: Light () >name< [pr]
      1.13: True () >on< [pr,pw,ev]
      1.14: 100 () >brightness< [pr,pw,ev]
      1.15: 0 () >hue< [pr,pw,ev]
      1.16: 0 () >saturation< [pr,pw,ev]
    1.17: >Unknown Service: 151909D0-3802-11E4-916C-0800200C9A66<
      1.18: firmware update () >name< [pr]
      1.19:  () >Unknown Characteristic 151909D1-3802-11E4-916C-0800200C9A66< [pw]
      1.20: 0 (firmware status) >Unknown Characteristic 151909D6-3802-11E4-916C-0800200C9A66< [pr,ev]


# Step 7 - get characteristics

## used command

Command used to get current power state of bulb 
True == On
False == Off


```python
!python3 -m homekit.get_characteristic -f ihapercolorbulb -a Device -c 1.13
```

    {
        "1.13": {
            "value": true
        }
    }


## result  **✔**

# Step 8 - put characteristics

## used command

Command used to set current power state of bulb 
True == On
False == Off


```python
!python3 -m homekit.put_characteristic -f ihapercolorbulb -a Device -c 1.13 False
```

## result  **✔**

Bulb turned off

# Step 9 - get events

## used command

Note: Ran *python3 -m homekit.put_characteristic -f ihapercolorbulb -a Device -c 1.13 True* from a seperate terminal window to get output. 


```python
!python3 -m homekit.get_events -f ihapercolorbulb -a Device -c 1.13
```

    event for 1.13: True


## result  **✔**

Bulb turned back on

# Step 10 - remove pairing

## used command


```python
!python -m homekit.unpair -f ihapercolorbulb -a Device
```

## result  **✔**
