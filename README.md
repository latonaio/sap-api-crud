# sap-api-crud
sap-api-crud は、[SAP API Business Hub](https://api.sap.com/) に掲載された CRUD APIs のうち、世界中の企業で繰り返し利用される、利用頻度の高いものをまとめたレポジトリです。  
本レポジトリでまとめられた API のリストに、現時点ではロジスティクス分野しか含められておりませんが、適宜、会計分野等のAPIが追加される予定です。  

## 前提条件  
sap-api-crud は、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。  
クラウド版APIを利用する場合は、ご注意ください。  

## 各リソースの所在  
各リソースの所在は、次の箇所です。  

### Logistics  

* [Product Master](https://api.sap.com/api/OP_API_PRODUCT_SRV_0001/overview)  
* [Batch Master Record](https://api.sap.com/api/OP_API_BATCH_SRV_0001/overview)  

### Inventory Management  

* [Material Stock - Read](https://api.sap.com/api/OP_API_MATERIAL_STOCK_SRV/overview)    
* [Reservation Document](https://api.sap.com/api/OP_API_RESERVATION_DOCUMENT_SRV_0001/overview)  
* [Inbound Delivery](https://api.sap.com/api/OP_API_INBOUND_DELIVERY_SRV_0002/overview)  
* [Material Documents - Read, Create](https://api.sap.com/api/OP_API_MATERIAL_DOCUMENT_SRV/overview)  

### Sales Management

* [Business Partner(Customer)](https://api.sap.com/api/OP_API_BUSINESS_PARTNER_SRV/overview) 
* [Sales Pricing](https://api.sap.com/api/OP_API_SLSPRCGCONDITIONRECORD_SRV_0001/overview)
* [Sales Inquiry](https://api.sap.com/api/OP_API_SALES_INQUIRY_SRV_0001/overview)
* [Sales Quotation](https://api.sap.com/api/OP_API_SALES_QUOTATION_SRV_0001/overview)
* [Sales Order](https://api.sap.com/api/OP_API_SALES_ORDER_SRV_0001/overview)  
* [Sales Contract](https://api.sap.com/api/OP_API_SALES_CONTRACT_SRV_0001/overview)
* [Outbound Delivery](https://api.sap.com/api/OP_API_OUTBOUND_DELIVERY_SRV_0002/overview)  
* [Customer Return](https://api.sap.com/api/OP_API_CUSTOMER_RETURN_SRV_0001/overview)
* [Billing Document - Read, Cancel](https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV_0001/overview)  

### Procurement Management  

* [Business Partner(Supplier)](https://api.sap.com/api/OP_API_BUSINESS_PARTNER_SRV/overview)  
* [Purchasing Source List](https://api.sap.com/api/OP_API_PURCHASING_SOURCE_SRV_0001/overview)  
* [Purchasing Info Record](https://api.sap.com/api/OP_API_INFORECORD_PROCESS_SRV_0001/overview)     
* [Purchase Requisition](https://api.sap.com/api/OP_API_PURCHASEREQ_PROCESS_SRV_0001/overview)  
* [Purchase Order](https://api.sap.com/api/OP_API_PURCHASEORDER_PROCESS_SRV_0001/overview)  
* [Supplier Invoice](https://api.sap.com/api/OP_API_SUPPLIERINVOICE_PROCESS_SRV/overview)  

### Production Management  

* [Bill of Material](https://api.sap.com/api/OP_API_BILL_OF_MATERIAL_SRV_0002/overview)  
* [Work Center](https://api.sap.com/api/OP_WORKCENTER_0001/overview)  
* [Production Routing](https://api.sap.com/api/OP_API_PRODUCTION_ROUTING_0001/overview)  
* [Planned Independent Requirement](https://api.sap.com/api/OP_API_PLND_INDEP_RQMT_SRV_0001/overview)   
* [Material Planning Data - Read](https://api.sap.com/api/OP_API_MRP_MATERIALS_SRV_01_0001/overview)   
* [Production Order](https://api.sap.com/api/OP_API_PRODUCTION_ORDER_2_SRV_0001/overview)  
* [Production Order Confirmation](https://api.sap.com/api/OP_API_PROD_ORDER_CONFIRMATIO_2_SRV_0001/overview)

### Plant Management  

* [Equipment Master](https://api.sap.com/api/OP_API_EQUIPMENT/overview)  