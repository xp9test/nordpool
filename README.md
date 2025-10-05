⚡ Nordpool-Based Automations for Home Assistant
This repository contains three YAML-based solutions for Home Assistant that leverage Nordpool's 15-minute electricity pricing data to optimize device control and visualization.

📁 Contents

| File | Description |
|------|-------------|
| `nordpool_price_based_on_15min.yaml` | Automation blueprint that controls a device based on the cheapest hours of the day. You define how many hours per day the device should be active, and the automation selects the cheapest 15-minute intervals accordingly. |
| `nordpool_price_based_on_15min_range.yaml` | Similar to the first blueprint, but adds time window constraints. You can define `hour_min` and `hour_max` to restrict when the device is allowed to operate. |
| `nordpool_dashboard_cheapest.yaml` | ApexCharts-based dashboard card that visualizes today's energy prices. It highlights the cheapest 15-minute intervals with red markers, making it easy to track optimal usage times. |


🚀 Features
Fully dynamic: adapts to daily Nordpool pricing

Granular control: works with 15-minute intervals

Time window support (optional)

Visual feedback via ApexCharts

Designed for energy cost optimization

🧠 Logic Highlights
Calculates cheapest intervals based on current day's pricing

Supports ranking logic (hour_rank) to define how many hours to activate

Optional time filtering to restrict activation window

Dashboard shows real-time price trends and cheapest slots

📦 Requirements
Home Assistant with Nordpool integration

ApexCharts custom card (for dashboard)

YAML blueprints imported via Home Assistant UI or file system

📸 Preview
<img width="1078" height="1027" alt="image" src="https://github.com/user-attachments/assets/f47c79d9-1cda-4d92-9fed-b434044c6580" />

<img width="1051" height="838" alt="image" src="https://github.com/user-attachments/assets/c1d7728f-0710-497c-9e7e-abcd68436c3e" />

<img width="512" height="744" alt="image" src="https://github.com/user-attachments/assets/d8ee5b63-30eb-4e95-bdfa-b5e7d6bd0192" />


[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=BE7ALR22TYABJ&no_recurring=1&item_name=Help+me+to+get+my+coffee&currency_code=EUR)

