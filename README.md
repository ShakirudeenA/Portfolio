# **Welcome!**  
I'm Shak, a Data Analyst based in London.

I specialise in *Power BI* and *SQL*, with a bit of *Python* on the side.  

## Content

**Home Page**: A summary of projects, containing screenshots and a little context.

### Projects

| Project Title                        | Tools              |
|--------------------------------------|--------------------|
| Ben's Pizzeria January Sales Report  | Power BI and SQL   |
| Retail Sales Report                  | Power BI           |
| Smartwatch Fitness Data              | Python / Pandas    |
| Data Professional Survey             | Power BI           |
| NBA.com Second Round Gems            | Tableau            |


---

## Ben's Pizzaria - January 2025 Branch Sales Report (NYC & PHL)

![Ben's Pizza Dashboard](./Ben%27s%20Pizza%20dashboard.png)

I built this project end-to-end using a synthetic but deliberately flawed sales dataset, with the approach of treating it as if it were commissioned with specific goals in mind. 	 

The raw CSV arrived with typical issues such as mixed formats, missing or inconsistent data, duplicate records and even simple typos.  These made for realistic data cleaning practice using MySQL. 

The next step was normalising the data and separating it from one large mess into well-organised, smaller tables with much less redundancy. 

The final step was uploading my normalised data into Power BI where it recognised table relationships and from there I built a series of visuals appropriate to the business context and objectives.

*In hindsight, I should've added a lot more columns to the original dataset to allow for a more interesting range of visuals.*

---

## Sales dashboard - Power BI

This dashboard presents key performance insights from 326 days of e-commerce activity, focusing on category sales performance.  
As it was an earlier project of mine, it lacked a professional finish - so I decided to clean it up.  Below are before and after screenshots.

<table>
  <tr>
    <td align="center"><strong>Before</strong></td>
    <td align="center"><strong>After</strong></td>
  </tr>
  <tr>
    <td><img src="./assets/Sales Dashboard before.png" width="480"/></td>
    <td><img src="./assets/Sales Dashboard after.png" width="480"/></td>
  </tr>
</table>

---

## Cleaning and Preparing Data Using Pandas - Python

The below data set shows the workout information collected by an individual's watch over the course of a month.

<p align="center"><em>On the left: raw data (errors in yellow)<br>On the right: cleaned data (correction in green)</em></p>

<img src="./assets/Smartwatch%20data%20before%20and%20after.png" width="1060"/>


### Data Integrity

Instead of deleting rows with errors, it's important to correct them appropriately, especially when dealing with a small dataset. 

For example, when handling missing values in the *Calories* column, I used the mean specific to each workout duration (45 or 60 minutes) instead of a flat overall average. This approach avoided skewing data or leaving it with holes, thus keeping the data realistic, accurate, and fit for purpose. 


---

## Data Professional Survey – Power BI

This dashboard visualises insights from a survey of data professionals, covering their demographics, career paths, and industry trends.

This was my first Power BI project.  I followed a YouTube tutorial using a provided dataset. I aim to revisit this project and improve it in the future.  

<p align="center">
  <img src="./assets/Data%20Professional%20Survey%20PBI.png" width="1080" alt="Data Professional Survey"/>
</p>



## An Analysis of the NBA Second Round Draft – Tableau

During my data analyst bootcamp, we were assigned to create a project focusing on one of our passions. The intention of this project was to explore a dataset with Tableau as the medium. Though very rudimentary, it offered my first experience in making visuals, using calculations (measures) and making dashboards. This dataset has a lot of potential and I will definitely recreate this project in Power BI and potentially expanding it with additional data. 

In the dashboard revisit, I'll include multiple KPIs that will provide deeper insight into a single player's performance, for example when selecting a player on the visuals, i.e Gilbert Arenas, the surrounding KPIs will show you his Career points total, Usage %, and Net Rating. These will be in comparison to peers, above or below average.

<p align="center">
  <img src="./assets/NBA%20Dashboard.png" width="1080" alt="NBA Dashboard"/>
</p>


