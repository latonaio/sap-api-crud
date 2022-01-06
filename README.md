# sap-api-crud
sap-api-crud は、[SAP API Business Hub](https://api.sap.com/) に掲載された CRUD APIs のうち、世界中の企業で繰り返し利用される、利用頻度の高いものをまとめたレポジトリです。  
本レポジトリでまとめられた API のリストに、現時点ではロジスティクス分野しか含められておりませんが、適宜、会計分野等のAPIが追加される予定です。  

## 前提条件  
sap-api-crud は、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  

## 各リソースの所在  
各リソースの所在は、次の箇所です。  

### Central Functions  

* [Classification](https://api.sap.com/api/OP_API_CLFN_CLASS_SRV/overview)
* [Characteristic](https://api.sap.com/api/OP_API_CLFN_CHARACTERISTIC_SRV/overview)
* [Bank Master](https://api.sap.com/api/OP_API_BANK_0002/overview)
* [Business Partner](https://api.sap.com/api/OP_API_BUSINESS_PARTNER_SRV/overview)

### Logistics  

* [Product Group](https://api.sap.com/api/OP_API_PRODUCTGROUP_SRV_0001/overview)
* [Product Master](https://api.sap.com/api/OP_API_PRODUCT_SRV_0001/overview)  
* [Product Master Class - Read](https://api.sap.com/api/OP_API_CLFN_PRODUCT_SRV/overview)
* [Batch Master Record](https://api.sap.com/api/OP_API_BATCH_SRV_0001/overview)  

### Inventory Management  

* [Material Stock - Read](https://api.sap.com/api/OP_API_MATERIAL_STOCK_SRV/overview)    
* [Reservation Document](https://api.sap.com/api/OP_API_RESERVATION_DOCUMENT_SRV_0001/overview)  
* [Inbound Delivery](https://api.sap.com/api/OP_API_INBOUND_DELIVERY_SRV_0002/overview)  
* [Material Documents - Read, Create](https://api.sap.com/api/OP_API_MATERIAL_DOCUMENT_SRV/overview)  
* [Physical Inventory](https://api.sap.com/api/OP_API_PHYSICAL_INVENTORY_DOC_SRV/overview)

### Sales Management

* [Business Partner(Customer)](https://api.sap.com/api/OP_API_BUSINESS_PARTNER_SRV/overview) 
* [Credit Management Master](https://api.sap.com/api/OP_API_CRDTMBUSINESSPARTNER_0001/overview)
* [Customer Material](https://api.sap.com/api/OP_API_CUSTOMER_MATERIAL_SRV_0001/overview)
* [Sales Pricing](https://api.sap.com/api/OP_API_SLSPRCGCONDITIONRECORD_SRV_0001/overview)
* [Sales Inquiry - Read](https://api.sap.com/api/OP_API_SALES_INQUIRY_SRV_0001/overview)
* [Sales Quotation](https://api.sap.com/api/OP_API_SALES_QUOTATION_SRV_0001/overview)
* [Sales Order](https://api.sap.com/api/OP_API_SALES_ORDER_SRV_0001/overview)  
* [Sales Contract](https://api.sap.com/api/OP_API_SALES_CONTRACT_SRV_0001/overview)
* [Sales Scheduling Agreement](https://api.sap.com/api/OP_API_SALES_SCHEDULING_AGREEMENT_0001/overview)
* [Outbound Delivery](https://api.sap.com/api/OP_API_OUTBOUND_DELIVERY_SRV_0002/overview)  
* [Customer Return](https://api.sap.com/api/OP_API_CUSTOMER_RETURN_SRV_0001/overview)
* [Billing Document - Read, Cancel, GetPDF](https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV_0001/overview)  

### Procurement Management  

* [Business Partner(Supplier)](https://api.sap.com/api/OP_API_BUSINESS_PARTNER_SRV/overview)  
* [Purchasing Source List](https://api.sap.com/api/OP_API_PURCHASING_SOURCE_SRV_0001/overview)  
* [Purchasing Info Record](https://api.sap.com/api/OP_API_INFORECORD_PROCESS_SRV_0001/overview)     
* [Purchase Requisition](https://api.sap.com/api/OP_API_PURCHASEREQ_PROCESS_SRV_0001/overview)  
* [Purchase Order](https://api.sap.com/api/OP_API_PURCHASEORDER_PROCESS_SRV_0001/overview)  
* [Purchase Contract](https://api.sap.com/api/OP_API_PURCHASECONTRACT_PROCESS_SRV/overview)
* [Purchase Scheduling Agreement](https://api.sap.com/api/OP_API_SCHED_AGRMT_PROCESS_SRV_0001/overview)
* [Supplier Invoice - Create, Read, Release, Reverse](https://api.sap.com/api/OP_API_SUPPLIERINVOICE_PROCESS_SRV/overview)  

### Production Management  

* [Bill of Material](https://api.sap.com/api/OP_API_BILL_OF_MATERIAL_SRV_0002/overview)  
* [Bill of Material Where Used List](https://api.sap.com/api/OP_API_BOM_WHERE_USED_SRV/overview)
* [Work Center](https://api.sap.com/api/OP_WORKCENTER_0001/overview)  
* [Production Routing](https://api.sap.com/api/OP_API_PRODUCTION_ROUTING_0001/overview)  
* [Planned Independent Requirement](https://api.sap.com/api/OP_API_PLND_INDEP_RQMT_SRV_0001/overview)   
* [Material Planning Data - Read](https://api.sap.com/api/OP_API_MRP_MATERIALS_SRV_01_0001/overview)   
* [Planned Order](https://api.sap.com/api/OP_PLANNEDORDER_0001/overview)
* [Production Order](https://api.sap.com/api/OP_API_PRODUCTION_ORDER_2_SRV_0001/overview)  
* [Production Order Confirmation](https://api.sap.com/api/OP_API_PROD_ORDER_CONFIRMATIO_2_SRV_0001/overview)

### Plant Maintenance  

* [Functional Location](https://api.sap.com/api/OP_API_FUNCTIONALLOCATION/overview) 
* [Equipment Master](https://api.sap.com/api/OP_API_EQUIPMENT/overview) 
* [Equipment Hierarchy](https://api.sap.com/api/OP_API_EQUIPMENTSTRUCLIST/overview)
* [Maintenance Plan](https://api.sap.com/api/OP_API_MAINTENANCEPLAN_0001/overview)
* [Maintenance Item](https://api.sap.com/api/OP_API_MAINTENANCEITEM_0001/overview)
* [Maintenance Notification](https://api.sap.com/api/OP_API_MAINTNOTIFICATION/overview)
* [Maintenance Order - Read](https://api.sap.com/api/OP_API_MAINTENANCEORDER_0001/overview) 
* [Maintenance Order Confirmation](https://api.sap.com/api/OP_API_MAINTORDERCONFIRMATION_0001/overview) 
* [Measuring Point](https://api.sap.com/api/OP_API_MEASURINGPOINT_0001/overview)
* [Measurement Document](https://api.sap.com/api/OP_API_MEASUREMENTDOCUMENT_0001/overview)


### Customer Service 

* [Service Order](https://api.sap.com/api/OP_API_SERVICE_ORDER_SRV_0001/overview)
* [Service Confirmation](https://api.sap.com/api/OP_API_SERVICE_CONFIRMATION_SRV_0001/overview)
