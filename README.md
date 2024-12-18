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

#### Holo-JP
```
auto lo
iface lo inet loopback

#A9
auto eth0
iface eth0 inet static
    address 10.66.64.2
    netmask 255.255.255.252
    gateway 10.66.64.1

#A17
auto eth1
iface eth1 inet static
    address 10.66.32.1
    netmask 255.255.255.248
```

### DEV_IS
```
auto lo
iface lo inet loopback

#A17
auto eth0
iface eth0 inet static
    address 10.66.32.2
    netmask 255.255.255.248
    gateway 10.66.32.1

#A18
auto eth1
iface eth1 inet static
    address 10.66.16.1
    netmask 255.255.255.240
```

#### Ririka_Raden (Client)
```
#A18
auto eth0
iface eth0 inet static
    address 10.66.16.2
    netmask 255.255.255.240
    gateway 10.66.16.1
```

#### Ao (Client)
```
#A18
auto eth0
iface eth0 inet static
    address 10.66.16.3
    netmask 255.255.255.240
    gateway 10.66.16.1
```

#### Hajime_Kanade (Client)
```
#A18
auto eth0
iface eth0 inet static
    address 10.66.16.4
    netmask 255.255.255.240
    gateway 10.66.16.1
```

#### GEN:0
```
auto lo
iface lo inet loopback

#A17
auto eth0
iface eth0 inet static
    address 10.66.32.3
    netmask 255.255.255.248
    gateway 10.66.32.1

#A19
auto eth1
iface eth1 inet static
    address 10.66.0.1
    netmask 255.255.255.248
```

#### MiComet (Client)
```
#A19
auto eth0
iface eth0 inet static
    address 10.66.0.2
    netmask 255.255.255.248
    gateway 10.66.0.1
```

#### Sora_Robo_AZKi (Client)
```
#A19
auto eth0
iface eth0 inet static
    address 10.66.0.3
    netmask 255.255.255.248
    gateway 10.66.0.1
```

#### GEN:1
```
auto lo
iface lo inet loopback

#A19
auto eth0
iface eth0 inet static
    address 10.66.0.4
    netmask 255.255.255.248
    gateway 10.66.0.1

#A21
auto eth1
iface eth1 inet static
    address 10.66.10.128
    netmask 255.255.255.252

#A20
auto eth2
iface eth2 inet static
    address 10.66.8.1
    netmask 255.255.254.0
```

#### FBK_Matsuri
```
#A20
auto eth0
iface eth0 inet static
    address 10.66.8.2
    netmask 255.255.254.0
    gateway 10.66.8.1
```

#### Aki_Hachama
```
#A20
auto eth0
iface eth0 inet static
    address 10.66.8.3
    netmask 255.255.254.0
    gateway 10.66.8.1
```

#### GAMERS
```
auto lo
iface lo inet loopback

#A21
auto eth0
iface eth0 inet static
    address 10.66.10.129
    netmask 255.255.255.252

#A22
auto eth1
iface eth1 inet static
    address 10.66.10.1
    netmask 255.255.255.128
```

#### Korone
```
#A22
auto eth0
iface eth0 inet static
    address 10.66.10.2
    netmask 255.255.255.128
    gateway 10.66.10.1
```

#### Okayu
```
#A22
auto eth0
iface eth0 inet static
    address 10.66.10.3
    netmask 255.255.255.128
    gateway 10.66.10.1
```

