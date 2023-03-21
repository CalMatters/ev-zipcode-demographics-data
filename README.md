# Data about CA EV car registrations and demographic data by ZIP code

This data was used in a story published March 22, 2023 titled "[Who buys electric cars in California — and who doesn’t?]([https://calmatters.org/](https://calmatters.org/environment/2023/03/california-electric-cars-demographics/(opens in a new tab)))". The data set can be found in the file named `ev-zipcode-demographics.csv` and comes from 3 different sources:

* 2021 light-duty vehicle population from DMV via the [California Energy Commission](https://www.energy.ca.gov/files/zev-and-infrastructure-stats-data)

> Vehicle population is updated annually, each April, to reflect the number of vehicles “on the road” during the previous calendar year. Vehicle population counts vehicles whose registration is either current or less than 35 days expired. Sales are higher than population because of vehicle retirements, accidents, owners moving out of state, or other reasons.

* 2021 5-Year American Census Survey from the Census Bureau
* [Zillow Home Value Index](https://www.zillow.com/research/data/), which represents the "typical" home value for a region, as of February 2023


<table>
<thead>
<tr>
<th>Column name</th>
<th>Description, caveats, and source</th>
</tr>
</thead>
<tbody>
<tr>
  <td>ZIP</td>
  <td><p>ZIP code. Only ZIP codes with 2021 American Community Survey population data and at least 1,000 residents are included. Used by the postal service, ZIP codes do not have exact persistent geographical boundaries. The demographic data here comes from the Census Bureau's Zip Code Tabulation Areas, which are approximated by addresses.</p></td>
</tr>
<tr>
  <td>Diesel</td>
  <td><p>The number of diesel cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Electric</td>
  <td><p>The number of battery electric cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Flex_Fuel</td>
  <td><p>The number of flex fuel cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Gasoline</td>
  <td><p>The number of gasoline cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Gasoline_Hybrid</td>
  <td><p>The number of gasoline hybrid cars (no external charger for the battery) registered in the ZIP code in 2021. They are not considered zero-emission vehicles by the state.</p></td>
</tr>
<tr>
  <td>Hydrogen</td>
  <td><p>The number of fuel cell electric cars, powered by hydrogen, registered in the ZIP code in 2021. They are considered zero-emission vehicles by the state.</p></td>
</tr>
<tr>
  <td>Natural Gas</td>
  <td><p>The number of natural gas cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Plugin_Hybrid</td>
  <td><p>The number of plug-in hybrid cars (has an internal combustion engine, but can also be charged externally) registered in the ZIP code in 2021. They are considered zero-emission vehicles by the state.</p></td>
</tr>
<tr>
  <td>Propane</td>
  <td><p>The number of propane cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Total_Cars</td>
  <td><p>The total number of cars registered in the ZIP code in 2021.</p></td>
</tr>
<tr>
  <td>Total_EV</td>
  <td><p>The total number of cars considered electric (the state uses the language "zero-emission vehicles"), registered in the ZIP code in 2021. This includes battery electric, plug-in hybrid and fuel cell vehicles.</p></td>
</tr>
<tr>
<td>EV_perc</td>
  <td><p>The percent of cars considered electric (the state uses the language "zero-emission vehicles"), registered in the ZIP code in 2021. This includes battery electric, plug-in hybrid and fuel cell vehicles. If the value is <code>14.23</code>, for example, it should be read as <code>14.23%</code>.</p></td>
</tr>
<tr>
  <td>Median_Household_Income</td>
  <td><p>The median household income of a ZIP code in dollars from the 2021 5-Year ACS. If the value is <code>250001</code>, that means the value is over $250,000, and the Census does not publish the exact value.</p></td>
</tr>
<tr>
  <td>Latino_perc</td>
  <td><p>The percent of the population that is Hispanic or Latino (of any race). If the value is <code>8.8</code>, for example, it should be read as <code>8.8%</code>.</p></td>
</tr>
<tr>
  <td>White_perc</td>
  <td><p>The percent of the population that is Not Hispanic or Latino, White alone. If the value is <code>8.8</code>, for example, it should be read as <code>8.8%</code>.</p></td>
</tr>
<tr>
  <td>Asian_perc</td>
  <td><p>The percent of the population that is Not Hispanic or Latino, Asian alone. If the value is <code>8.8</code>, for example, it should be read as <code>8.8%</code>.</p></td>
</tr>
  <tr>
  <td>Black_perc</td>
  <td><p>The percent of the population that is Not Hispanic or Latino, Black or African American alone. If the value is <code>8.8</code>, for example, it should be read as <code>8.8%</code>.</p></td>
</tr>
  </tr>
<tr>
  <td>BachOrHigher_perc</td>
  <td><p>The percent of the population 25 years and over that has a bachelor's degree or higher. If the value is <code>8.8</code>, for example, it should be read as <code>8.8%</code>.</p></td>
</tr>
<tr>
  <td>Total_Population</td>
  <td><p>The total population of the ZIP code.</p></td>
</tr>
<tr>
  <td>Zillow_Home_Value_Index</td>
  <td><p>The typical home value of the ZIP code in dollars, estimated by Zillow, as of February 2023.</p></td>
</tr>
</tbody>
</table>

## Data use

If you use this dataset, please mention it was collected, combined and cleaned by CalMatters. We would love to know how you used it. If you have any questions about this dataset, feel free to contact us as well.

[CalMatters](https://calmatters.org/) is a nonpartisan, nonprofit journalism venture committed to explaining how California’s state Capitol works and why it matters.
