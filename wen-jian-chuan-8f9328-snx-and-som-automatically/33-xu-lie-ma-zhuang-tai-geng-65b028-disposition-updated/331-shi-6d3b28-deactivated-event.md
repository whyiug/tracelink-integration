# 范例文件



## 小盒状态失活



```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<snx:SNXDispositionUpdatedMessage xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <snx:ControlFileHeader>
        <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
        <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
        <cmn:FileControlNumber>03104-13300001</cmn:FileControlNumber>
        <cmn:FileDate>2017-09-13</cmn:FileDate>
        <cmn:FileTime>07:24:44Z</cmn:FileTime>
    </snx:ControlFileHeader>
    <snx:MessageBody>
        <snx:EventSummary>
            <cmn:InternalMaterialCode>2502111502</cmn:InternalMaterialCode>
            <cmn:LotNumber>A112345</cmn:LotNumber>
            <snx:SerialNumberCount>
                <cmn:PackagingLevelItemCode type="GTIN-14">20325021115026</cmn:PackagingLevelItemCode>
                <cmn:PackagingLevel>EA</cmn:PackagingLevel>
                <cmn:Quantity>1</cmn:Quantity>
            </snx:SerialNumberCount>
            <TotalSerialNumberCount>1</TotalSerialNumberCount>
        </snx:EventSummary>
        <cmn:EventDateTime>2017-09-13T06:24:43.764Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
        <snx:SerialNumbers>
            <cmn:Serial companyPrefix="0325021" filterValue="1" format="AI(01)+AI(21)">012032502111502621Z2PMYRXN0MK2</cmn:Serial>
        </snx:SerialNumbers>
        <cmn:PackagingSerialNumberStatus>DEACTIVATED</cmn:PackagingSerialNumberStatus>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>PW0013</cmn:ProductionLineId>
        <cmn:LineManagerName>John Smith</cmn:LineManagerName>
        <cmn:ReasonDescription>test</cmn:ReasonDescription>
    </snx:MessageBody>
</snx:SNXDispositionUpdatedMessage>
```



