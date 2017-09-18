# 范例文件

## 小盒状态销毁



```xml
<?xml version="1.0" encoding="UTF-8"?>
<SNXDispositionUpdatedMessage xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <ControlFileHeader>
        <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
        <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
        <cmn:FileControlNumber>010853000101</cmn:FileControlNumber>
        <cmn:FileDate>2017-09-13</cmn:FileDate>
        <cmn:FileTime>08:27:24Z</cmn:FileTime>
    </ControlFileHeader>
    <MessageBody>
        <cmn:EventDateTime>2017-09-13T08:17:23.696Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
        <SerialNumbers>
            <cmn:Serial>012032502111502621PZKSS5S7W9M1</cmn:Serial>
        </SerialNumbers>
        <cmn:PackagingSerialNumberStatus>DESTROYED</cmn:PackagingSerialNumberStatus>
        <cmn:ItemAttribute>DAMAGED</cmn:ItemAttribute>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>PW001</cmn:ProductionLineId>
        <cmn:LineManagerName>John Smith</cmn:LineManagerName>
        <cmn:ReferenceDocuments>
            <cmn:PONumber>1001764</cmn:PONumber>
        </cmn:ReferenceDocuments>
        <cmn:ReasonDescription>Damaged in warehouse</cmn:ReasonDescription>
    </MessageBody>
</SNXDispositionUpdatedMessage>
```