#### Mio
```
#A22
auto eth0
iface eth0 inet static
    address 10.66.10.4
    netmask 255.255.255.128
    gateway 10.66.10.1
```
#### Holo-ID
```
auto lo
iface lo inet loopback

#A10
auto eth0
iface eth0 inet static
    address 10.66.160.2
    netmask 255.255.255.252
    gateway 10.66.160.1

#A11
auto eth1
iface eth1 inet static
    address 10.66.132.1
    netmask 255.255.255.252

#A12
auto eth2
iface eth2 inet static
    address 10.66.144.65
    netmask 255.255.255.252

#A13
auto eth2
iface eth2 inet static
    address 10.66.138.1
    netmask 255.255.255.252
```
#### AREA15
```
auto lo
iface lo inet loopback

#A11
auto eth0
iface eth0 inet static
    address 10.66.132.2
    netmask 255.255.255.252
    gateway 10.66.132.1

#A14
auto eth1
iface eth1 inet static
    address 10.66.128.1
    netmask 255.255.252.0
```
#### Risu
```
auto eth0
iface eth0 inet static
    address 10.66.128.2
    netmask 255.255.252.0
    gateway 10.66.128.1
```
#### Moona
```
auto eth0
iface eth0 inet static
    address 10.66.128.3
    netmask 255.255.252.0
    gateway 10.66.128.1
```
#### Lofi
```
auto eth0
iface eth0 inet static
    address 10.66.128.4
    netmask 255.255.252.0
    gateway 10.66.128.1
```
#### Holoro
```
auto lo
iface lo inet loopback

#A12
auto eth0
iface eth0 inet static
    address 10.66.144.66
    netmask 255.255.255.252
    gateway 10.66.144.66

#A15
auto eth1
iface eth1 inet static
    address 10.66.144.1
    netmask 255.255.255.192
```
#### Ollie
```
auto eth0
iface eth0 inet static
    address 10.66.144.2
    netmask 255.255.255.192
    gateway 10.66.144.1
```
#### Anya
```
auto eth0
iface eth0 inet static
    address 10.66.144.3
    netmask 255.255.255.192
    gateway 10.66.144.1
```
#### Reine
```
auto eth0
iface eth0 inet static
    address 10.66.144.4
    netmask 255.255.255.192
    gateway 10.66.144.1
```

#### Holoh3ro
```
auto lo
iface lo inet loopback

#A13
auto eth0
iface eth0 inet static
    address 10.66.138.2
    netmask 255.255.255.252
    gateway 10.66.138.1

#A16
auto eth1
iface eth1 inet static
    address 10.66.136.1
    netmask 255.255.254.0
```
#### Zeta
```
auto eth0
iface eth0 inet static
    address 10.66.136.2
    netmask 255.255.254.0
    gateway 10.66.136.1
```
#### Kaela
```
auto eth0
iface eth0 inet static
    address 10.66.136.3
    netmask 255.255.254.0
    gateway 10.66.136.1
```
#### Kobo
```
auto eth0
iface eth0 inet static
    address 10.66.136.4
    netmask 255.255.254.0
    gateway 10.66.136.1
```

