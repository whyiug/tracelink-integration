# 注意

> GCP，GLN，Address信息由客户提供；

# 范例文件



## 托盘出库文件



```xml
<?xml version="1.0" encoding="utf-8"?>
<som:SOMSalesShipmentMessage xmlns="urn:tracelink:mapper:sl:serialized_operations_manager" xmlns:som="urn:tracelink:mapper:sl:serialized_operations_manager" xmlns:cmn="urn:tracelink:mapper:sl:commontypes" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <som:ControlFileHeader>
    <cmn:FileSenderNumber>6970021750014</cmn:FileSenderNumber>
    <cmn:FileReceiverNumber>0325021000007</cmn:FileReceiverNumber>
    <cmn:FileControlNumber>1505699480</cmn:FileControlNumber>
    <cmn:FileDate>2017-09-18</cmn:FileDate>
    <cmn:FileTime>01:51:20Z</cmn:FileTime>
  </som:ControlFileHeader>
  <som:MessageBody>
    <cmn:DeliveryNumber>D1505699480</cmn:DeliveryNumber>
    <cmn:DeliveryCompleteFlag>true</cmn:DeliveryCompleteFlag>
    <som:OrderDetails>
      <cmn:TransactionIdentifier type="PO">A12345</cmn:TransactionIdentifier>
      <cmn:TransactionDate>2017-09-18</cmn:TransactionDate>
      <cmn:TransactionTime>01:49:20Z</cmn:TransactionTime>
      <cmn:ShipToCountryCode>US</cmn:ShipToCountryCode>
      <cmn:ShipFromCountryCode>CN</cmn:ShipFromCountryCode>
      <cmn:SalesDistributionType>EXPORTTRANSFER</cmn:SalesDistributionType>
      <cmn:OrderItemList>
        <cmn:OrderItem>
          <cmn:PackagingItemCode type="GTIN-14">20325021115026</cmn:PackagingItemCode>
          <cmn:LotNumber>B1505699480</cmn:LotNumber>
          <cmn:Quantity>1</cmn:Quantity>
        </cmn:OrderItem>
      </cmn:OrderItemList>
      <cmn:SenderInfo>
        <cmn:FromBusinessPartyInfo>
          <cmn:BusinessId type="GLN">0325021000007</cmn:BusinessId>
          <cmn:BusinessInfo>
            <cmn:BusinessName>Sagent Pharmaceuticals</cmn:BusinessName>
            <cmn:Street1>1901 North Roselle Road</cmn:Street1>
            <cmn:City>Schaumburg</cmn:City>
            <cmn:StateOrRegion>IL</cmn:StateOrRegion>
            <cmn:PostalCode>60195</cmn:PostalCode>
            <cmn:Country>US</cmn:Country>
          </cmn:BusinessInfo>
        </cmn:FromBusinessPartyInfo>
        <cmn:ShipFromLocationInfo>
          <cmn:FacilityId type="SGLN">6970021.75001.4</cmn:FacilityId>
          <cmn:LocationInfo>
            <cmn:BusinessName>Nanjing King-friend Biochemical_Nanjing</cmn:BusinessName>
            <cmn:Street1>16 Xuefu Road</cmn:Street1>
            <cmn:City>Nanjing</cmn:City>
            <cmn:StateOrRegion>32</cmn:StateOrRegion>
            <cmn:PostalCode>210061</cmn:PostalCode>
            <cmn:Country>CN</cmn:Country>
          </cmn:LocationInfo>
        </cmn:ShipFromLocationInfo>
      </cmn:SenderInfo>
      <cmn:ReceiverInfo>
        <cmn:ToBusinessPartyInfo>
          <cmn:BusinessId type="GLN">0325021000007</cmn:BusinessId>
          <cmn:BusinessInfo>
            <cmn:BusinessName>Sagent Pharmaceuticals</cmn:BusinessName>
            <cmn:Street1>1901 North Roselle Road</cmn:Street1>
            <cmn:City>Schaumburg</cmn:City>
            <cmn:StateOrRegion>IL</cmn:StateOrRegion>
            <cmn:PostalCode>60195</cmn:PostalCode>
            <cmn:Country>US</cmn:Country>
          </cmn:BusinessInfo>
        </cmn:ToBusinessPartyInfo>
        <cmn:ShipToLocationInfo>
          <cmn:FacilityId type="GLN">0842671116709</cmn:FacilityId>
          <cmn:LocationInfo>
            <cmn:BusinessName>Dohmen Life Science Services</cmn:BusinessName>
            <cmn:Street1>4580 S Mendenhall Rd</cmn:Street1>
            <cmn:City>Memphis</cmn:City>
            <cmn:StateOrRegion>TN</cmn:StateOrRegion>
            <cmn:PostalCode>38141</cmn:PostalCode>
            <cmn:Country>US</cmn:Country>
          </cmn:LocationInfo>
        </cmn:ShipToLocationInfo>
      </cmn:ReceiverInfo>
    </som:OrderDetails>
    <cmn:WarehouseOperatorName>Kang</cmn:WarehouseOperatorName>
    <som:AddPickedItems>
      <cmn:Serial format="AI(00)">00803250210000051395</cmn:Serial>
    </som:AddPickedItems>
  </som:MessageBody>
</som:SOMSalesShipmentMessage>

```





