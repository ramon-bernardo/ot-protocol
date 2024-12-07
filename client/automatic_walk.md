### Automatic Walk Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x64        | 100     | Game sever |

### Last version

| Field name | Field type                                   | Notes                                     |
| ---------- | -------------------------------------------- | ----------------------------------------- |
| length     | u8                                           | Number of elements in the following array |
| directions | Array of [Direction](..\common\direction.md) |                                           |
