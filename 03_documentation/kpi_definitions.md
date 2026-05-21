# KPI Definitions

## On-Time Delivery %

Measures delivery SLA compliance and logistics efficiency.

```text
(Total On-Time Orders / Total Orders) * 100
```

Target Benchmark: 85%+

---

## Net Profit

```text
Revenue - (Item Cost + Shipping Cost)
```

Measures operational profitability after product and shipping expenses.

---

## Net Profit Margin %

```text
(Total Net Profit / Total Revenue) * 100
```

Tracks profitability efficiency relative to revenue generation.

---

## Product Damage Rate %

```text
(Damaged Orders / Total Orders) * 100
```

Measures the percentage of products damaged during shipment or handling.

---

## Return Rate %

```text
(Returned Orders / Total Orders) * 100
```

Measures reverse logistics activity and customer return frequency.

---

## Inventory Risk Logic

Warehouses are flagged as High Risk when:

```text
WarehouseInventoryLevel < SafetyStockLevel
```

This helps identify potential stockout exposure.