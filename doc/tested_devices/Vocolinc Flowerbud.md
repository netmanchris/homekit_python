
# Device Name: **Vocolinc Flowerbud**

Important Information:
 * device manufacturer : **LIFX**
 * device model : **LIFX Tiles**
 * device firmware version : **3.117.2**
 * device hardware version : **0.1**
 * communication channel : **IP**
 * version of *homekit* library: **0.14.0.**

# Step 1 - discovery

## used command


```python
!python3 -m homekit.discover
```

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
    
    Name: VOCOlinc-Flowerbud-0d239e._hap._tcp.local.
    Url: http_impl://10.101.30.191:80
    Configuration number (c#): 1
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 3F:EB:2F:CD:AE:2A
    Model Name (md): VOCOlinc-Flowerbud-0d239e
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
    Category Identifier (ci): Humidifier (Id: 22)
    
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
    
    Name: Aqara Hub-A779 10._hap._tcp.local.
    Url: http_impl://10.101.30.88:4567
    Configuration number (c#): 16
    Feature Flags (ff): Supports HAP Pairing (Flag: 1)
    Device ID (id): 50:E0:B3:76:FD:0F
    Model Name (md): Aqara Hub-1900
    Protocol Version (pv): 1.1
    State Number (s#): 1
    Status Flags (sf): Accessory has been paired. (Flag: 0)
    Category Identifier (ci): Bridge (Id: 2)
    
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
    


## result **✔**

```
Name: VOCOlinc-Flowerbud-0d239e._hap._tcp.local.
Url: http_impl://10.101.30.191:80
Configuration number (c#): 1
Feature Flags (ff): Supports HAP Pairing (Flag: 1)
Device ID (id): 3F:EB:2F:CD:AE:2A
Model Name (md): VOCOlinc-Flowerbud-0d239e
Protocol Version (pv): 1.1
State Number (s#): 1
Status Flags (sf): Accessory has not been paired with any controllers. (Flag: 1)
Category Identifier (ci): Humidifier (Id: 22)
```

# Step 2 - unpaired identify
## used command


```python
!python3 -m homekit.identify -d 3F:EB:2F:CD:AE:2A
```

# Device Name: **LIFX Tiles**

Important Information:
 * device manufacturer : **LIFX**
 * device model : **LIFX Tiles**
 * device firmware version : **3.50**
 * device hardware version : **1.0**
 * communication channel : **IP**
 * version of *homekit* library: **0.14.0.**

## result **✔ **

Vocolinc Flowerbud Flashes

# Step 3 - initialize controller storage

## used command


```python
!python3 -m homekit.init_controller_storage -f vocolinc
```

## result **✔**

# Step 4 - pairing

## used command


```python
!python3 -m homekit.pair -d 3F:EB:2F:CD:AE:2A -p 555-55-555 -a flower -f vocolinc
```

    Pairing for "flower" was established.


## result **✔**

```{
  "flower": {
    "AccessoryPairingID": "3F:EB:2F:CD:AE:2A",
    "AccessoryLTPK": "c9f33fb23b5ca65564577579d7d79dbe5f503e022c12ebe1173908a9e1d2149a",
    "iOSPairingId": "348bf936-d897-4741-bdc3-8b6d2f1d2df9",
    "iOSDeviceLTSK": "970f5915be1d660c8b5ebb266cf16d4727c1e3c7cf6b6dcd51848461b7d225d6",
    "iOSDeviceLTPK": "f084479b76cf47f745520e5053e09c4d71e03a549440f730f4e94540f4f5a10c",
    "AccessoryIP": "10.101.30.191",
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
                "perms": [
                  "pw"
                ],
                "type": "00000014-0000-1000-8000-0026BB765291",
                "iid": 2,
                "format": "bool"
              },
              {
                "value": "VOCOlinc",
                "perms": [
                  "pr"
                ],
                "type": "00000020-0000-1000-8000-0026BB765291",
                "iid": 3,
                "format": "string"
              },
              {
                "value": "Flowerbud",
                "perms": [
                  "pr"
                ],
                "type": "00000021-0000-1000-8000-0026BB765291",
                "iid": 4,
                "format": "string"
              },
              {
                "value": "VOCOlinc-Flowerbud-0d239e",
                "perms": [
                  "pr"
                ],
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 5,
                "format": "string"
              },
              {
                "value": "AM01121836000010",
                "perms": [
                  "pr"
                ],
                "type": "00000030-0000-1000-8000-0026BB765291",
                "iid": 6,
                "format": "string"
              },
              {
                "description": "",
                "value": "3.117.2",
                "perms": [
                  "pr"
                ],
                "type": "00000052-0000-1000-8000-0026BB765291",
                "iid": 7,
                "format": "string"
              },
              {
                "value": "0.1",
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
            "type": "C635EF5C-5BBC-4F96-B7DA-6669069A4B32",
            "iid": 80,
            "characteristics": [
              {
                "perms": [
                  "pr",
                  "pw"
                ],
                "format": "bool",
                "value": 0,
                "type": "D9959C8A-809A-4F75-92D7-71F630AC2925",
                "description": "rssi_report_switch",
                "iid": 81
              },
              {
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "format": "uint8",
                "value": 37,
                "type": "8137182C-6904-4FB9-ADCC-61CECA85CE48",
                "description": "rssi_report_value",
                "iid": 82
              }
            ]
          },
          {
            "type": "BD",
            "iid": 30,
            "characteristics": [
              {
                "value": "FLOWERBUD",
                "perms": [
                  "pr"
                ],
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 31,
                "format": "string"
              },
              {
                "value": 0,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "000000B0-0000-1000-8000-0026BB765291",
                "iid": 32,
                "format": "uint8",
                "maxValue": 1,
                "minValue": 0,
                "minStep": 1
              },
              {
                "value": 60.0,
                "perms": [
                  "pr",
                  "ev"
                ],
                "type": "00000010-0000-1000-8000-0026BB765291",
                "iid": 33,
                "unit": "percentage",
                "format": "float",
                "maxValue": 100.0,
                "minValue": 0.0,
                "minStep": 1.0
              },
              {
                "value": 0,
                "perms": [
                  "pr",
                  "ev"
                ],
                "type": "B3",
                "iid": 34,
                "format": "uint8",
                "maxValue": 2,
                "minValue": 0,
                "minStep": 1
              },
              {
                "value": 1,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "B4",
                "iid": 35,
                "format": "uint8",
                "maxValue": 1,
                "minValue": 1,
                "minStep": 1
              },
              {
                "value": 0,
                "perms": [
                  "pr",
                  "ev"
                ],
                "type": "36158AC8-5191-4AE2-9EF5-1D6722E88E3D",
                "iid": 36,
                "format": "uint8",
                "maxValue": 1,
                "minValue": 0,
                "minStep": 1
              },
              {
                "description": "spray quantity",
                "value": 5,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "69D52519-0A4E-4898-8335-4739F9116D0A",
                "iid": 38,
                "format": "uint8",
                "maxValue": 5,
                "minValue": 1,
                "minStep": 1
              },
              {
                "value": 100.0,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "CA",
                "iid": 39,
                "format": "float",
                "unit": "percentage",
                "maxValue": 100.0,
                "minValue": 0.0,
                "minStep": 1.0
              },
              {
                "description": "humidifier_timer_setting",
                "value": "AA==",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "F84B3138-E44F-49B9-AA91-9E1736C247C0",
                "iid": 40,
                "format": "data"
              },
              {
                "description": "humidifier_countdown",
                "value": "AA==",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "43CE176B-2933-4034-98A7-AD215BEEBF2F",
                "iid": 41,
                "format": "data"
              }
            ]
          },
          {
            "type": "00000043-0000-1000-8000-0026BB765291",
            "iid": 9,
            "characteristics": [
              {
                "value": "Mood Light",
                "perms": [
                  "pr"
                ],
                "type": "00000023-0000-1000-8000-0026BB765291",
                "iid": 10,
                "format": "string"
              },
              {
                "value": true,
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "00000025-0000-1000-8000-0026BB765291",
                "iid": 11,
                "format": "bool"
              },
              {
                "unit": "percentage",
                "format": "int",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 12,
                "maxValue": 100,
                "minValue": 0,
                "value": 50,
                "type": "00000008-0000-1000-8000-0026BB765291",
                "minStep": 1
              },
              {
                "unit": "arcdegrees",
                "format": "float",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 13,
                "maxValue": 360.0,
                "minValue": 0.0,
                "value": 0.0,
                "type": "00000013-0000-1000-8000-0026BB765291",
                "minStep": 1.0
              },
              {
                "unit": "percentage",
                "format": "float",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 14,
                "maxValue": 100.0,
                "minValue": 0.0,
                "value": 0.0,
                "type": "0000002F-0000-1000-8000-0026BB765291",
                "minStep": 1.0
              },
              {
                "description": "lb_timer_setting",
                "value": "AA==",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "type": "A30DFE91-271A-42A5-88BA-00E3FF5488AD",
                "iid": 63,
                "format": "data"
              },
              {
                "description": "light effect mode",
                "value": 0,
                "format": "uint8",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 64,
                "maxValue": 31,
                "minValue": 0,
                "minStep": 1,
                "type": "146889FC-7C42-429B-93AB-E80F79759E90"
              },
              {
                "description": "light effect flag",
                "value": 7,
                "format": "uint32",
                "perms": [
                  "pr"
                ],
                "iid": 73,
                "type": "9D4B479D-9EFB-4739-98F3-B33E6543BF7B"
              },
              {
                "description": "flashing mode",
                "value": "AA==",
                "format": "data",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 65,
                "type": "2C42B339-6EC9-4ED5-8DBF-FFCCC721B144"
              },
              {
                "description": "smoothing mode",
                "value": "AA==",
                "format": "data",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 66,
                "type": "A3663C89-DC18-42EF-8297-910A4C0C9B61"
              },
              {
                "description": "breathing mode",
                "value": "AA==",
                "format": "data",
                "perms": [
                  "pr",
                  "pw",
                  "ev"
                ],
                "iid": 67,
                "type": "6533B15C-AECB-455F-8896-20B125390F61"
              }
            ]
          },
          {
            "type": "961EBB65-A1E3-4F34-BD31-86552706FE40",
            "iid": 48,
            "characteristics": [
              {
                "format": "int",
                "perms": [
                  "pr",
                  "pw"
                ],
                "iid": 50,
                "maxValue": 1400,
                "minValue": -1200,
                "value": 0,
                "type": "38396B8E-161B-4A77-AF3F-C4DAC0BE9B74",
                "description": "time_zone",
                "minStep": 1
              },
              {
                "format": "int",
                "perms": [
                  "pr",
                  "pw"
                ],
                "iid": 51,
                "value": 0,
                "type": "71216CD3-209E-40CC-BEA0-71A2A9458E13",
                "description": "hour_date_time"
              }
            ]
          },
          {
            "hidden": true,
            "type": "3138B537-E830-4F52-90A7-D6FDB000BF97",
            "iid": 20,
            "characteristics": [
              {
                "description": "fm_upgrade_status",
                "value": 0,
                "perms": [
                  "pr",
                  "ev"
                ],
                "type": "49DDDE07-C3FA-499E-8055-58E154E04F34",
                "iid": 21,
                "format": "int"
              },
              {
                "description": "fm_upgrade_url",
                "perms": [
                  "pw"
                ],
                "maxLen": 256,
                "type": "4C203E30-EB25-466D-9980-C6C2E14BF6AA",
                "iid": 22,
                "format": "string"
              }
            ]
          },
          {
            "type": "000000A2-0000-1000-8000-0026BB765291",
            "iid": 23,
            "characteristics": [
              {
                "type": "00000037-0000-1000-8000-0026BB765291",
                "iid": 24,
                "perms": [
                  "pr"
                ],
                "format": "string",
                "value": "1.1.0"
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
!python3 -m homekit.identify -f vocolinc -a flower
```

## result  **✔**

Vocolinc Flower Flashes

# Step 6 - get accessories

## used command


```python
!python3 -m homekit.get_accessories -f vocolinc -a flower
```

    1.1: >accessory-information<
      1.2:  () >identify< [pw]
      1.3: VOCOlinc () >manufacturer< [pr]
      1.4: Flowerbud () >model< [pr]
      1.5: VOCOlinc-Flowerbud-0d239e () >name< [pr]
      1.6: AM01121836000010 () >serial-number< [pr]
      1.7: 3.117.2 () >firmware.revision< [pr]
      1.8: 0.1 () >hardware.revision< [pr]
    1.80: >Unknown Service: C635EF5C-5BBC-4F96-B7DA-6669069A4B32<
      1.81: 0 (rssi_report_switch) >Unknown Characteristic D9959C8A-809A-4F75-92D7-71F630AC2925< [pr,pw]
      1.82: 37 (rssi_report_value) >Unknown Characteristic 8137182C-6904-4FB9-ADCC-61CECA85CE48< [pr,pw,ev]
    1.30: >Unknown Service: BD<
      1.31: FLOWERBUD () >name< [pr]
      1.32: 0 () >active< [pr,pw,ev]
      1.33: 60.0 () >relative-humidity.current< [pr,ev]
      1.34: 0 () >Unknown Characteristic B3< [pr,ev]
      1.35: 1 () >Unknown Characteristic B4< [pr,pw,ev]
      1.36: 0 () >Unknown Characteristic 36158AC8-5191-4AE2-9EF5-1D6722E88E3D< [pr,ev]
      1.38: 5 (spray quantity) >Unknown Characteristic 69D52519-0A4E-4898-8335-4739F9116D0A< [pr,pw,ev]
      1.39: 100.0 () >Unknown Characteristic CA< [pr,pw,ev]
      1.40: AA== (humidifier_timer_setting) >Unknown Characteristic F84B3138-E44F-49B9-AA91-9E1736C247C0< [pr,pw,ev]
      1.41: AA== (humidifier_countdown) >Unknown Characteristic 43CE176B-2933-4034-98A7-AD215BEEBF2F< [pr,pw,ev]
    1.9: >lightbulb<
      1.10: Mood Light () >name< [pr]
      1.11: True () >on< [pr,pw,ev]
      1.12: 50 () >brightness< [pr,pw,ev]
      1.13: 0.0 () >hue< [pr,pw,ev]
      1.14: 0.0 () >saturation< [pr,pw,ev]
      1.63: AA== (lb_timer_setting) >Unknown Characteristic A30DFE91-271A-42A5-88BA-00E3FF5488AD< [pr,pw,ev]
      1.64: 0 (light effect mode) >Unknown Characteristic 146889FC-7C42-429B-93AB-E80F79759E90< [pr,pw,ev]
      1.73: 7 (light effect flag) >Unknown Characteristic 9D4B479D-9EFB-4739-98F3-B33E6543BF7B< [pr]
      1.65: AA== (flashing mode) >Unknown Characteristic 2C42B339-6EC9-4ED5-8DBF-FFCCC721B144< [pr,pw,ev]
      1.66: AA== (smoothing mode) >Unknown Characteristic A3663C89-DC18-42EF-8297-910A4C0C9B61< [pr,pw,ev]
      1.67: AA== (breathing mode) >Unknown Characteristic 6533B15C-AECB-455F-8896-20B125390F61< [pr,pw,ev]
    1.48: >Unknown Service: 961EBB65-A1E3-4F34-BD31-86552706FE40<
      1.50: 0 (time_zone) >Unknown Characteristic 38396B8E-161B-4A77-AF3F-C4DAC0BE9B74< [pr,pw]
      1.51: 0 (hour_date_time) >Unknown Characteristic 71216CD3-209E-40CC-BEA0-71A2A9458E13< [pr,pw]
    1.20: >Unknown Service: 3138B537-E830-4F52-90A7-D6FDB000BF97<
      1.21: 0 (fm_upgrade_status) >Unknown Characteristic 49DDDE07-C3FA-499E-8055-58E154E04F34< [pr,ev]
      1.22:  (fm_upgrade_url) >Unknown Characteristic 4C203E30-EB25-466D-9980-C6C2E14BF6AA< [pw]
    1.23: >service<
      1.24: 1.1.0 () >version< [pr]


# Step 7 - get characteristics

## used command


```python
!python3 -m homekit.get_characteristic -f vocolinc -a flower -c 1.11
```

    {
        "1.11": {
            "value": true
        }
    }


## result  **✔**

# Step 8 - put characteristics

## used command


```python
!python3 -m homekit.put_characteristic -f vocolinc -a flower -c 1.11 False
```

## result  **✔**

Vocolinc Flower Light turned off Tiles turned off

# Step 9 - get events

## used command

Note: Ran *python3 -m homekit.put_characteristic -f vocolinc -a flower -c 1.11 True* from a seperate terminal window to get output. 


```python
!python3 -m homekit.get_events -f vocolinc -a flower -c 1.11
```

    event for 1.11: True
    ^C


## result  **✔**

# Step 10 - remove pairing

## used command


```python
!python -m homekit.unpair -f vocolinc -a flower
```

    Pairing for "flower" was removed.


## result  **✔**
