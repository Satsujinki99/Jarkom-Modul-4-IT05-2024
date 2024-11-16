# Jarkom-Modul-4-IT05-2024

| Nama | NRP |
| ---- | :-: |
| Adlya Isriena Aftarisya | 5027231066 |
| Furqon Aryadana | 5027231024 |

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