### Routing
#### Hololive
```
#KIRI
post-up route add -net 10.67.16.0 netmask 255.255.255.252 gw 10.67.16.2 #A8
post-up route add -net 10.67.4.0 netmask 255.255.255.252 gw 10.67.16.2 #A5
post-up route add -net 10.67.0.0 netmask 255.255.254.0 gw 10.67.16.2 #A6
post-up route add -net 10.67.2.64 netmask 255.255.255.252 gw 10.67.16.2 #A3
post-up route add -net 10.67.2.128 netmask 255.255.255.252 gw 10.67.16.2 #A2
post-up route add -net 10.67.2.0 netmask 255.255.255.192 gw 10.67.16.2 #A1
post-up route add -net 10.67.8.32 netmask 255.255.255.252 gw 10.67.16.2 #A7
post-up route add -net 10.67.8.0 netmask 255.255.255.224 gw 10.67.16.2 #A4

#BAWAH
post-up route add -net 10.66.32.0 netmask 255.255.255.248 gw 10.66.64.2 #A17
post-up route add -net 10.66.16.0 netmask 255.255.255.240 gw 10.66.64.2 #A18
post-up route add -net 10.66.0.0 netmask 255.255.248.0 gw 10.66.64.2 #A19
post-up route add -net 10.66.8.0 netmask 255.255.254.0 gw 10.66.64.2 #A20
post-up route add -net 10.66.10.128 netmask 255.255.255.252 gw 10.66.64.2 #A21
post-up route add -net 10.66.10.0 netmask 255.255.255.128 gw 10.66.64.2 #A22

#KANAN
post-up route add -net 10.66.132.0 netmask 255.255.255.252 gw 10.66.160.2 #A11
post-up route add -net 10.66.144.64 netmask 255.255.255.252 gw 10.66.160.2 #A12
post-up route add -net 10.66.138.0 netmask 255.255.255.252 gw 10.66.160.2 #A13
post-up route add -net 10.66.128.0 netmask 255.255.252.0 gw 10.66.160.2 #A14
post-up route add -net 10.66.144.0 netmask 255.255.255.192 gw 10.66.160.2 #A15
post-up route add -net 10.66.136.0 netmask 255.255.254.0 gw 10.66.160.2 #A16
```
#### Holo-EN
```
post-up route add -net 10.67.0.0 netmask 255.255.254.0 gw 10.67.4.2 #A6
post-up route add -net 10.67.2.128 netmask 255.255.255.248 gw 10.67.4.2 #A2
post-up route add -net 10.67.2.64 netmask 255.255.255.252 gw 10.67.4.2 #A3
post-up route add -net 10.67.2.0 netmask 255.255.255.192 gw 10.67.4.2 #A1
post-up route add -net 10.67.8.0 netmask 255.255.255.224 gw 10.67.8.34 #A4
```
#### Holo-Myth
```
post-up route add -net 10.67.16.0 netmask 255.255.255.252 gw 10.67.4.1 #A8
post-up route add -net 10.67.2.64 netmask 255.255.255.252 gw 10.67.2.130 #A3
post-up route add -net 10.67.2.0 netmask 255.255.255.192 gw 10.67.2.131 #A1
```
#### Holo-Council & Project-Hope
```
post-up route add -net 10.67.16.0 netmask 255.255.255.252 gw 10.67.2.129 #A8
post-up route add -net 10.67.4.0 netmask 255.255.255.252 gw 10.67.2.129 #A5
post-up route add -net 10.67.0.0 netmask 255.255.254.0 gw 10.67.2.129 #A6
```
#### HoloAdvent
```
post-up route add -net 10.67.16.0 netmask 255.255.255.252 gw 10.67.8.33 #A8
```
#### Holo-JP
```
post-up route add -net 10.66.16.0 netmask 255.255.255.240 gw 10.66.32.2 #A18
post-up route add -net 10.66.0.0 netmask 255.255.248.0 gw 10.66.32.3 #A19
post-up route add -net 10.66.8.0 netmask 255.255.254.0 gw 10.66.32.3 #A20
post-up route add -net 10.66.10.128 netmask 255.255.255.252 gw 10.66.32.3 #A21
post-up route add -net 10.66.10.0 netmask 255.255.255.128 gw 10.66.32.3 #A22
```
#### DEV_IS
```
post-up route add -net 10.66.64.0 netmask 255.255.255.252 gw 10.66.32.1 #A9
```
#### GEN:0
```
post-up route add -net 10.66.64.0 netmask 255.255.255.252 gw 10.66.32.1 #A9
post-up route add -net 10.66.8.0 netmask 255.255.254.0 gw 10.66.0.4 #A20
post-up route add -net 10.66.10.128 netmask 255.255.255.252 gw 10.66.0.4 #A21
post-up route add -net 10.66.10.0 netmask 255.255.255.128 gw 10.66.0.4 #A22
```
#### GEN:1
```
post-up route add -net 10.66.10.0 netmask 255.255.255.128 gw 10.66.10.130 #A22
```
#### GAMERS
```
post-up route add -net 10.66.64.0 netmask 255.255.255.252 gw 10.66.10.129 #A9
post-up route add -net 10.66.32.0 netmask 255.255.255.248 gw 10.66.10.129 #A17
post-up route add -net 10.66.0.0 netmask 255.255.248.0 gw 10.66.10.129 #A19
```
#### Holo-ID
```
post-up route add -net 10.66.128.0 netmask 255.255.252.0 gw 10.66.132.2 #A14
post-up route add -net 10.66.144.0 netmask 255.255.255.192 gw 10.66.144.66 #A15
post-up route add -net 10.66.136.0 netmask 255.255.254.0 gw 10.66.138.2 #A16
```
#### AREA15
```
post-up route add -net 10.66.160.0 netmask 255.255.255.252 gw 10.66.132.1 #A10
```
#### Holoro
```
post-up route add -net 10.66.160.0 netmask 255.255.255.252 gw 10.66.144.65 #A10
```
#### Holoh3ro
```
post-up route add -net 10.66.160.0 netmask 255.255.255.252 gw 10.66.138.1 #A10
```


## CPT (VLSM)
### Topologi
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/69c0de7a-91c3-460c-9a41-d6a4210e3e53">


