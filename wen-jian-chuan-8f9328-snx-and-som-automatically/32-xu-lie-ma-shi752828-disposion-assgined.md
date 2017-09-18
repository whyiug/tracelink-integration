# 一个文件

一个文件中同时包含赋码和关联事件，为RED4S/SDC系统导出的主要文件。\(Tracelink API手册提供的就是这种方式\)。

# 范例文件

## 介绍

> 为了简单起见，范例中只使用：一托盘一箱一盒的关联，所以是零托，零箱；
>
> 一种是零箱SGTIN形式，一种是零箱SSCC形式；
>
> 注意SSCC的filter Value，当用于零箱时，这里是4，而Extension Digit为5\(可变\)；

## 零箱使用SGTIN

```xml
<?xml version="1.0" encoding="utf-8"?>
<SNXDispositionAssignedMessage xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <snx:ControlFileHeader>
    <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
    <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
    <cmn:FileControlNumber>1505699480</cmn:FileControlNumber>
    <cmn:FileDate>2017-09-18</cmn:FileDate>
    <cmn:FileTime>01:51:20Z</cmn:FileTime>
  </snx:ControlFileHeader>
  <MessageBody>
    <snx:CommissionEvent>
      <snx:CommissionEventDetail>
        <cmn:EventDateTime>2017-09-18T01:41:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:SerialNumber>0120325021115026213HYY8ZPNE0HX</cmn:SerialNumber>
        <cmn:FilterValue>2</cmn:FilterValue>
        <cmn:PackagingLevel>EA</cmn:PackagingLevel>
        <cmn:BarcodeContent>(01)20325021115026(21)3HYY8ZPNE0HX(17)180300(10)B1505699480</cmn:BarcodeContent>
      </snx:CommissionEventDetail>
      <snx:CommissionCommonAttributes>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>L001</cmn:ProductionLineId>
        <cmn:LineManagerName>胡小芳</cmn:LineManagerName>
        <ItemDetail>
          <cmn:ItemCode type="GTIN-14">20325021115026</cmn:ItemCode>
          <cmn:CountryDrugCode type="US_NDC532">2502111502</cmn:CountryDrugCode>
          <cmn:LotNumber>B1505699480</cmn:LotNumber>
          <cmn:ExpirationDate>2018-03-31</cmn:ExpirationDate>
          <cmn:ManufacturingDate>2017-09-18</cmn:ManufacturingDate>
        </ItemDetail>
      </snx:CommissionCommonAttributes>
    </snx:CommissionEvent>
    <snx:CommissionEvent>
      <snx:CommissionEventDetail>
        <cmn:EventDateTime>2017-09-18T01:42:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:SerialNumber>015032502111502721YE44073ZPP38</cmn:SerialNumber>
        <cmn:FilterValue>5</cmn:FilterValue>
        <cmn:PackagingLevel>CA</cmn:PackagingLevel>
        <cmn:BarcodeContent>(01)50325021115027(21)YE44073ZPP38(17)180300(10)B1505699480(30)1</cmn:BarcodeContent>
      </snx:CommissionEventDetail>
      <snx:CommissionCommonAttributes>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>L001</cmn:ProductionLineId>
        <cmn:LineManagerName>胡小芳</cmn:LineManagerName>
        <ItemDetail>
          <cmn:ItemCode type="GTIN-14">50325021115027</cmn:ItemCode>
          <cmn:CountryDrugCode type="US_NDC532">2502111502</cmn:CountryDrugCode>
          <cmn:LotNumber>B1505699480</cmn:LotNumber>
          <cmn:ExpirationDate>2018-03-31</cmn:ExpirationDate>
          <cmn:ManufacturingDate>2017-09-18</cmn:ManufacturingDate>
        </ItemDetail>
      </snx:CommissionCommonAttributes>
    </snx:CommissionEvent>
    <snx:CommissionEvent>
      <snx:CommissionEventDetail>
        <cmn:EventDateTime>2017-09-18T01:44:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:SerialNumber>00803250210000051395</cmn:SerialNumber>
        <cmn:FilterValue>7</cmn:FilterValue>
        <cmn:PackagingLevel>PL</cmn:PackagingLevel>
        <cmn:BarcodeContent>(00)803250210000051395</cmn:BarcodeContent>
      </snx:CommissionEventDetail>
      <snx:CommissionCommonAttributes>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>L001</cmn:ProductionLineId>
        <cmn:LineManagerName>胡小芳</cmn:LineManagerName>
        <cmn:CompanyPrefix>0325021</cmn:CompanyPrefix>
      </snx:CommissionCommonAttributes>
    </snx:CommissionEvent>
    <snx:AggregationEvent>
      <AggregationEventDetail>
        <cmn:EventDateTime>2017-09-18T01:45:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ParentSerialNumber>00803250210000051395</cmn:ParentSerialNumber>
        <cmn:PackedStatus>PARTIAL</cmn:PackedStatus>
        <cmn:Quantity>1</cmn:Quantity>
        <cmn:SerialNumberList>
          <cmn:SerialNumber>015032502111502721YE44073ZPP38</cmn:SerialNumber>
        </cmn:SerialNumberList>
      </AggregationEventDetail>
      <AggregationEventDetail>
        <cmn:EventDateTime>2017-09-18T01:43:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ParentSerialNumber>015032502111502721YE44073ZPP38</cmn:ParentSerialNumber>
        <cmn:PackedStatus>PARTIAL</cmn:PackedStatus>
        <cmn:Quantity>1</cmn:Quantity>
        <cmn:SerialNumberList>
          <cmn:SerialNumber>0120325021115026213HYY8ZPNE0HX</cmn:SerialNumber>
        </cmn:SerialNumberList>
      </AggregationEventDetail>
    </snx:AggregationEvent>
  </MessageBody>
</SNXDispositionAssignedMessage>
```

