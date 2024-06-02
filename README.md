# Drunky
<img src="/assets/img/DrunkyAppLogo.png" style="width:400px">

A Blood Alcohol Content(BAC) App.

## Guide

### Setup

Go to settings and enter your weight and gender (male/female).

### Step 1:

Select which beverage(s) you have drank from the list. (The list can be edited)

Drunky uses a database from Airtable of common drinks, as seen below:

<img src="/assets/img/AirtableLogo.png" style="width:200px">

<table><thead>
  <tr>
    <th>Navn</th>
    <th></th>
    <th>Alkohol gram</th>
    <th>% & mængde</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Breezer</td>
    <td> <img src="/assets/img/Breezer.png" style="width:60px"> </td>
    <td>11</td>
    <td>4% 27,5 cl</td>
  </tr>
  <tr>
    <td>Øl</td>
    <td> <img src="/assets/img/Øl.jpg" style="width:60px"> </td>
    <td>15.18</td>
    <td>4,6% 33 cl</td>
  </tr>
  <tr>
    <td>Små shots</td>
    <td> <img src="/assets/img/SmåShots.jpg" style="width:60px"> </td>
    <td>3.64</td>
    <td>16,4% 2 cl</td>
  </tr>
  <tr>
    <td>Underberg</td>
    <td> <img src="/assets/img/Underberg.jpg" style="width:60px"> </td>
    <td>8.8</td>
    <td>44% 2 cl</td>
  </tr>
  <tr>
    <td>Vodka shot</td>
    <td> <img src="/assets/img/VodkaShot.jpg" style="width:60px"> </td>
    <td>16.5</td>
    <td>37,5% 4.4 cl</td>
  </tr>
  <tr>
    <td>Vodka shot</td>
    <td> <img src="/assets/img/VodkaShot2.png" style="width:60px"> </td>
    <td>17.6</td>
    <td>40% 4,4 cl</td>
  </tr>
</tbody>
</table>

### Step 2:

Determine at what time you drank the beverage(s).
It then calculates your BAC and whether you're above the legal limit. (Denmark, 0,5 ‰)
It also generates a graph that shows a linear decrease and when the BAC should be at 00. 

**Settings**

It saves your weight to a database in Airtable.

**Graph**

### Extra features
A weekly, monthly, and yearly status of whether you drink too much.
