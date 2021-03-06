
# Device Name: **LIFX Tiles**

Important Information:
 * device manufacturer : **LIFX**
 * device model : **LIFX Tiles**
 * device firmware version : **3.50**
 * device hardware version : **1.0**
 * communication channel : **IP**
 * version of *homekit* library: **0.14.0.**

# Step 1 - discovery

## used command


```python
!python3 -m homekit.discover
```

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
    
    Name: VOCOlinc-PM3-0be650._hap._tcp.local.
    Url: http_impl://10.101.30.145:80
    Configuration number (c#): 20
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:5F:A4:BD:D8:69
    Model Name (md): VOCOlinc-PM3-0be650
    Protocol Version (pv): 1.1
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
    
    Name: Philips hue - 2687A7._hap._tcp.local.
    Url: http_impl://10.101.30.137:8080
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): E6:B6:C2:9C:85:E5
    Model Name (md): BSB002
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
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
    
    Name: VOCOlinc-Flowerbud-0d19f1._hap._tcp.local.
    Url: http_impl://10.101.30.183:80
    Configuration number (c#): 16
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): C8:93:D2:13:47:7D
    Model Name (md): VOCOlinc-Flowerbud-0d19f1
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Humidifier (Id: 22)
    
    Name: Netatmo Welcome (2)._hap._tcp.local.
    Url: http_impl://10.101.30.29:5001
    Configuration number (c#): 4
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 67:C5:2B:9E:59:47
    Model Name (md): Welcome
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
    
    Name: LIX Tiles._hap._tcp.local.
    Url: http_impl://10.101.30.180:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): C8:3A:A5:FD:DA:10
    Model Name (md): LIFX Tile
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
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
    
    Name: Aqara Hub-A779._hap._tcp.local.
    Url: http_impl://10.101.30.88:4567
    Configuration number (c#): 16
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:E0:B3:76:FD:0F
    Model Name (md): Aqara Hub-1900
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
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
    
    Name: iDevices Outdoor Switch._hap._tcp.local.
    Url: http_impl://10.101.30.46:80
    Configuration number (c#): 3
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): AE:E4:D8:DC:12:2F
    Model Name (md): IDEV0004
    Protocol Version (pv): 1.0
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Switch (Id: 8)
    
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
    


## result **✔**

Name: LIX Tiles._hap._tcp.local.
Url: http_impl://10.101.30.180:80
Configuration number (c#): 3
Feature Flags (ff): Supports HAP Pairing (Flag: 1)
Device ID (id): C8:3A:A5:FD:DA:10
Model Name (md): LIFX Tile
Protocol Version (pv): 1.1
State Number (s#): 1
Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
Category Identifier (ci): Lightbulb (Id: 5)

# Step 2 - unpaired identify
## used command


```python
!python3 -m homekit.identify -d C8:3A:A5:FD:DA:10
```

## result **✔ **

LIFX Tiles First tile Flashes

# Step 3 - initialize controller storage

## used command


```python
!python3 -m homekit.init_controller_storage -f lifx
```

## result **✔**

# Step 4 - pairing

## used command


```python
!python3 -m homekit.pair -d C8:3A:A5:FD:DA:10 -p 555-55-555 -a tiles -f lifx
```

    Pairing for "tiles" was established.


## result **✔**

~~~
{
  "tiles": {
    "AccessoryPairingID": "C8:3A:A5:FD:DA:10",
    "AccessoryLTPK": "1f142e8087ba100b293c42c619318943abf5d5d8a4f77ca8edc7458270df0ded",
    "iOSPairingId": "0f7546ff-351c-453c-92f6-936cc271778e",
    "iOSDeviceLTSK": "d2b6fd030a6eb1d5d8f7b84d14637d2d75a3caf5a91007535e62bb574bcd3fb7",
    "iOSDeviceLTPK": "e5cde91dec3914c4c1e824e4e553cc970d292f63c505ffd7f2ac545774749d8e",
    "AccessoryIP": "10.101.30.180",
    "AccessoryPort": 80,
    "Connection": "IP",
    "accessories": [
      {
        "aid": 1,
        "services": [
          {
            "type": "0000003E-0000-1000-8000-0026BB765291",
            "iid": 1,
            "primary": false,
            "hidden": false,
            "linked": [],
            "characteristics": [
              {
                "perms": [
                  "pw"
                ],
                "type": "00000014-0000-1000-8000-0026BB765291",
                "iid": 2,
                "format": "bool"
              },
              {
                "value": "LIFX",
                "perms": [
                  "pr"
                ],
                "type": "00000020-0000-1000-8000-0026BB765291",
                "iid": 3,
                "format": "string"
              },
              {
                "value": "LIFX Tile",
                "perms": [
                  "pr"
                ],
                "type": "00000021-0000-1000-8000-0026BB765291",
                "iid": 4,
                "format": "string"
              },
              {
                "value": "LIX Tiles",
                "perms": [
                  "pr"
                ],
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 5,
                "format": "string"
              },
              {
                "value": "D073D53C5E25",
                "perms": [
                  "pr"
                ],
                "type": "00000030-0000-1000-8000-0026BB765291",
                "iid": 6,
                "format": "string"
              },
              {
                "value": "3.50",
                "perms": [
                  "pr"
                ],
                "type": "00000052-0000-1000-8000-0026BB765291",
                "iid": 7,
                "format": "string"
              },
              {
                "value": "1.0",
                "perms": [
                  "pr"
                ],
                "type": "00000053-0000-1000-8000-0026BB765291",
                "iid": 8,
                "format": "string"
              }
            ]
          },
          {
            "type": "000000A2-0000-1000-8000-0026BB765291",
            "iid": 16,
            "primary": false,
            "hidden": false,
            "linked": [],
            "characteristics": [
              {
                "value": "1.1.0",
                "perms": [
                  "pr"
                ],
                "type": "00000037-0000-1000-8000-0026BB765291",
                "iid": 17,
                "format": "string",
                "maxLen": 64
              }
            ]
          },
          {
            "type": "00000043-0000-1000-8000-0026BB765291",
            "iid": 9,
            "primary": true,
            "hidden": false,
            "linked": [],
            "characteristics": [
              {
                "value": true,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "00000025-0000-1000-8000-0026BB765291",
                "iid": 10,
                "format": "bool"
              },
              {
                "value": 39,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "00000008-0000-1000-8000-0026BB765291",
                "iid": 11,
                "format": "int",
                "minValue": 0,
                "maxValue": 100,
                "minStep": 1,
                "unit": "percentage"
              },
              {
                "value": 197,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "00000013-0000-1000-8000-0026BB765291",
                "iid": 13,
                "format": "float",
                "minValue": 0,
                "maxValue": 360,
                "minStep": 1,
                "unit": "arcdegrees"
              },
              {
                "value": 49,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "0000002F-0000-1000-8000-0026BB765291",
                "iid": 12,
                "format": "float",
                "minValue": 0,
                "maxValue": 100,
                "minStep": 1,
                "unit": "percentage"
              },
              {
                "value": "LIX Tiles",
                "perms": [
                  "pr"
                ],
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 14,
                "format": "string"
              }
            ]
          }
        ]
      }
    ]
  }
}

# Step 5 - paired identify

## used command


```python
!python3 -m homekit.identify -f lifx -a tiles
```

## result  **✔**

First tile of LIFX tiles chain flashes

# Step 6 - get accessories

## used command


```python
!python3 -m homekit.get_accessories -f lifx -a tiles
```

    1.1: >accessory-information<
      1.2:  () >identify< [pw]
      1.3: LIFX () >manufacturer< [pr]
      1.4: LIFX Tile () >model< [pr]
      1.5: LIX Tiles () >name< [pr]
      1.6: D073D53C5E25 () >serial-number< [pr]
      1.7: 3.50 () >firmware.revision< [pr]
      1.8: 1.0 () >hardware.revision< [pr]
    1.16: >service<
      1.17: 1.1.0 () >version< [pr]
    1.9: >lightbulb<
      1.10: True () >on< [pr,pw,ev]
      1.11: 39 () >brightness< [pr,pw,ev]
      1.13: 197 () >hue< [pr,pw,ev]
      1.12: 49 () >saturation< [pr,pw,ev]
      1.14: LIX Tiles () >name< [pr]


# Step 7 - get characteristics

## used command


```python
!python3 -m homekit.get_characteristic -f lifx -a tiles -c 1.4
```

    {
        "1.4": {
            "value": "LIFX Tile"
        }
    }


## result  **✔**

# Step 8 - put characteristics

## used command


```python
!python3 -m homekit.put_characteristic -f lifx -a tiles -c 1.10 False
```

## result  **✔**

All LIFX Tiles turned off

# Step 9 - get events

## used command

Note: Ran *python3 -m homekit.put_characteristic -f lifx -a tiles -c 1.10 True* from a seperate terminal window to get output. 


```python
!python3 -m homekit.get_events -f lifx -a tiles -c 1.10
```

    event for 1.10: True
    ^C


## result  **✔**

# Step 10 - remove pairing

## used command


```python
!python -m homekit.unpair -f lifx -a tiles
```

    Traceback (most recent call last):
      File "/usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/lib/python3.7/runpy.py", line 193, in _run_module_as_main
        "__main__", mod_spec)
      File "/usr/local/Cellar/python/3.7.0/Frameworks/Python.framework/Versions/3.7/lib/python3.7/runpy.py", line 85, in _run_code
        exec(code, run_globals)
      File "/Users/christopheryoung/PycharmProjects/netmanchris_homekit/venv/lib/python3.7/site-packages/homekit-0.13.0-py3.7.egg/homekit/unpair.py", line 46, in <module>
      File "/Users/christopheryoung/PycharmProjects/netmanchris_homekit/venv/lib/python3.7/site-packages/homekit-0.13.0-py3.7.egg/homekit/controller/controller.py", line 500, in remove_pairing
      File "/Users/christopheryoung/PycharmProjects/netmanchris_homekit/venv/lib/python3.7/site-packages/homekit-0.13.0-py3.7.egg/homekit/protocol/tlv.py", line 96, in decode_bytes
      File "/Users/christopheryoung/PycharmProjects/netmanchris_homekit/venv/lib/python3.7/site-packages/homekit-0.13.0-py3.7.egg/homekit/protocol/tlv.py", line 110, in decode_bytearray
    homekit.protocol.tlv.TlvParseException: Not enough data for length 34


## result  **✔**
