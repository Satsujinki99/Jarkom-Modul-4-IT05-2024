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
