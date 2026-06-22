# Dataset-sci-internship
Dataset: Cold Chain Logistics Temperature Logs

| Field Name            | Type     | Description                                                                                                |
| --------------------- | -------- | ---------------------------------------------------------------------------------------------------------- |
| log\_id               | string   | Unique identifier for each temperature and humidity log entry                                              |
| shipment\_id          | string   | Unique identifier for the shipment associated with this log entry                                          |
| container\_id         | string   | Unique identifier for the container or storage unit being monitored                                        |
| sensor\_id            | string   | Unique identifier for the sensor device recording the data                                                 |
| timestamp             | datetime | Date and time when the temperature and humidity were recorded (in UTC)                                     |
| temperature\_celsius  | float    | Measured temperature in degrees Celsius                                                                    |
| humidity\_percent     | float    | Measured relative humidity as a percentage (0-100%)                                                        |
| location\_latitude    | float    | Latitude coordinate of the sensor at the time of recording                                                 |
| location\_longitude   | float    | Longitude coordinate of the sensor at the time of recording                                                |
| location\_description | string   | Textual description of the sensor's location (e.g., warehouse, truck, facility name)                       |
| alarm\_triggered      | boolean  | Indicates whether an alarm was triggered due to temperature or humidity out of range                       |
| alarm\_type           | string   | Type of alarm triggered, if any (e.g., temperature\_high, temperature\_low, humidity\_high, humidity\_low) |
| operator\_id          | string   | Identifier of the operator responsible at the time of recording (if applicable)                            |
| remarks               | string   | Additional notes or comments about the log entry                                                           |

Source
Dataset: Cold Chain Logistics Temperature Logs (Synthetic)
Source: GoMask AI Marketplace
URL: https://gomask.ai/marketplace/datasets/cold-chain-logistics-temperature-logs
Records: 200
Format: CSV
