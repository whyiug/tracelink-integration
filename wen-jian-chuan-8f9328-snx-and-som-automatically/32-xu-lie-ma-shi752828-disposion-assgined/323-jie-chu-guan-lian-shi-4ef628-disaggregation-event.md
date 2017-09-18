# 范例文件

## 解除大箱和小盒的关联

```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<snx:SNXDisaggregatedMessage xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes">
    <snx:ControlFileHeader>
        <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
        <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
        <cmn:FileControlNumber>01085dgcldaa</cmn:FileControlNumber>
        <cmn:FileDate>2017-09-15</cmn:FileDate>
        <cmn:FileTime>07:32:21Z</cmn:FileTime>
    </snx:ControlFileHeader>
    <snx:MessageBody>
        <snx:DisaggregatedEvent>
            <cmn:EventDateTime>2017-09-14T07:30:04.000Z</cmn:EventDateTime>
            <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
            <cmn:EventLocation type="SGLN">6970021.75001.4</cmn:EventLocation>
            <cmn:ParentSerialNumber companyPrefix="0325021" filterValue="5" format="AI(01)+AI(21)">015032502111502721RXXXEA48PWYN</cmn:ParentSerialNumber>
            <snx:SerialNumberList>
                <cmn:SerialNumber companyPrefix="0325021" filterValue="2" format="AI(01)+AI(21)">0120325021115026218SMHZ61YFYSZ</cmn:SerialNumber>
            </snx:SerialNumberList>
        </snx:DisaggregatedEvent>
    </snx:MessageBody>
</snx:SNXDisaggregatedMessage>
```



