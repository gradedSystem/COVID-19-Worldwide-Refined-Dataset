---
datapackage:
  title: COVID-19 Worldwide Refined Dataset
  description: This dataset offers a well-curated and extensive collection of COVID-19 data, sourced from RapidAPI, designed to provide valuable insights. It is regularly updated with the latest available information, ensuring accurate and timely statistics.
  created: 2024-09-02
  updated: 2024-09-02
  sources:
  - path: https://www.kaggle.com/datasets/vanka2003/covid-19-worldwide-refined-dataset
    title: COVID-19 Worldwide Refined Dataset
  resources:
  - name: covid-19-worldwide-refined-dataset
    title: COVID-19 Worldwide Refined Dataset
    description: This is the main dataset which provides a comprehensive and refined collection of COVID-19 information, sourced from RapidAPI and curated to offer valuable insights. The data is updated with the most recent information available, ensuring that you have access to accurate and timely statistics.
    lastModified: 2024-09-02
    path: alzheimers_disease_patient_data.csv
---

<div class="hero">
    <h1 class="hero-title">A Glimpse into the Global COVID-19 Impact 🌍</h1>
    <p class="hero-description">Explore how COVID-19 has affected countries around the world. Dive into the data to see the spread, recovery, and critical cases globally.</p>
</div>

## Data Catalog
<Catalog
  datasets={[
    {
      _id: 'map-of-spreaded-covid',
      metadata: {
        title: 'Spreading of the Covid-19',
        'details-of-task': 'Dataset contains the map of the Covid-10 spread',
        'task-description': 'Provides insights into the global spread of confirmed cases.',
      },
      url_path: 'map-of-spreaded-covid'
    }
  facets={[
    'title'
  ]}
/>

## Global Impact of COVID-19

The COVID-19 pandemic has swept across the globe, affecting countries in different ways. Some nations have struggled with high numbers of cases, while others have shown resilience in their recovery rates.

In many regions, the pandemic's progression has been closely monitored through the number of confirmed cases, recoveries, and fatalities. Countries around the world have faced significant challenges as they navigate through these unprecedented times, with healthcare systems being pushed to their limits.

In some areas, the situation has been particularly severe, with high numbers of confirmed cases and related deaths. Meanwhile, other nations have seen encouraging recovery rates, highlighting the varied impact of the virus across different regions.

### COVID-19 Data Visualization

Below are some visualizations that help us understand the global impact of COVID-19:

### Total COVID-19 Confirmed Cases by Country (Top 10)

<PlotlyLineChart
  data={{
    url: 'top_10_confirmed.csv'
  }}
  title="Total COVID-19 Confirmed Cases by Country Top 10"
  xAxis="country"
  yAxis="confirmed"
/>

### COVID-19 Recoveries by Country (Top 10)

<PlotlyLineChart
  data={{
    url: 'top_10_recovered.csv'
  }}
  title="COVID-19 Recoveries by Country Top 10"
  xAxis="country"
  yAxis="recovered"
/>

### COVID-19 Critical Cases by Country (Top 10)

<PlotlyLineChart
  data={{
    url: 'top_10_critical.csv'
  }}
  title="COVID-19 Critical Cases by Country Top 10"
  xAxis="country"
  yAxis="critical"
/>

### The Human Toll

The impact of COVID-19 is not just measured in cases and recoveries but also in the tragic loss of life. The pandemic has claimed lives around the world, leaving a lasting mark on communities. Each statistic represents a person, a family, and a community affected by this global crisis.

The story of COVID-19 is one of both struggle and resilience, a global challenge that has touched every corner of the world. As we continue to track and respond to the pandemic, these numbers provide crucial insights into its impact and the ongoing efforts to combat it.
