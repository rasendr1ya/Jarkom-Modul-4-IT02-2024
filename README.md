# Praktikum Modul 04 Komunikasi Data dan Jaringan Komputer
## Kelompok IT02
### Anggota Kelompok :
|             Nama              |     NRP    |
|-------------------------------|------------|
| Gallant Damas Hayuaji         | 5027231037 |
| Danar Bagus Rasendriya        | 5027231055 |

### Note
Prefix IP: `192.234.x.x`

**GNS3** menggunakan **CIDR**.

**Cisco Packet Tracer** menggunakan **VLSM**.

***
## GNS3
### Topologi
![image](https://github.com/user-attachments/assets/fcfbe360-cf50-4470-9818-a804875d05c7)

### Sheets dan Pembagian Subnet GNS3
![image](https://github.com/user-attachments/assets/7051942f-b0c3-4b4f-a7b2-ed6c85a2d9a8)

![image](https://github.com/user-attachments/assets/3bd37376-94e4-4d49-a448-0eb02be8a20a)


### Penggabungan GNS3
1. Gabungan 1

|Subnet|Gabungan|Hasil Netmask|
|-|-|-|
|B1|A22/25 + A21/30|/24|

![B1](https://github.com/user-attachments/assets/a481f010-ee79-4ac6-b0f5-ae38b1327073)

2. Gabungan 2

|Subnet|Gabungan|Hasil Netmask|
|-|-|-|
|C1|A5/29 + A6/26|/25|
|C2|B1/24 + A20/23|/22|

![C1](https://github.com/user-attachments/assets/124493ba-ccfa-4e62-9c23-ee27826967a2)

3. Gabungan 3

|Subnet|Gabungan|Hasil Netmask|
|-|-|-|
|D1|C2/22 + A19/21|/20|
|D2|C1/25 + A4/29|/24|

![D1](https://github.com/user-attachments/assets/a2978c15-51db-4d56-bfb7-d710f451692f)

4. Gabungan 4

|Subnet|Gabungan|Hasil Netmask|
|-|-|-|
|E1|D2/24 + A3/23|/22|
|E2|A10/30 + A11/22|/21|
|E3|A12/30 + A13/26|/25|
|E4|A14/30 + A15/23|/22|
|E5|A17/29 + D1/20|/19|

![E1](https://github.com/user-attachments/assets/37b5083a-fcc7-409a-a9d7-9f6dab837d14)

5. Gabungan 5

6. Gabungan 6

7. Gabungan 7

8. Gabungan 8

9. Gabungan 9

10. Gabungan 10

### Tree CIDR GNS3

***
## Cisco Packet Tracer
![Screenshot 2024-11-17 at 21 19 41](https://github.com/user-attachments/assets/5cf2d163-59f9-447f-bae6-c1df892dd6eb)

***
## Sheets & Subnetting

### Cisco Packet Tracer
![Screenshot 2024-11-17 at 22 28 05](https://github.com/user-attachments/assets/ac428c21-8d5c-4c1f-bfe8-ee8c3d977b17)

***
## Tree CPT-VLSM
![Jarkom_Modul4_VLSM_Danar](https://github.com/user-attachments/assets/8d66dcd6-da3c-4cd3-9641-3bb6adb270f7)
