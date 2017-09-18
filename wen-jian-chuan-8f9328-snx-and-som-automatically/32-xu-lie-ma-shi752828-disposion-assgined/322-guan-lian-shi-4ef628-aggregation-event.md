# 范例文件

## 大箱关联小盒

```xml
<?xml version="1.0" encoding="utf-8"?>
<snx:SNXDispositionAssignedMessage xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <snx:ControlFileHeader>
        <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
        <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
        <cmn:FileControlNumber>01085dgcldaa</cmn:FileControlNumber>
        <cmn:FileDate>2017-09-15</cmn:FileDate>
        <cmn:FileTime>07:28:21Z</cmn:FileTime>
    </snx:ControlFileHeader>
    <snx:MessageBody>
        <snx:AggregationEvent>
            <snx:AggregationEventDetail>
                <cmn:EventDateTime>2017-09-15T07:26:51Z</cmn:EventDateTime>
                <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
                <cmn:EventLocation type="SGLN">6970021.75001.4</cmn:EventLocation>
                <cmn:ParentSerialNumber>015032502111502721F8HA2R93PFFN</cmn:ParentSerialNumber>
                <cmn:PackedStatus>PARTIAL</cmn:PackedStatus>
                <cmn:Quantity>1</cmn:Quantity>
                <cmn:SerialNumberList>
                    <cmn:SerialNumber>012032502111502621SRVPR8N50KCY</cmn:SerialNumber>
                </cmn:SerialNumberList>
            </snx:AggregationEventDetail>
            <snx:AggregationEventDetail>
                <cmn:EventDateTime>2017-09-15T07:27:51Z</cmn:EventDateTime>
                <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
                <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
                <cmn:ParentSerialNumber>015032502111502721RXXXEA48PWYN</cmn:ParentSerialNumber>
                <cmn:PackedStatus>PARTIAL</cmn:PackedStatus>
                <cmn:Quantity>3</cmn:Quantity>
                <cmn:SerialNumberList>
                    <cmn:SerialNumber>0120325021115026218SMHZ61YFYSZ</cmn:SerialNumber>
                    <cmn:SerialNumber>0120325021115026216H69K46KRCXM</cmn:SerialNumber>
                    <cmn:SerialNumber>012032502111502621PACVY1C1R9CK</cmn:SerialNumber>
                </cmn:SerialNumberList>
            </snx:AggregationEventDetail>
        </snx:AggregationEvent>
    </snx:MessageBody>
</snx:SNXDispositionAssignedMessage>
```

# 





