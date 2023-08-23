![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301027/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301027",
    "model"     : "model-01",
    "serial"    : "SN-001",
    "name"      : "wash_count",
    "value"     : "10"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301027/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301027",
    "model"     : "model-01",
    "serial"    : "SN-001",
    "name"      : "firmware",
    "value"     : "01"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301027/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301027",
    "model"     : "model-01",
    "serial"    : "SN-001",
    "name"      : "location placement",
    "value"     : "phuket"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301027/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301027",
    "model"     : "model-01",
    "serial"    : "SN-001",
    "name"      : "location placement",
    "value"     : "phuket"
}
```

## Monitor machine sensor
```
Topic: v1cdti/hw/monitor/6310301027/model-01/WSH-SN001
Payload: {
    "action"    : "monitor",
    "project"   : "6310301027",
    "model"     : "model-01",
    "serial"    : "SN-001",
    "name"      : "rotage round",
    "value"     : "2000"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/set/6310301027/model-01/WSH-SN001
Payload: {
    "action"    : "monitor",
    "project"   : "6310301027",
    "model"     : "model-01",
    "serial"    : "SN-001",
    "name"      : "status",
    "value"     : "maint"
}
```