## 零箱使用SSCC

```xml
<SNXDispositionAssignedMessage xmlns:snx="urn:tracelink:mapper:sl:serial_number_exchange" xmlns="urn:tracelink:mapper:sl:serial_number_exchange" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <snx:ControlFileHeader>
    <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
    <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
    <cmn:FileControlNumber>1505699489</cmn:FileControlNumber>
    <cmn:FileDate>2017-09-18</cmn:FileDate>
    <cmn:FileTime>01:51:20Z</cmn:FileTime>
  </snx:ControlFileHeader>
  <MessageBody>
    <snx:CommissionEvent>
      <snx:CommissionEventDetail>
        <cmn:EventDateTime>2017-09-18T01:41:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:SerialNumber>0120325021115026213HYY8ZPNE0HX</cmn:SerialNumber>
        <cmn:FilterValue>2</cmn:FilterValue>
        <cmn:PackagingLevel>EA</cmn:PackagingLevel>
        <cmn:BarcodeContent>(01)20325021115026(21)3HYY8ZPNE0HX(17)180300(10)B1505699480</cmn:BarcodeContent>
      </snx:CommissionEventDetail>
      <snx:CommissionCommonAttributes>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>L001</cmn:ProductionLineId>
        <cmn:LineManagerName>胡小芳</cmn:LineManagerName>
        <ItemDetail>
          <cmn:ItemCode type="GTIN-14">20325021115026</cmn:ItemCode>
          <cmn:CountryDrugCode type="US_NDC532">2502111502</cmn:CountryDrugCode>
          <cmn:LotNumber>B1505699480</cmn:LotNumber>
          <cmn:ExpirationDate>2018-03-31</cmn:ExpirationDate>
          <cmn:ManufacturingDate>2017-09-18</cmn:ManufacturingDate>
        </ItemDetail>
      </snx:CommissionCommonAttributes>
    </snx:CommissionEvent>
    <snx:CommissionEvent>
      <snx:CommissionEventDetail>
        <cmn:EventDateTime>2017-09-18T01:42:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:SerialNumber>00503250210000045805</cmn:SerialNumber>
        <cmn:FilterValue>4</cmn:FilterValue>
        <cmn:PackagingLevel>CA</cmn:PackagingLevel>
        <cmn:BarcodeContent>(00)503250210000045805</cmn:BarcodeContent>
      </snx:CommissionEventDetail>
      <snx:CommissionCommonAttributes>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>L001</cmn:ProductionLineId>
        <cmn:LineManagerName>胡小芳</cmn:LineManagerName>
        <cmn:CompanyPrefix>0325021</cmn:CompanyPrefix>
      </snx:CommissionCommonAttributes>
    </snx:CommissionEvent>
    <snx:CommissionEvent>
      <snx:CommissionEventDetail>
        <cmn:EventDateTime>2017-09-18T01:44:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:SerialNumber>00803250210000051395</cmn:SerialNumber>
        <cmn:FilterValue>7</cmn:FilterValue>
        <cmn:PackagingLevel>PL</cmn:PackagingLevel>
        <cmn:BarcodeContent>(00)803250210000051395</cmn:BarcodeContent>
      </snx:CommissionEventDetail>
      <snx:CommissionCommonAttributes>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ProductionLineId>L001</cmn:ProductionLineId>
        <cmn:LineManagerName>胡小芳</cmn:LineManagerName>
        <cmn:CompanyPrefix>0325021</cmn:CompanyPrefix>
      </snx:CommissionCommonAttributes>
    </snx:CommissionEvent>
    <snx:AggregationEvent>
      <AggregationEventDetail>
        <cmn:EventDateTime>2017-09-18T01:45:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ParentSerialNumber>00803250210000051395</cmn:ParentSerialNumber>
        <cmn:PackedStatus>PARTIAL</cmn:PackedStatus>
        <cmn:Quantity>1</cmn:Quantity>
        <cmn:SerialNumberList>
          <cmn:SerialNumber>00503250210000045805</cmn:SerialNumber>
        </cmn:SerialNumberList>
      </AggregationEventDetail>
      <AggregationEventDetail>
        <cmn:EventDateTime>2017-09-18T01:43:20Z</cmn:EventDateTime>
        <cmn:EventTimeZoneOffset>+08:00</cmn:EventTimeZoneOffset>
        <cmn:EventLocation>6970021.75001.4</cmn:EventLocation>
        <cmn:ParentSerialNumber>00503250210000045805</cmn:ParentSerialNumber>
        <cmn:PackedStatus>PARTIAL</cmn:PackedStatus>
        <cmn:Quantity>1</cmn:Quantity>
        <cmn:SerialNumberList>
          <cmn:SerialNumber>0120325021115026213HYY8ZPNE0HX</cmn:SerialNumber>
        </cmn:SerialNumberList>
      </AggregationEventDetail>
    </snx:AggregationEvent>
  </MessageBody>
</SNXDispositionAssignedMessage>
```



