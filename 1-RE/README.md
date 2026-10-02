# Lab 1 – Requirements Engineering & UML Use-Case Modelling

**Name:** Mutnuri Nagavalli Sri Sravya  
**SRN:** PES1UG24CS284

## Problem Statement #38
**Dropshipping Inventory & Order Orchestrator**

## Actors
- E-Commerce Platform
- Supplier Partner
- E-Store Owner

## Primary Use Cases
- Receive & Process Order
- Verify Supplier Inventory
- Split Multi-Vendor Order
- Dispatch Supplier Purchase Order
- Update Order Status
- Track Shipment
- View Order & Fulfillment Status

## UML Relationships
- `Receive & Process Order` «include» `Verify Supplier Inventory`
- `Receive & Process Order` «include» `Dispatch Supplier Purchase Order`
- `Split Multi-Vendor Order` «extend» `Receive & Process Order`

## Submission Files
- `RequirementsTable.pdf`
- `Use_Case_Flow.pdf`
- `PES10UG24CS304_SE_Lab01.drawio.pdf` — add your exported Draw.io PDF here