### Tree VLSM
![pohon vlsm drawio (1)](https://github.com/user-attachments/assets/7165273e-7595-47f6-9b34-114ac4076b5f)


### Pembagian IP
<img width="532" alt="image" src="https://github.com/user-attachments/assets/2a8ece76-b6b1-4fbd-8154-ded98ef96986">


### Subnet A1
### Hololive
```
enable
configure terminal
interface fa1/0
ip address 10.66.19.73 255.255.255.252
no shutdown
```

### Holo-ID
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.74 255.255.255.252
no shutdown
```

### Subnet A2
### Holo-ID
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.93 255.255.255.252
no shutdown
```
### AREA15
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.94 255.255.255.252
no shutdown
```

### Subnet A3
### AREA15
```
enable
configure terminal
interface fa0/1
ip address 10.66.8.1 255.255.252.0
no shutdown
```
### Moona
```
Dekstop IP Configuration
IP Address: 10.66.8.2
Subnet Mask: 255.255.252.0
Gateway: 10.66.8.1
```
### Risu
```
Dekstop IP Configuration
IP Address: 10.66.8.3
Subnet Mask: 255.255.252.0
Gateway: 10.66.8.1
```
### lofi
```
Dekstop IP Configuration
IP Address: 10.66.8.4
Subnet Mask: 255.255.252.0
Gateway: 10.66.8.1
```

### Subnet A4
### Holo-ID
```
enable
configure terminal
interface fa1/0
ip address 10.66.19.97 255.255.255.252
no shutdown
```
### holoro
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.98 255.255.255.252
no shutdown
```

### Subnet A5
### holoro
```
enable
configure terminal
interface fa0/1
ip address 10.66.18.193 255.255.255.192
no shutdown
```
### Ollie
```
Dekstop IP Configuration
IP Address: 10.66.18.194
Subnet Mask: 255.255.255.192
Gateway: 10.66.18.193
```
### Anya
```
Dekstop IP Configuration
IP Address: 10.66.18.195
Subnet Mask: 255.255.255.192
Gateway: 10.66.18.193
```
### Reine
```
Dekstop IP Configuration
IP Address: 10.66.18.196
Subnet Mask: 255.255.255.192
Gateway: 10.66.18.193
```

### Subnet A6
### Holo-ID
```
enable
configure terminal
interface fa1/1
ip address 10.66.19.101 255.255.255.252
no shutdown
```
### holoh3ro
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.102 255.255.255.252
no shutdown
```

### Subnet A7
### holoh3ro
```
enable
configure terminal
interface fa0/1
ip address 10.66.16.1 255.255.254.0
no shutdown
```
### Zeta
```
Dekstop IP Configuration
IP Address: 10.66.16.2
Subnet Mask: 255.255.254.0
Gateway: 10.66.16.1
```
### Kaela 
```
Dekstop IP Configuration
IP Address: 10.66.16.3
Subnet Mask: 255.255.254.0
Gateway: 10.66.16.1
```
### Kobo 
```
Dekstop IP Configuration
IP Address: 10.66.16.4
Subnet Mask: 255.255.254.0
Gateway: 10.66.16.1
```

### Subnet A8
### Hololive
```
enable
configure terminal
interface fa1/1
ip address 10.66.19.105 255.255.255.252
no shutdown
```
### HoloJP
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.106 255.255.255.252
no shutdown
```

### Subnet A9
### HoloJP
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.65 255.255.255.248
no shutdown
```
### DEV_IS
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.66 255.255.255.248
no shutdown
```
### GEN:0 
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.67 255.255.255.248
no shutdown
```

### Subnet A10
### DEV_IS
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.33 255.255.255.240
no shutdown
```
### Ririka_Rade
```
Dekstop IP Configuration
IP Address: 10.66.19.34
Subnet Mask: 255.255.255.240
Gateway: 10.66.19.33
```
### Ao
```
Dekstop IP Configuration
IP Address: 10.66.19.35
Subnet Mask: 255.255.255.240
Gateway: 10.66.19.33
```
### Hajime_Kanade
```
Dekstop IP Configuration
IP Address: 10.66.19.36
Subnet Mask: 255.255.255.240
Gateway: 10.66.19.33
```

### Subnet A11
### GEN:0
```
enable
configure terminal
interface fa0/1
ip address 10.66.0.1 255.255.248.0
no shutdown
```
### GEN:1
```
enable
configure terminal
interface fa0/0
ip address 10.66.0.2 255.255.248.0
no shutdown
```
### MiComet
```
Dekstop IP Configuration
IP Address: 10.66.0.3
Subnet Mask: 255.255.248.0
Gateway: 10.66.0.1
```
### Sora_Robo_AZK 
```
Dekstop IP Configuration
IP Address: 10.66.0.4
Subnet Mask: 255.255.248.0
Gateway: 10.66.0.1
```

### Subnet A12
### GEN:1
```
enable
configure terminal
interface fa0/1
ip address 10.66.14.1 255.255.254.0
no shutdown
```
### FBK_Matsuri
```
Dekstop IP Configuration
IP Address: 10.66.14.2
Subnet Mask: 255.255.254.0
Gateway: 10.66.14.1
```
### Aki_Hachama
```
Dekstop IP Configuration
IP Address: 10.66.14.3
Subnet Mask: 255.255.254.0
Gateway: 10.66.14.1
```

### Subnet A13
### GEN:1
```
enable
configure terminal
interface fa1/0
ip address 10.66.19.77 255.255.255.252
no shutdown
```
### GAMERS
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.78 255.255.255.252
no shutdown
```

### Subnet A14
### GAMERS
```
enable
configure terminal
interface fa0/1
ip address 10.66.18.1 255.255.255.128
no shutdown
```
### Kerone 
```
Dekstop IP Configuration
IP Address: 10.66.18.2
Subnet Mask: 255.255.255.128
Gateway: 10.66.18.1
```
### Okayu
```
Dekstop IP Configuration
IP Address: 10.66.18.3
Subnet Mask: 255.255.255.128
Gateway: 10.66.18.1
```
### Mio
```
Dekstop IP Configuration
IP Address: 10.66.18.4
Subnet Mask: 255.255.255.128
Gateway: 10.66.18.1
```

### Subnet A15
### Hololive
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.81 255.255.255.252
no shutdown
```
### Holo-EN
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.82 255.255.255.252
no shutdown
```

### Subnet A16
### Holo-EN
```
enable
configure terminal
interface fa1/0
ip address 10.66.19.85 255.255.255.252
no shutdown
```
### HoloAdvent
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.86 255.255.255.252
no shutdown
```

### Subnet A17
### HoloAdvent
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.1 255.255.255.224
no shutdown
```
### FuwaMoco
```
Dekstop IP Configuration
IP Address: 10.66.19.2
Subnet Mask: 255.255.255.224
Gateway: 10.66.19.1
```
### Shiori_Nerissa
```
Dekstop IP Configuration
IP Address: 10.66.19.3
Subnet Mask: 255.255.255.224
Gateway: 10.66.19.1
```
### Biboo
```
Dekstop IP Configuration
IP Address: 10.66.19.4
Subnet Mask: 255.255.255.224
Gateway: 10.66.19.1
```

### Subnet A18
### Holo-EN
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.89 255.255.255.252
no shutdown
```
### Holo-Myth
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.90 255.255.255.252
no shutdown
```

### Subnet A19
### Holo-Myth
```
enable
configure terminal
interface fa0/1
ip address 10.66.12.1 255.255.254.0
no shutdown
```
### Gura_Ame_Ina
```
Dekstop IP Configuration
IP Address: 10.66.12.2
Subnet Mask: 255.255.254.0
Gateway: 10.66.12.1
```
### Kiara_Calli
```
Dekstop IP Configuration
IP Address: 10.66.12.3
Subnet Mask: 255.255.254.0
Gateway: 10.66.12.1
```

### Subnet A20
### Holo-Myth
```
enable
configure terminal
interface fa1/0
ip address 10.66.19.49 255.255.255.248
no shutdown
```
### Router4
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.50 255.255.255.248
no shutdown
```
### Holo-Council
```
enable
configure terminal
interface fa0/0
ip address 10.66.19.51 255.255.255.248
no shutdown
```

### Subnet A21
### Router4
```
enable
configure terminal
interface fa0/1
ip address 10.66.19.57 255.255.255.248
no shutdown
```
### Irys
```
Dekstop IP Configuration
IP Address: 10.66.19.58
Subnet Mask: 255.255.255.248
Gateway: 10.66.19.57
```

### Subnet A22
### Holo-Council
```
enable
configure terminal
interface fa0/1
ip address 10.66.18.129 255.255.255.192
no shutdown
```
### Kronii_Mumei
```
Dekstop IP Configuration
IP Address: 10.66.18.130
Subnet Mask: 255.255.255.192
Gateway: 10.66.18.129
```
### Bae_Fauna
```
Dekstop IP Configuration
IP Address: 10.66.18.131
Subnet Mask: 255.255.255.192
Gateway: 10.66.18.129
```

### Konfigurasi Routing
### Sisi Kanan (Holo-ID)
### Hololive
```
enable
configure terminal
ip route 10.66.19.92 255.255.255.252 10.66.19.74
ip route 10.66.8.0 255.255.252.0 10.66.19.74
ip route 10.66.19.96 255.255.255.252 10.66.19.74
ip route 10.66.18.192 255.255.255.192 10.66.19.74
ip route 10.66.19.100 255.255.255.252 10.66.19.74
ip route 10.66.16.0 255.255.254.0 10.66.19.74
do write
```
### Holo-ID
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.73
ip route 10.66.8.0 255.255.252.0 10.66.19.94
ip route 10.66.18.192 255.255.255.192 10.66.19.98
ip route 10.66.16.0 255.255.254.0 10.66.19.102
do write
```
### AREA15
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.93
do write
```
### holoro
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.97
do write
```
### holoh3ro
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.101
do write
```

### Sisi Bawah (HoloJP)
### Hololive
```
enable
configure terminal
ip route 10.66.19.64 255.255.255.248 10.66.19.106
ip route 10.66.19.32 255.255.255.240 10.66.19.106
ip route 10.66.0.0 255.255.248.0 10.66.19.106
ip route 10.66.14.0 255.255.254.0 10.66.19.106
ip route 10.66.19.76 255.255.255.252 10.66.19.106
ip route 10.66.18.0 255.255.255.128 10.66.19.106
do write
```
### HoloJP
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.105
ip route 10.66.19.32 255.255.255.240 10.66.19.66
ip route 10.66.0.0 255.255.248.0 10.66.19.67
ip route 10.66.14.0 255.255.254.0 10.66.19.67
ip route 10.66.19.76 255.255.255.252 10.66.19.67
ip route 10.66.18.0 255.255.255.128 10.66.19.67
do write
```
### DEV_IS
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.65
ip route 10.66.0.0 255.255.248.0 10.66.19.67
ip route 10.66.14.0 255.255.254.0 10.66.19.67
ip route 10.66.19.76 255.255.255.252 10.66.19.67
ip route 10.66.18.0 255.255.255.128 10.66.19.67
do write
```
### GEN:0
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.65
ip route 10.66.19.32 255.255.255.240 10.66.19.66
ip route 10.66.14.0 255.255.254.0 10.66.0.2
ip route 10.66.19.76 255.255.255.252 10.66.0.2
ip route 10.66.18.0 255.255.255.128 10.66.0.2
do write
```
### GEN:1
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.0.1
ip route 10.66.18.0 255.255.255.128 10.66.19.78
do write
```
### GAMERS
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.77
do write
```
### Sisi Kiri (HoloEN)
### Hololive
```
enable
configure terminal
ip route 10.66.19.84 255.255.255.252 10.66.19.82
ip route 10.66.19.0 255.255.255.224 10.66.19.82
ip route 10.66.19.88 255.255.255.252 10.66.19.82
ip route 10.66.12.0 255.255.254.0 10.66.19.82
ip route 10.66.19.48 255.255.255.248 10.66.19.82
ip route 10.66.19.56 255.255.255.248 10.66.19.82
ip route 10.66.18.128 255.255.255.192 10.66.19.82
do write
```
### Holo-EN
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.81
ip route 10.66.19.0 255.255.255.224 10.66.19.86
ip route 10.66.12.0 255.255.254.0 10.66.19.90
ip route 10.66.19.48 255.255.255.248 10.66.19.90
ip route 10.66.19.56 255.255.255.248 10.66.19.90
ip route 10.66.18.128 255.255.255.192 10.66.19.90
do write
```
### HoloAdvent
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.85
do write
```
### Holo-Myth
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.89
ip route 10.66.19.56 255.255.255.248 10.66.19.50
ip route 10.66.18.128 255.255.255.192 10.66.19.51
do write
```
### Router4
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.49
ip route 10.66.18.128 255.255.255.192 10.66.19.51
do write
```
### Holo-Council
```
enable
configure terminal
ip route 0.0.0.0 0.0.0.0 10.66.19.49
ip route 10.66.19.56 255.255.255.248 10.66.19.50
do write
```
