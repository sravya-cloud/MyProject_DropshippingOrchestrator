# 2 - Architectural Diagram

## Project
Dropshipping Inventory & Order Orchestrator

## Architecture
The system uses a **Microservices Architecture**.

The architecture separates the major system functions into independent components/services. 
This allows individual services to be developed, deployed and scaled independently.

## Components

The component diagram contains the following five main components:

1. **Order Manager Component**
   - Coordinates order processing and service requests.

2. **Payment Service Component**
   - Handles payment-processing requests.

3. **Supplier Inventory Service**
   - Verifies supplier SKU inventory availability.

4. **Supplier Purchase Order Service**
   - Creates and dispatches supplier purchase orders to suppliers.

5. **Shipment Tracking Service**
   - Handles shipment tracking information and order status updates.

## External Systems

- **E-Commerce Platform**
  - Sends order information to the Order Manager through the Order Webhook API.
  - Receives order/fulfillment status updates.

- **Supplier Partner**
  - Provides inventory information.
  - Receives supplier purchase orders.

## Interfaces

The component diagram represents the following interfaces:

- Order Webhook API
- Order Status API
- Payment Processing API
- Inventory Verification API
- Purchase Order API
- Shipment Tracking API
- Supplier Inventory API
- Supplier PO API

## Architectural Justification

The Microservices architecture was selected because the system contains multiple independent business functions such as order processing, payment processing, supplier inventory verification, purchase-order dispatch and shipment tracking.

The architecture provides:
- Independent scaling of services
- Fault isolation
- Independent deployment
- Controlled communication through service APIs
- Better performance by allowing frequently used services to scale independently

## Files

| File | Description |
|---|---|
| `Dropshipping_Component_Diagram.pdf` | UML component diagram for the system |
| `Dropshipping_Lab3_Component_Diagram_Clean.drawio` | Editable Draw.io source file |
| `Dropshipping_Lab3_Architecture_Justification.pdf` | One-page architectural justification |

## Lab Requirement

The component diagram contains at least five components and four interfaces, with provided/required interface notation as required for Lab 3.
