The code in this repository aims at exploring the basics of pandas while solving problems.

Following are the problems we will be solving here:

<h3>Problem 1</h3>

You are given the heights (in inch) and weights (in lbs) of 5 people as shown in the table below:

<table>
  <thead>
    <tr>
      <th>Person</th>
      <th>Height(inch)</th>
      <th>Weight(lbs)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>A</td>
      <td>72</td>
      <td>186</td>
    </tr>
    <tr>
      <td>B</td>
      <td>69</td>
      <td>205</td>
    </tr>
    <tr>
      <td>C</td>
      <td>70</td>
      <td>201</td>
    </tr>
    <tr>
      <td>D</td>
      <td>62</td>
      <td>125</td>
    </tr>
    <tr>
      <td>E</td>
      <td>57</td>
      <td>89</td>
    </tr>
  </tbody>
</table>

It is later found that the table actually misses entries for persons F and G whose heights are 65 inch and 60 inch respectively and the weight for F is 121 lbs, but data for G's weight is missing. Also, values for all the heights is found to be 5 inch less than it should have been, whereas values for all the weights is found to be 5 lbs more than it should have been. Find the correct Body Mass Index (BMI) for each person, if possible.

We will solve this problem using both Series and DataFrame.

<h3>Problem 2</h3>

We have a <a href="https://openmv.net/info/travel-times">dataset</a> that contains data for trips made by a driver over a period of time. The description of the dataset reads as following:

A driver uses an app to track GPS coordinates as he drives to work and back each day. The app collects the location and elevation data. Data for about 200 trips are summarized in this data set.

Using the dataset, find <br/>
(a) the details for first, last and 10th entry, <br/>
(b) the details for each day, <br/>
(c) entries when total distance travelled in a day is greater than 90 but less than 100, <br/>
(d) the distance and fuel economy for a single row from (c), <br/>
(e) entries for Fridays when the average moving speed is greater than 90, <br/>
(f) entries when max speed is greater than 135 or fuel economy is less than 8, and <br/>
(g) details for the entries by day of week.

We'll be using DataFrame to solve this problem.
