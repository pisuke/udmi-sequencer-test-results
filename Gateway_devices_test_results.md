- Date: 2024/02/27, 17:49:33
- UDMI version: 1.5.0-16-g48397c75b

## UDMI test results for direct and gateway devices

| Bucket | Feature | Stage | DDC&#x2011;1 | DDC&#x2011;9 | DDC&#x2011;3 | DDC&#x2011;4 | DDC&#x2011;5 | DDC&#x2011;10 | DDC&#x2011;12 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| image| | | <img src="img/products/FW-14.png">| <img src="img/products/FS-32.png"> | <img src="img/products/O3-DIN-CPU.png"> | <img src="img/products/eBCON-2.png"> | <img src="img/products/Mango_os.png"> | <img src="img/products/LROC_400.png"> | <img src="img/products/ALC_OFHI.png"> |
| make| | | JCI | JCI | Delta Controls Inc. | Delta Controls | RadixIoT | LOYTEC electronics | Automated Logic Corporation |
| model| | | FW14/08/28 | FS32/20 | O3&#x2011;DIN&#x2011;CPU | eBCON&#x2011;2 | Mango | LROC&#x2011;400 | OFHI |
| firmware| | | v1.0b23_GS | V3.0b61a_GS | 4.13.1.1017 (4130-001) | 4.14.0.2116 (4141-001) | 5.1.1-beta.2 | 8.2.0 | 108.04.20021 |
| test_date| | | 2024&#x2011;02&#x2011;14T09:12:47Z | 2024&#x2011;02&#x2011;15T14:00:51Z | 2024&#x2011;02&#x2011;26T13:46:12Z | 2024&#x2011;02&#x2011;15T16:17:51Z | 2024&#x2011;02&#x2011;12T09:02:59Z | 2024&#x2011;01&#x2011;30T19:02:54Z | 2024&#x2011;02&#x2011;28T17:08:52Z |
| manual | is_iotcore_gateway | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/no.png">|<img src="img/yes.png">|
| manual | udmi.native | beta |<img src="img/no.png">|<img src="img/no.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.manual | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.clearblade_connected | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.mqtt.mqtt_311 | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.mqtt.mqtt_tls | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.mqtt.mqtt_sustained | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.mqtt.mqtt_reconnect | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | endpoint.mqtt.mqtt_exponential_backoff | beta |<img src="img/no.png">|<img src="img/no.png">|<img src="img/no.png">|<img src="img/no.png">|<img src="img/yes.png">|<img src="img/no.png">|<img src="img/no.png">|
| manual | endpoint.mqtt.mqtt_auth_jwt | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | datapoint_mapping | beta |<img src="img/no.png">|<img src="img/no.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| manual | time_utc_format | beta |<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|<img src="img/yes.png">|
| pointset | pointset_publish | beta | <img src="img/yes.png"> | <img src="img/yes.png"> | <img src="img/yes.png"> | <img src="img/yes.png"> | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png">|
| pointset | pointset_publish_interval | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/yes.png"> |<img src="img/no.png">|
| pointset | pointset_remove_point | beta | <img src="img/no.png"> |<img src="img/no.png">| <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| pointset | pointset_request_extraneous | beta | <img src="img/no.png"> |<img src="img/no.png">| <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/no.png">|<img src="img/skip.png">|
| pointset | pointset_sample_rate | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/no.png">|
| system | broken_config | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/no.png">|
| system | config_logging.receive | beta | <img src="img/no.png"> |<img src="img/yes.png"> | <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/no.png">|<img src="img/no.png">|
| system | config_logging.parse | beta | <img src="img/no.png"> |<img src="img/yes.png"> | <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/no.png">|<img src="img/yes.png">|
| system | config_logging.apply | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/no.png"> |<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/no.png">|<img src="img/yes.png">|
| system | device_config_acked | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| system | extra_config | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| system | state_make_model | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| system | state_software | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| system | system_last_update | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| system | valid_serial_no | beta | <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">| <img src="img/yes.png"> |<img src="img/yes.png">|<img src="img/yes.png">|
| unknown | family_ether_addr | beta | <img src="img/no.png"> |<img src="img/no.png">| <img src="img/no.png">|<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/no.png">|<img src="img/no.png">|
| unknown | family_ipv4_addr | beta | <img src="img/no.png"> |<img src="img/no.png">| <img src="img/no.png">|<img src="img/no.png">| <img src="img/yes.png"> |<img src="img/no.png">|<img src="img/no.png">|
| notes |  |  |  |  |  |  |  |  |  |
