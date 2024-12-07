### Automatic Walk Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x64        | 100     | Game sever |

### Last version

| Field name | Field type         | Notes                                     |
| ---------- | ------------------ | ----------------------------------------- |
| length     | u8                 | Number of elements in the following array |
| directions | Array of Direction |                                           |

| Direction Id | Direction | Notes |
| ------------ | --------- | ----- |
| 0            | North     |       |
| 1            | East      |       |
| 2            | South     |       |
| 3            | West      |       |
| 4            | Southwest |       |
| 5            | Southeast |       |
| 6            | Northwest |       |
| 7            | Northeast |       |
