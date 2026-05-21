# Data Architecture Notes

The project follows a Star Schema architecture to optimize analytical query performance and reporting scalability.

## Fact Table

Central transactional dataset containing:
- Orders
- Revenue
- Shipping Costs
- Delivery Metrics
- Return Information

## Dimension Tables

The model integrates supporting dimensions for:
- Customers
- Products
- Warehouses
- Suppliers
- Delivery Partners

This structure improves:
- Query performance
- KPI aggregation efficiency
- Dashboard scalability
- Reporting flexibility