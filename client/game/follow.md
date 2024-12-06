### Follow Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0xA2        | 162     | Game sever |

### Last version

| Field name  | Field type | Notes                                          |
| ----------- | ---------- | ---------------------------------------------- |
| creature_id | u32        | Cancel previous follow if set to zero.         |
| creature_id | u32        | Same as above; zero if the follow is canceled. |

### Above: Version 9.63

| Field name      | Field type | Notes                                  |
| --------------- | ---------- | -------------------------------------- |
| creature_id     | u32        | Cancel previous follow if set to zero. |
| follow_sequence | u32        | Zero if the follow is canceled.        |

### Above: Version 8.60

| Field name  | Field type | Notes                                  |
| ----------- | ---------- | -------------------------------------- |
| creature_id | u32        | Cancel previous follow if set to zero. |
