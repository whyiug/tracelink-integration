```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<snx:SNXDispositionAssignedMessage xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <snx:ControlFileHeader>
        <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
        <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
        <cmn:FileControlNumber>893a5-4faa79ff4ae5cd0b</cmn:FileControlNumber>
        <cmn:FileDate>2017-09-15</cmn:FileDate>
        <cmn:FileTime>06:20:38</cmn:FileTime>
        <cmn:FileTransactionType>GR_COMMISSION</cmn:FileTransactionType>
    </snx:ControlFileHeader>
    <snx:MessageBody>
        <snx:CommissionEvent>
            <snx:CommissionEventDetail>
                <cmn:EventDateTime>2017-09-15T06:20:38.695</cmn:EventDateTime>
                <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
                <cmn:SerialNumber companyPrefix="0325021" filterValue="2" format="AI(01)+AI(21)">012032502111502621SRVPR8N50KCY</cmn:SerialNumber>
                <cmn:FilterValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:nil="true"/>
                <cmn:PackagingLevel>EA</cmn:PackagingLevel>
                <cmn:BarcodeContent>012032502111502621SRVPR8N50KCY</cmn:BarcodeContent>
            </snx:CommissionEventDetail>
            <snx:CommissionEventDetail>
                <cmn:EventDateTime>2017-09-15T06:20:38.695</cmn:EventDateTime>
                <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
                <cmn:SerialNumber companyPrefix="0325021" filterValue="2" format="AI(01)+AI(21)">0120325021115026218SMHZ61YFYSZ</cmn:SerialNumber>
                <cmn:FilterValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:nil="true"/>
                <cmn:PackagingLevel>EA</cmn:PackagingLevel>
                <cmn:BarcodeContent>0120325021115026218SMHZ61YFYSZ</cmn:BarcodeContent>
            </snx:CommissionEventDetail>
            <snx:CommissionEventDetail>
                <cmn:EventDateTime>2017-09-15T06:20:38.695</cmn:EventDateTime>
                <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
                <cmn:SerialNumber companyPrefix="0325021" filterValue="2" format="AI(01)+AI(21)">0120325021115026216H69K46KRCXM</cmn:SerialNumber>
                <cmn:FilterValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:nil="true"/>
                <cmn:PackagingLevel>EA</cmn:PackagingLevel>
                <cmn:BarcodeContent>0120325021115026216H69K46KRCXM</cmn:BarcodeContent>
            </snx:CommissionEventDetail>
            <snx:CommissionEventDetail>
                <cmn:EventDateTime>2017-09-15T06:20:38.695</cmn:EventDateTime>
                <cmn:EventTimeZoneOffset>+00:00</cmn:EventTimeZoneOffset>
                <cmn:SerialNumber companyPrefix="0325021" filterValue="2" format="AI(01)+AI(21)">012032502111502621PACVY1C1R9CK</cmn:SerialNumber>
                <cmn:FilterValue xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:nil="true"/>
                <cmn:PackagingLevel>EA</cmn:PackagingLevel>
                <cmn:BarcodeContent>012032502111502621PACVY1C1R9CK</cmn:BarcodeContent>
            </snx:CommissionEventDetail>
            <snx:CommissionCommonAttributes>
                <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
                <cmn:ProductionLineId>L001</cmn:ProductionLineId>
                <cmn:LineManagerName>Kang</cmn:LineManagerName>
                <snx:ItemDetail>
                    <cmn:ItemCode type="GTIN-14">20325021115026</cmn:ItemCode>
                    <cmn:CountryDrugCode type="US_NDC532">2502111502</cmn:CountryDrugCode>
                    <cmn:LotNumber>B00013</cmn:LotNumber>
                    <cmn:ExpirationDate>2018-07-26</cmn:ExpirationDate>
                </snx:ItemDetail>
            </snx:CommissionCommonAttributes>
        </snx:CommissionEvent>
    </snx:MessageBody>
</snx:SNXDispositionAssignedMessage>

```



# 注意

> EventDateTime为GM时间；
>
> 时区如果是中国的话，填写+08:00；
>
> GCP填写Sagent的GCP；



