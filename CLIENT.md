#### Leave Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x14        | 20      | Game sever |


#


#### Ping Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x1D        | 29      | Game sever |


#


#### Pong Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x1E        | 30      | Game sever |


#


#### Attack Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0xA1        | 161     | Game sever |

##### Last version

| Field name  | Field type | Notes                                          |
| ----------- | ---------- | ---------------------------------------------- |
| creature_id | u32        | Cancel previous attack if set to zero.         |
| creature_id | u32        | Same as above; zero if the attack is canceled. |

##### Below: Version 9.63

| Field name      | Field type | Notes                                  |
| --------------- | ---------- | -------------------------------------- |
| creature_id     | u32        | Cancel previous attack if set to zero. |
| attack_sequence | u32        | Zero if the attack is canceled.        |

##### Below: Version 8.60

| Field name  | Field type | Notes                                  |
| ----------- | ---------- | -------------------------------------- |
| creature_id | u32        | Cancel previous attack if set to zero. |


#


#### Accept Trade Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x7F        | 127     | Game sever |


#


#### Automatic Walk Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x64        | 100     | Game sever |

#### Last version

| Field name | Field type         | Notes                                     |
| ---------- | ------------------ | ----------------------------------------- |
| length     | u8                 | Number of elements in the following array |
| directions | Array of Direction |                                           |


#


#### Buy Npc Trade Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x7A        | 122     | Game sever |

##### Last version

| Field name       | Field type | Notes |
| ---------------- | ---------- | ----- |
| item_id          | u16        |       |
| count_or_subtype | u8         |       |
| amount           | u16        |       |
| ignore-capacity  | bool       |       |
| with_backpack    | bool       |       |


#


#### Equip Item Packet

|               | Hexadecimal | Decimal | Protocol   |
| ------------- | ----------- | ------- | ---------- |
| **Packet Id** | 0x77        | 119     | Game sever |

##### Last version

| Field name       | Field type | Notes |
| ---------------- | ---------- | ----- |
| item_id          | u16        |       |
| count_or_subtype | u8         |       |
