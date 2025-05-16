## Test suit "Add to data base form" with Bug repors

<div style="overflow-x: auto;">
<table style="width: 100%; table-layout: fixed; border-collapse: collapse;border-style: solid;">
  <thead>
    <tr>
      <th colspan="11" style="text-align:center; background-color:#E0FFFF; color:#000000;">Functional Test Area</th>
      <th colspan="4" style="text-align:center; background-color:#FFB6C1; color:#000000;">Defect Reporting Area</th>
    </tr>
    <tr>
      <th style="min-width: 40px;">N</th>
      <th style="min-width: 130px;">Title</th>
      <th style="min-width: 160px;">Description</th>
      <th style="min-width: 40px;">Priority</th>
      <th style="min-width: 50px;">Frequency</th>
      <th style="min-width: 60px;">Environment</th>
      <th style="min-width: 90px;">Precondition</th>
      <th style="min-width: 250px;">Script Content</th>
      <th style="min-width: 220px;">Check</th>
      <th style="min-width: 40px">Result</th>
      <th style="min-width: 160px">Note</th>
      <th style="min-width: 150px;">Bug</th>
      <th style="min-width: 220px;">Actual result</th>
      <th style="min-width: 100px;">Environment</th>
      <th style="min-width: 150px;">Screenshot</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TC 01</td>
      <td>Check with entering the 1st character in the field “Patronymic” in Cyrillic alphabet</td>
      <td>Checking the creation of a new client in the database when entering a single Cyrillic alphabetic character in the “Patronymic” field</td>
      <td>High</td>
      <td>Always</td>
      <td>Web,<br>Test scope</td>
      <td>Log in and authorize in the “Database” service</td>
      <td>1. Go to the “Create Client” tab<br>2. Enter in the “Name” field - Д<br>3. Enter in the “Last Name” field - Б<br>4. Enter in the “Patronymic” field - Л<br>5. Do not fill in the rest of the fields<br>6. Press the “Create” button</td>
      <td>1. Validation did not work, the fields are complete;<br>2. The customer's data is stored in the database;<br>3. DB entries:<br>“First Name” - Д<br>“Surname” - Б<br>“Patronymic” - Л</td>
      <td>OK</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <!-- Add more rows here -->
  </tbody>
</table>
</div>