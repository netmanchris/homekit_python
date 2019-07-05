
# Device Name: **iHome iSS50 Multi Sensor**

Important Information:
 * device manufacturer : **iHome**
 * device model : **iSS50 Multi Sensor**
 * device firmware version : **1.3.8**
 * device hardware version : **0.1**
 * communication channel : **IP**
 * version of *homekit* library: **0.14.0.**

# Step 1 - discovery

## used command


```python
!python3 -m homekit.discover
```

    Name: Brid Air Purifier-052F40._hap._tcp.local.
    Url: http_impl://10.101.30.42:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 30:1B:2B:7B:3B:50
    Model Name (md): Brid Filter
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Air Purifier (Id: 19)
    
    Name: iHome SmartMonitor-A289F4._hap._tcp.local.
    Url: http_impl://10.101.30.37:80
    Configuration number (c#): 2
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 6D:3A:28:5E:56:A6
    Model Name (md): iSS50
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
    Category Identifier (ci): Sensor (Id: 10)
    
    Name: Koogeek-O1US-917363._hap._tcp.local.
    Url: http_impl://10.101.30.31:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 88:F1:F6:7A:38:F3
    Model Name (md): O1US
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: Xiaoyan HC - 789b41._hap._tcp.local.
    Url: http_impl://10.101.0.126:42797
    Configuration number (c#): 32
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 09:8b:8c:6a:31:58
    Model Name (md): xiaoyan home center
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: Omna 180Cam HD - 790D._hap._tcp.local.
    Url: http_impl://10.101.30.41:5011
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B8:00:CC:07:9B:0F
    Model Name (md): DSH-C310
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: Smart Bridge 2._hap._tcp.local.
    Url: http_impl://10.101.30.127:4548
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 86:dc:1c:6d:4c:5c
    Model Name (md): Smart Bridge 2
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: Aqara Hub-A779 11._hap._tcp.local.
    Url: http_impl://10.101.30.88:4567
    Configuration number (c#): 16
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:E0:B3:76:FD:0F
    Model Name (md): Aqara Hub-1900
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: Games Flood Four._hap._tcp.local.
    Url: http_impl://10.101.30.30:80
    Configuration number (c#): 9
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 13:5D:2B:A5:84:5E
    Model Name (md): LIFX Pls BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: My Office LIFX Beam._hap._tcp.local.
    Url: http_impl://10.101.30.12:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): ED:C7:A8:46:62:EA
    Model Name (md): LIFX Beam
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: iHome SmartPlug-8DDFC4._hap._tcp.local.
    Url: http_impl://10.101.30.74:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 58:8C:E3:77:A5:EA
    Model Name (md): iSP8
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: iHome SmartPlug-C4CF6A._hap._tcp.local.
    Url: http_impl://10.101.30.24:80
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 0E:AA:CE:2B:35:71
    Model Name (md): iSP8
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: TRADFRI gateway._hap._tcp.local.
    Url: http_impl://10.101.30.129:80
    Configuration number (c#): 520
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): CD:66:9B:8C:72:39
    Model Name (md): TRADFRI gateway
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: ConnectSense Outlet 2 01786E._hap._tcp.local.
    Url: http_impl://10.101.30.26:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 17:0F:14:F9:C6:5D
    Model Name (md): CS-SO-2
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: Games Flood One._hap._tcp.local.
    Url: http_impl://10.101.30.58:80
    Configuration number (c#): 8
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): C9:D2:EE:D2:5A:6D
    Model Name (md): LIFX BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: LIX Tiles._hap._tcp.local.
    Url: http_impl://10.101.30.180:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): C8:3A:A5:FD:DA:10
    Model Name (md): LIFX Tile
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: iHaper-L3-9C5931._hap._tcp.local.
    Url: http_impl://10.101.30.83:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): BE:91:7F:F9:32:4E
    Model Name (md): L3
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Netatmo Welcome._hap._tcp.local.
    Url: http_impl://10.101.30.39:5001
    Configuration number (c#): 5
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): EB:30:84:4C:A6:DA
    Model Name (md): Welcome
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: Logi Circle._hap._tcp.local.
    Url: http_impl://10.101.30.38:8080
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): E2:3E:22:29:A8:2A
    Model Name (md): V-R0008
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: VOCOlinc-Flowerbud-0d239e._hap._tcp.local.
    Url: http_impl://10.101.30.191:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 3F:EB:2F:CD:AE:2A
    Model Name (md): VOCOlinc-Flowerbud-0d239e
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Humidifier (Id: 22)
    
    Name: VOCOlinc-PM2-0bbd7c._hap._tcp.local.
    Url: http_impl://10.101.30.148:80
    Configuration number (c#): 13
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): DF:E1:49:D0:38:86
    Model Name (md): VOCOlinc-PM2-0bbd7c
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: Games Flood Two._hap._tcp.local.
    Url: http_impl://10.101.30.16:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 56:E3:17:08:12:94
    Model Name (md): LIFX Pls BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Healthy Home Coach._hap._tcp.local.
    Url: http_impl://10.101.30.48:5001
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B4:35:6E:AA:39:5D
    Model Name (md): Healthy Home Coach 
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Sensor (Id: 10)
    
    Name: MiDeskLampPro-1712._hap._tcp.local.
    Url: http_impl://10.101.30.93:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 8B:19:1B:BE:76:B1
    Model Name (md): MJTD02YL
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Flood  Master Bedroom._hap._tcp.local.
    Url: http_impl://10.101.30.54:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 43:98:C2:91:83:5F
    Model Name (md): LIFX BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Canvas 6A54._hap._tcp.local.
    Url: http_impl://10.101.30.76:6517
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 57:C8:27:4B:E7:33
    Model Name (md): NL29
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: VOCOlinc-LS1-0c657f._hap._tcp.local.
    Url: http_impl://10.101.30.138:80
    Configuration number (c#): 13
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 84:A0:82:FA:A2:02
    Model Name (md): VOCOlinc-LS1-0c657f
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Light Panels 50:d2:b7._hap._tcp.local.
    Url: http_impl://10.101.30.15:6517
    Configuration number (c#): 6
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 82:9C:E8:3B:94:EF
    Model Name (md): NL22
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Philips hue - 2687A7._hap._tcp.local.
    Url: http_impl://10.101.30.137:8080
    Configuration number (c#): 6
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): E6:B6:C2:9C:85:E5
    Model Name (md): BSB002
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
    Name: Plants._hap._tcp.local.
    Url: http_impl://10.101.30.22:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 70:26:C0:BC:31:7F
    Model Name (md): LIFX Pls BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Lifx Master Bedroom Strip._hap._tcp.local.
    Url: http_impl://10.101.30.85:80
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 74:54:0F:8C:F7:9A
    Model Name (md): LIFX Z
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Eve Light Strip 8606._hap._tcp.local.
    Url: http_impl://10.101.30.18:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 69:3A:2E:97:6E:3E
    Model Name (md): Eve Light Strip 20EAS9901
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: ArloBaby1A._hap._tcp.local.
    Url: http_impl://10.101.30.72:5051
    Configuration number (c#): 22
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): EA:14:B6:A5:EA:47
    Model Name (md): ABC1000
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): IP Camera (Id: 17)
    
    Name: LifX Strip Top._hap._tcp.local.
    Url: http_impl://10.101.30.60:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): B6:1B:12:3E:43:B2
    Model Name (md): LIFX Z
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: VOCOlinc-PM3-0be650._hap._tcp.local.
    Url: http_impl://10.101.30.188:80
    Configuration number (c#): 20
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:5F:A4:BD:D8:69
    Model Name (md): VOCOlinc-PM3-0be650
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Outlet (Id: 7)
    
    Name: MiBedsideLamp2-17DD._hap._tcp.local.
    Url: http_impl://10.101.30.68:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): F8:4C:F5:1D:A1:B1
    Model Name (md): MJCTD02YL
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Main Floor._hap._tcp.local.
    Url: http_impl://10.101.30.45:1200
    Configuration number (c#): 14
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 99:2C:C7:72:F0:A2
    Model Name (md): ecobee4
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Thermostat (Id: 9)
    
    Name: Eve Light Strip BC58._hap._tcp.local.
    Url: http_impl://10.101.30.17:80
    Configuration number (c#): 2
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 19:9A:41:EA:25:CF
    Model Name (md): Eve Light Strip 20EAS9901
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    
    Name: Joshua’s Main Light._hap._tcp.local.
    Url: http_impl://10.101.30.57:80
    Configuration number (c#): 10
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 3C:E0:EE:CC:24:A2
    Model Name (md): LIFX BR30
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Lightbulb (Id: 5)
    


## result **✔**

```
Name: iHome SmartMonitor-A289F4._hap._tcp.local.
Url: http_impl://10.101.30.37:80
Configuration number (c#): 2
Feature Flags (ff): Supports HAP Pairing (Flag: 1)
Device ID (id): 6D:3A:28:5E:56:A6
Model Name (md): iSS50
Protocol Version (pv): 1.0
State Number (s#): 1
Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
Category Identifier (ci): Sensor (Id: 10)
```

# Step 2 - unpaired identify
## used command


```python
!python3 -m homekit.identify -d 6D:3A:28:5E:56:A6
```

## result **✔ **

iHome iSS50 Multi sensor screen flashes

# Step 3 - initialize controller storage

## used command


```python
!python3 -m homekit.init_controller_storage -f iHome
```

## result **✔**

# Step 4 - pairing

## used command


```python
!python3 -m homekit.pair -d 6D:3A:28:5E:56:A6 -p 555-55-555 -a sensor -f iHome
```

    Pairing for "sensor" was established.


## result **✔**

```
{
  "sensor": {
    "AccessoryPairingID": "6D:3A:28:5E:56:A6",
    "AccessoryLTPK": "e1730be3481fa3da02b6a7f3ba950bdcd09f5e32c9bac49ded8cbeb9f2126ad0",
    "iOSPairingId": "8099f71c-5b31-4b3c-ad2c-40eb4fb4322c",
    "iOSDeviceLTSK": "5c141077a5b2c9766d483e4ecf40c0d686ebc6329fbd51f6bd0b7c7ce2a19210",
    "iOSDeviceLTPK": "476b3ddfb2f88a91efaddba4946f16cba9eb38757f60aeba5786a53dfb228bf0",
    "AccessoryIP": "10.101.30.37",
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
                "iid": 2,
                "value": "iHome SmartMonitor-A289F4",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 3,
                "value": "SDI Technologies",
                "format": "string",
                "maxLen": 64,
                "type": "00000020-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 4,
                "value": "iSS50",
                "format": "string",
                "maxLen": 64,
                "type": "00000021-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 5,
                "value": "08531360040000289555",
                "format": "string",
                "maxLen": 64,
                "type": "00000030-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 6,
                "format": "bool",
                "type": "00000014-0000-1000-8000-0026BB765291",
                "perms": [
                  "pw"
                ]
              },
              {
                "iid": 7,
                "value": "1.3.8",
                "format": "string",
                "type": "00000052-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              }
            ]
          },
          {
            "type": "00000082-0000-1000-8000-0026BB765291",
            "iid": 8,
            "characteristics": [
              {
                "iid": 9,
                "value": 43.0,
                "format": "float",
                "minValue": 0.0,
                "maxValue": 100.0,
                "minStep": 1.0,
                "type": "00000010-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 10,
                "value": "Humidity Sensor",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              }
            ]
          },
          {
            "type": "00000084-0000-1000-8000-0026BB765291",
            "iid": 11,
            "characteristics": [
              {
                "iid": 12,
                "value": 411.0,
                "format": "float",
                "minValue": 0.0001,
                "maxValue": 100000.0,
                "type": "0000006B-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 13,
                "value": "Light Sensor",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 14,
                "value": true,
                "format": "bool",
                "description": "Light Detected",
                "type": "AF55B701-6EE1-4786-B8EB-AC25668C4517",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 15,
                "value": 20.0,
                "format": "float",
                "description": "Ambient Light Detection Trigger Treshold",
                "minValue": 0.0001,
                "maxValue": 100000.0,
                "type": "56B376D9-48A7-4AC9-9B49-92C3F24206C4",
                "perms": [
                  "pr",
                  "pw"
                ]
              }
            ]
          },
          {
            "type": "00000085-0000-1000-8000-0026BB765291",
            "iid": 16,
            "characteristics": [
              {
                "iid": 17,
                "value": false,
                "format": "bool",
                "type": "00000022-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 18,
                "value": "Motion Sensor",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              }
            ]
          },
          {
            "type": "0000008A-0000-1000-8000-0026BB765291",
            "iid": 19,
            "characteristics": [
              {
                "iid": 20,
                "value": 26.79999,
                "format": "float",
                "minValue": 0.0,
                "maxValue": 100.0,
                "minStep": 0.1,
                "type": "00000011-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 21,
                "value": "Temperature Sensor",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              }
            ]
          },
          {
            "type": "681DCD9E-3E92-4308-B46C-0F3DC4A1A25A",
            "iid": 22,
            "characteristics": [
              {
                "iid": 23,
                "value": "Sound Detector",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 24,
                "value": false,
                "format": "bool",
                "description": "Sound Detected",
                "type": "B4AA28DF-1970-49D5-8655-B881892D4339",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              }
            ]
          },
          {
            "type": "CFC67791-48F2-4382-ACBE-294196CF5B70",
            "iid": 25,
            "characteristics": [
              {
                "iid": 26,
                "value": "Sensor Configuration Service",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 27,
                "value": 3,
                "format": "int",
                "description": "Sound Detection Trigger Threshold",
                "minValue": 3,
                "maxValue": 200,
                "minStep": 1,
                "type": "298A64ED-9BD6-4ADE-9697-F180CEACE5C4",
                "perms": [
                  "pr",
                  "pw"
                ]
              },
              {
                "iid": 28,
                "value": 0,
                "format": "uint8",
                "minValue": 0,
                "maxValue": 1,
                "minStep": 1,
                "type": "00000036-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 29,
                "value": 30,
                "format": "int",
                "description": "Sound Detector Silence Duration",
                "minValue": 1,
                "maxValue": 120,
                "minStep": 1,
                "type": "BA8D7756-3F81-4E56-976C-9BBA88683600",
                "perms": [
                  "pr",
                  "pw"
                ]
              },
              {
                "iid": 30,
                "value": 30,
                "format": "int",
                "description": "Motion Detector Silence Duration",
                "minValue": 1,
                "maxValue": 120,
                "minStep": 1,
                "type": "B0FABCF0-8911-41BC-9159-CB0323E3D49D",
                "perms": [
                  "pr",
                  "pw"
                ]
              },
              {
                "iid": 31,
                "value": "kABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAA=",
                "format": "string",
                "description": "iSS50 Diagnostics",
                "maxLen": 128,
                "type": "37EC0441-060C-4794-96AC-F8124BE019FE",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              }
            ]
          },
          {
            "type": "151909D0-3802-11E4-916C-0800200C9A66",
            "iid": 32,
            "characteristics": [
              {
                "iid": 33,
                "value": "url",
                "format": "string",
                "description": "FW Upgrade supported types",
                "type": "151909D2-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 34,
                "format": "string",
                "description": "FW Upgrade URL",
                "maxLen": 256,
                "type": "151909D1-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pw"
                ]
              },
              {
                "iid": 35,
                "value": 0,
                "format": "int",
                "description": "FW Upgrade Status",
                "type": "151909D6-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              }
            ]
          },
          {
            "type": "151BF015-3802-11E4-916C-0800200C9A66",
            "iid": 36,
            "characteristics": [
              {
                "iid": 37,
                "value": "Cloud Credentials Service",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 38,
                "format": "string",
                "description": "Cloud API Key",
                "maxLen": 81,
                "type": "151BF016-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pw"
                ]
              },
              {
                "iid": 39,
                "format": "string",
                "description": "Cloud Thing ID",
                "maxLen": 25,
                "type": "151BF017-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pw"
                ]
              },
              {
                "iid": 40,
                "value": false,
                "format": "bool",
                "description": "Non-iOS Cloud config",
                "type": "151BF013-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 41,
                "value": 0,
                "format": "int",
                "description": "Cloud Status",
                "minValue": -2,
                "maxValue": 1,
                "type": "151BF014-3802-11E4-916C-0800200C9A66",
                "perms": [
                  "pr"
                ]
              }
            ]
          },
          {
            "type": "5C14BE69-B86D-4B3B-B31A-996C020C3B69",
            "iid": 42,
            "characteristics": [
              {
                "iid": 43,
                "value": "Inactivity Detector Service",
                "format": "string",
                "maxLen": 64,
                "type": "00000023-0000-1000-8000-0026BB765291",
                "perms": [
                  "pr"
                ]
              },
              {
                "iid": 44,
                "value": false,
                "format": "bool",
                "description": "Motion Detector Silent for Configured Duration",
                "type": "7096DF31-1B02-48BA-9DB6-03C00353DE49",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              },
              {
                "iid": 45,
                "value": false,
                "format": "bool",
                "description": "Sound Detector Silent for Configured Duration",
                "type": "868A6FAD-AC7A-4249-B0E1-74E7BB8BECCD",
                "perms": [
                  "pr",
                  "ev"
                ],
                "ev": false
              }
            ]
          }
        ]
      }
    ]
  }
}
```

# Step 5 - paired identify

## used command


```python
!python3 -m homekit.identify -f iHome -a sensor
```

## result  **✔**

iHome iSS50 Multi Sensor screen flashes

# Step 6 - get accessories

## used command


```python
!python3 -m homekit.get_accessories -f iHome -a sensor
```

    1.1: >accessory-information<
      1.2: iHome SmartMonitor-A289F4 () >name< [pr]
      1.3: SDI Technologies () >manufacturer< [pr]
      1.4: iSS50 () >model< [pr]
      1.5: 08531360040000289555 () >serial-number< [pr]
      1.6:  () >identify< [pw]
      1.7: 1.3.8 () >firmware.revision< [pr]
    1.8: >humidity<
      1.9: 44.0 () >relative-humidity.current< [pr,ev]
      1.10: Humidity Sensor () >name< [pr]
    1.11: >light<
      1.12: 411.0 () >light-level.current< [pr,ev]
      1.13: Light Sensor () >name< [pr]
      1.14: True (Light Detected) >Unknown Characteristic AF55B701-6EE1-4786-B8EB-AC25668C4517< [pr,ev]
      1.15: 20.0 (Ambient Light Detection Trigger Treshold) >Unknown Characteristic 56B376D9-48A7-4AC9-9B49-92C3F24206C4< [pr,pw]
    1.16: >motion<
      1.17: False () >motion-detected< [pr,ev]
      1.18: Motion Sensor () >name< [pr]
    1.19: >temperature<
      1.20: 26.7 () >temperature.current< [pr,ev]
      1.21: Temperature Sensor () >name< [pr]
    1.22: >Unknown Service: 681DCD9E-3E92-4308-B46C-0F3DC4A1A25A<
      1.23: Sound Detector () >name< [pr]
      1.24: False (Sound Detected) >Unknown Characteristic B4AA28DF-1970-49D5-8655-B881892D4339< [pr,ev]
    1.25: >Unknown Service: CFC67791-48F2-4382-ACBE-294196CF5B70<
      1.26: Sensor Configuration Service () >name< [pr]
      1.27: 3 (Sound Detection Trigger Threshold) >Unknown Characteristic 298A64ED-9BD6-4ADE-9697-F180CEACE5C4< [pr,pw]
      1.28: 0 () >temperature.units< [pr,pw,ev]
      1.29: 30 (Sound Detector Silence Duration) >Unknown Characteristic BA8D7756-3F81-4E56-976C-9BBA88683600< [pr,pw]
      1.30: 30 (Motion Detector Silence Duration) >Unknown Characteristic B0FABCF0-8911-41BC-9159-CB0323E3D49D< [pr,pw]
      1.31: kABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAA= (iSS50 Diagnostics) >Unknown Characteristic 37EC0441-060C-4794-96AC-F8124BE019FE< [pr,ev]
    1.32: >Unknown Service: 151909D0-3802-11E4-916C-0800200C9A66<
      1.33: url (FW Upgrade supported types) >Unknown Characteristic 151909D2-3802-11E4-916C-0800200C9A66< [pr]
      1.34:  (FW Upgrade URL) >Unknown Characteristic 151909D1-3802-11E4-916C-0800200C9A66< [pw]
      1.35: 0 (FW Upgrade Status) >Unknown Characteristic 151909D6-3802-11E4-916C-0800200C9A66< [pr,ev]
    1.36: >Unknown Service: 151BF015-3802-11E4-916C-0800200C9A66<
      1.37: Cloud Credentials Service () >name< [pr]
      1.38:  (Cloud API Key) >Unknown Characteristic 151BF016-3802-11E4-916C-0800200C9A66< [pw]
      1.39:  (Cloud Thing ID) >Unknown Characteristic 151BF017-3802-11E4-916C-0800200C9A66< [pw]
      1.40: False (Non-iOS Cloud config) >Unknown Characteristic 151BF013-3802-11E4-916C-0800200C9A66< [pr]
      1.41: 0 (Cloud Status) >Unknown Characteristic 151BF014-3802-11E4-916C-0800200C9A66< [pr]
    1.42: >Unknown Service: 5C14BE69-B86D-4B3B-B31A-996C020C3B69<
      1.43: Inactivity Detector Service () >name< [pr]
      1.44: False (Motion Detector Silent for Configured Duration) >Unknown Characteristic 7096DF31-1B02-48BA-9DB6-03C00353DE49< [pr,ev]
      1.45: False (Sound Detector Silent for Configured Duration) >Unknown Characteristic 868A6FAD-AC7A-4249-B0E1-74E7BB8BECCD< [pr,ev]


# Step 7 - get characteristics

## used command


```python
!python3 -m homekit.get_characteristic -f iHome -a sensor -c 1.2
```

    {
        "1.2": {
            "value": "iHome SmartMonitor-A289F4"
        }
    }


## result  **✔**

# Step 8 - put characteristics

## used command

Not applicable for this device


```python

```

## result  **✔**

Not applicable for this device

# Step 9 - get events

## used command

Note: Waved hand in front of motion sensor


```python
!python3 -m homekit.get_events -f iHome -a sensor -c 1.17
```

    event for 1.17: True
    event for 1.17: False
    event for 1.17: False
    ^C


## result  **✔**

# Step 10 - remove pairing

## used command


```python
!python -m homekit.unpair -f iHome -a sensor
```

    Pairing for "sensor" was removed.


## result  **✔**
