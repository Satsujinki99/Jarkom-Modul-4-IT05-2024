# Jarkom-Modul-4-IT05-2024

| Nama | NRP | Aplikasi | Metode |
| ---- | :-: | -------- | ------ |
| Adlya Isriena Aftarisya | 5027231066 | GNS3 | CIDR |
| Furqon Aryadana | 5027231024 | CPT | VLSM |

## CIDR (GNS)
### Topologi
![image](https://github.com/user-attachments/assets/158bbfd2-62b3-4029-9340-e750ac373fe2)

### Penggabungan
#### Langkah 1
![image](https://github.com/user-attachments/assets/3b1cebd6-6744-4cb3-8c3d-4177265e8bc1)

#### Langkah 2
<img width="782" alt="image" src="https://github.com/user-attachments/assets/a7a11052-6356-4d80-8c2c-b1a4138aa482">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>B1</td>
      <td>A22</td>
      <td>/25</td>
      <td>A21</td>
      <td>/30</td>
      <td>/24</td>
    </tr>
  </tbody>
</table>

#### Langkah 3
<img width="762" alt="image" src="https://github.com/user-attachments/assets/8a3411d8-f92c-4af4-9121-f9b84f54220c">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>C1</td>
      <td>A1</td>
      <td>/26</td>
      <td>A3</td>
      <td>/30</td>
      <td>/25</td>
    </tr>
    <tr>
      <td>C2</td>
      <td>B1</td>
      <td>/24</td>
      <td>A20</td>
      <td>/23</td>
      <td>/22</td>
    </tr>
  </tbody>
</table>

#### Langkah 4
<img width="761" alt="image" src="https://github.com/user-attachments/assets/b02a8651-8479-4b64-a1cb-1a0569be3932">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>D1</td>
      <td>C1</td>
      <td>/25</td>
      <td>A2</td>
      <td>/29</td>
      <td>/24</td>
    </tr>
    <tr>
      <td>D2</td>
      <td>C2</td>
      <td>/22</td>
      <td>A19</td>
      <td>/21</td>
      <td>/20</td>
    </tr>
  </tbody>
</table>

#### Langkah 5
<img width="762" alt="image" src="https://github.com/user-attachments/assets/f1159600-89e6-4000-9c15-ef02ceb0f43a">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>E1</td>
      <td>D1</td>
      <td>/24</td>
      <td>A6</td>
      <td>/23</td>
      <td>/22</td>
    </tr>
    <tr>
      <td>E2</td>
      <td>D2</td>
      <td>/20</td>
      <td>A18</td>
      <td>/28</td>
      <td>/19</td>
    </tr>
    <tr>
      <td>E3</td>
      <td>A14</td>
      <td>/22</td>
      <td>A11</td>
      <td>/30</td>
      <td>/21</td>
    </tr>
    <tr>
      <td>E4</td>
      <td>A15</td>
      <td>/26</td>
      <td>A12</td>
      <td>/30</td>
      <td>/25</td>
    </tr>
    <tr>
      <td>E5</td>
      <td>A16</td>
      <td>/23</td>
      <td>A13</td>
      <td>/30</td>
      <td>/22</td>
    </tr>
  </tbody>
</table>

#### Langkah 6
<img width="762" alt="image" src="https://github.com/user-attachments/assets/accd234a-401e-4d22-890e-cf8b9d2e77d2">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>F1</td>
      <td>E1</td>
      <td>/22</td>
      <td>A5</td>
      <td>/30</td>
      <td>/21</td>
    </tr>
    <tr>
      <td>F2</td>
      <td>E2</td>
      <td>/19</td>
      <td>A17</td>
      <td>/29</td>
      <td>/18</td>
    </tr>
    <tr>
      <td>F3</td>
      <td>E3</td>
      <td>/21</td>
      <td>E5</td>
      <td>/22</td>
      <td>/20</td>
    </tr>
    <tr>
      <td>F4</td>
      <td>A4</td>
      <td>/27</td>
      <td>A7</td>
      <td>/30</td>
      <td>/26</td>
    </tr>
  </tbody>
</table>

#### Langkah 7
<img width="762" alt="image" src="https://github.com/user-attachments/assets/af919d52-a293-49d8-bbcc-8287cfcc49db">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>G1</td>
      <td>F1</td>
      <td>/21</td>
      <td>F4</td>
      <td>/26</td>
      <td>/20</td>
    </tr>
    <tr>
      <td>G2</td>
      <td>F3</td>
      <td>/20</td>
      <td>E4</td>
      <td>/25</td>
      <td>/19</td>
    </tr>
  </tbody>
</table>

#### Langkah 8
<img width="762" alt="image" src="https://github.com/user-attachments/assets/c70b8911-9d67-40c8-a590-5dc6a5596fe4">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>H1</td>
      <td>G1</td>
      <td>/20</td>
      <td>A8</td>
      <td>/30</td>
      <td>/19</td>
    </tr>
    <tr>
      <td>H2</td>
      <td>G2</td>
      <td>/19</td>
      <td>A10</td>
      <td>/30</td>
      <td>/18</td>
    </tr>
    <tr>
      <td>H3</td>
      <td>F2</td>
      <td>/18</td>
      <td>A9</td>
      <td>/30</td>
      <td>/17</td>
    </tr>
  </tbody>
</table>

#### Langkah 9
<img width="762" alt="image" src="https://github.com/user-attachments/assets/be824aab-4aa8-4c04-8c2c-2ba7dbd192ad">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>I1</td>
      <td>H2</td>
      <td>/18</td>
      <td>H3</td>
      <td>/17</td>
      <td>/16</td>
    </tr>
  </tbody>
</table>

#### Langkah 10
<img width="761" alt="image" src="https://github.com/user-attachments/assets/a34b5209-c856-4663-84b3-1e1e05db7065">

<table>
  <thead>
    <tr>
      <th rowspan="3">Subnet</th>
      <th colspan="4">Gabungan dari</th>
      <th rowspan="3">Netmask Akhir</th>
    </tr>
    <tr>
      <th colspan="2">1</th>
	  <th colspan="2">2</th>
    </tr>
	<tr>
	<th>Subnet</th>
      <th>Netmask</th>
      <th>Subnet</th>
      <th>Netmask</th>
	</tr>
  </thead>
  <tbody>
    <tr>
      <td>J1</td>
      <td>H1</td>
      <td>/19</td>
      <td>I1</td>
      <td>/16</td>
      <td>/15</td>
    </tr>
  </tbody>
</table>

### Tree
<img width="1218" alt="image" src="https://github.com/user-attachments/assets/0f58a47c-77a6-4591-85b8-978be73a3541">

### Pembagian IP

Prefix IP : **10.66**

| Subnet | Network ID     | Netmask         | Broadcast      | Range IP                        |
| ------ | -------------- | --------------- | -------------- | ------------------------------- |
| A1     | 10.67.2.0      | 255.255.255.192 | 10.67.2.63     | 10.67.2.1 - 10.67.2.62          |
| A2     | 10.67.2.128    | 255.255.255.248 | 10.67.2.135    | 10.67.2.129 - 10.67.2.134       |
| A3     | 10.67.2.64     | 255.255.255.252 | 10.67.2.67     | 10.67.2.65 - 10.67.2.66         |
| A4     | 10.67.8.0      | 255.255.255.224 | 10.67.8.31     | 10.67.8.1 - 10.67.8.30          |
| A5     | 10.67.4.0      | 255.255.255.252 | 10.67.4.3      | 10.67.4.1 - 10.67.4.2           |
| A6     | 10.67.0.0      | 255.255.254.0   | 10.67.1.255    | 10.67.0.1 - 10.67.1.254         |
| A7     | 10.67.8.32     | 255.255.255.252 | 10.67.8.35     | 10.67.8.33 - 10.67.8.34         |
| A8     | 10.67.16.0     | 255.255.255.252 | 10.67.16.3     | 10.67.16.1 - 10.67.16.2         |
| A9     | 10.66.64.0     | 255.255.255.252 | 10.66.64.3     | 10.66.64.1 - 10.66.64.2         |
| A10    | 10.66.160.0    | 255.255.255.252 | 10.66.160.3    | 10.66.160.1 - 10.66.160.2       |
| A11    | 10.66.132.0    | 255.255.255.252 | 10.66.132.3    | 10.66.132.1 - 10.66.132.2       |
| A12    | 10.66.144.64   | 255.255.255.252 | 10.66.144.67   | 10.66.144.65 - 10.66.144.66     |
| A13    | 10.66.138.0    | 255.255.255.252 | 10.66.138.3    | 10.66.138.1 - 10.66.138.2       |
| A14    | 10.66.128.0    | 255.255.252.0   | 10.66.131.255  | 10.66.128.1 - 10.66.131.254     |
| A15    | 10.66.144.0    | 255.255.255.192 | 10.66.144.63   | 10.66.144.1 - 10.66.144.62      |
| A16    | 10.66.136.0    | 255.255.254.0   | 10.66.137.255  | 10.66.136.1 - 10.66.137.254     |
| A17    | 10.66.32.0     | 255.255.255.248 | 10.66.32.7     | 10.66.32.1 - 10.66.32.6         |
| A18    | 10.66.16.0     | 255.255.255.240 | 10.66.16.15    | 10.66.16.1 - 10.66.16.14        |
| A19    | 10.66.0.0      | 255.255.248.0   | 10.66.7.255    | 10.66.0.1 - 10.66.7.254         |
| A20    | 10.66.8.0      | 255.255.254.0   | 10.66.9.255    | 10.66.8.1 - 10.66.9.254         |
| A21    | 10.66.10.128   | 255.255.255.252 | 10.66.10.131   | 10.66.10.129 - 10.66.10.130     |
| A22    | 10.66.10.0     | 255.255.255.128 | 10.66.10.127   | 10.66.10.1 - 10.66.10.126       |

### Network Configuration
#### Hololive
```
auto lo
iface lo inet loopback

auto eth0
iface eth0  inet dhcp

#A8
auto eth1
iface eth1 inet static
    address 10.67.16.1
    netmask 255.255.255.252

#A9
auto eth3
iface eth3 inet static
    address 10.66.64.1
    netmask 255.255.255.252

#A10
auto eth2
iface eth2 inet static
    address 10.66.160.1
    netmask 255.255.255.252
```

#### Holo-EN
```
auto lo
iface lo inet loopback

#A8
auto eth0
iface eth0 inet static
    address 10.67.16.2
    netmask 255.255.255.252
    gateway 10.67.16.1

#A7
auto eth2
iface eth2 inet static
    address 10.67.8.33
    netmask 255.255.255.252

#A5
auto eth1
iface eth1 inet static
    address 10.67.4.1
    netmask 255.255.255.252
```

#### Holo-Myth
```
auto lo
iface lo inet loopback

#A5
auto eth0
iface eth0 inet static
    address 10.67.4.2
    netmask 255.255.255.252
    gateway 10.67.4.1

#A6
auto eth1
iface eth1 inet static
    address 10.67.0.1
    netmask 255.255.254.0

#A2
auto eth2
iface eth2 inet static
    address 10.67.2.129
    netmask 255.255.255.248
```

#### Gura_Ame_Ina (Client)
```
#A6
auto eth0
iface eth0 inet static
    address 10.67.0.2
    netmask 255.255.254.0
    gateway 10.67.0.1
```
#### Kiara_Caili (Client)
```
#A6
auto eth0
iface eth0 inet static
    address 10.67.0.3
    netmask 255.255.254.0
    gateway 10.67.0.1
```

#### HoloAdvent
```
auto lo
iface lo inet loopback

#A7
auto eth0
iface eth0 inet static
    address 10.67.8.34
    netmask 255.255.255.252
    gateway 10.67.8.33

#A4
auto eth1
iface eth1 inet static
    address 10.67.8.1
    netmask 255.255.255.224
```

#### FuwaMoco (Client)
```
#A4
auto eth0
iface eth0 inet static
    address 10.67.8.2
    netmask 255.255.255.224
    gateway 10.67.8.1
```

#### Shiori_Nerissa (Client)
```
#A4
auto eth0
iface eth0 inet static
    address 10.67.8.3
    netmask 255.255.255.224
    gateway 10.67.8.1
```

#### Biboo (Client)
```
#A4
auto eth0
iface eth0 inet static
    address 10.67.8.4
    netmask 255.255.255.224
    gateway 10.67.8.1
```

#### Project-Hope
```
auto lo
iface lo inet loopback

#A2
auto eth0
iface eth0 inet static
    address 10.67.2.130
    netmask 255.255.255.248
    gateway 10.67.2.129

#A3
auto eth1
iface eth1 inet static
    address 10.67.2.64
    netmask 255.255.255.252
```

#### Irys (Client)
```
#A3
auto eth0
iface eth0 inet static
    address 10.67.2.65
    netmask 255.255.255.252
    gateway 10.67.2.64
```

#### Holo-Council
```
auto lo
iface lo inet loopback

#A2
auto eth0
iface eth0 inet static
    address 10.67.2.131
    netmask 255.255.255.248
    gateway 10.67.2.129

#A1
auto eth1
iface eth1 inet static
    address 10.67.2.1
    netmask 255.255.255.248
```

#### Kronii_Mumei (Client)
```
#A1
auto eth0
iface eth0 inet static
    address 10.67.2.2
    netmask 255.255.255.248
    gateway 10.67.2.1
```

#### Bae_Fauna (Client)
```
#A1
auto eth0
iface eth0 inet static
    address 10.67.2.3
    netmask 255.255.255.248
    gateway 10.67.2.1
```

