### Attack Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0xA1        | 161     | Game sever |

### Last version

| Field name  | Field type | Notes                                          |
| ----------- | ---------- | ---------------------------------------------- |
| creature_id | u32        | Cancel previous attack if set to zero.         |
| creature_id | u32        | Same as above; zero if the attack is canceled. |

### Below: Version 9.63

| Field name      | Field type | Notes                                  |
| --------------- | ---------- | -------------------------------------- |
| creature_id     | u32        | Cancel previous attack if set to zero. |
| attack_sequence | u32        | Zero if the attack is canceled.        |

### Below: Version 8.60

| Field name  | Field type | Notes                                  |
| ----------- | ---------- | -------------------------------------- |
| creature_id | u32        | Cancel previous attack if set to zero. |
