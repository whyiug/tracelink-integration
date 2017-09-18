# 范例文件

## 小盒赋码状态解除



```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<snx:SNXDispositionUpdatedMessage xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes">
    <snx:ControlFileHeader>
        <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
        <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
        <cmn:FileControlNumber>01085300013011</cmn:FileControlNumber>
        <cmn:FileDate>2017-09-13</cmn:FileDate>
        <cmn:FileTime>08:59:24Z</cmn:FileTime>
    </snx:ControlFileHeader>
    <snx:MessageBody>
        <cmn:EventDateTime>2017-09-13T08:58:23.696Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
        <snx:SerialNumbers>
            <cmn:Serial>012032502111502621WXVCECA0HRR5</cmn:Serial>
        </snx:SerialNumbers>
        <cmn:PackagingSerialNumberStatus>DECOMMISSIONED</cmn:PackagingSerialNumberStatus>
        <cmn:ItemAttribute>DAMAGED</cmn:ItemAttribute>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>PW001</cmn:ProductionLineId>
        <cmn:LineManagerName>John Smith</cmn:LineManagerName>
        <cmn:ReferenceDocuments>
            <cmn:PONumber>1001764</cmn:PONumber>
        </cmn:ReferenceDocuments>
        <cmn:ReasonDescription>Damaged in warehouse</cmn:ReasonDescription>
    </snx:MessageBody>
</snx:SNXDispositionUpdatedMessage>
```



