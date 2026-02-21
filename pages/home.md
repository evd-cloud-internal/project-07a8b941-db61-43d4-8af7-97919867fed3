---
name: Home
assetId: 54364a06-e932-4bd7-b1cb-9e8c002d2359
type: page
---

# Welcome

This is your new project's homepage. Edit this file to get started.

{% area_chart
  data="demo_daily_orders"
  x="avg_transaction_value"
  y="total_sales"
/%}

# Combo Charts

{% date_grain_selector
  id="something"
/%}

{% table
  data="demo_items"
%}
{% /table %}