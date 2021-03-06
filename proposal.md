Project Proposal
================

#### Team Member:

Danyang Gui (dg3187)

Jingyi Zhang (jz3297)

Zihan Yu (zy2443)

Kexin Sun (sk4833)

Yining Xiang (yx2641)

<br />

#### Project Title:

Hospital Inpatient Cost in New York State (2009-2017)

<br />

#### Motivation

In 2018, the U.S. spent 16.9 percent of gross domestic product (GDP) on
health care, nearly twice as much as the average of ten other
high-income countries including Australia, Canada, France, Germany,
Netherlands, New Zealand, Norway, Sweden, Switzerland, and the United
Kingdom. When diving deep into the data, we will find that U.S. public
spending is similar to other countries but private spending is higher
than most. In spite of the high cost, the U.S. has the lowest life
expectancy among the 11 nations and the highest chronic disease burden.
Therefore, increasing access to affordable and effective health care is
one of the most important challenges for the U.S. health care system. As
residents-to-be, we are collectively interested in investigating the
hospital inpatient cost in New York State and hopefully providing a
plain guideline for patients who are seeking inpatient treatment.

<br />

#### Final Products

The final products will be displayed as a webpage. It will include the
following:

  - main page - a brief introduction to the project.

  - 2-3 pages - the project scope, data, approaches, visualizations,
    results.

  - a page for report.

  - a page for screencast.

<br />

#### Data Sources

  - Provided by New York State Department of Health
      - Hospital Inpatient Cost Transparency: Beginning 2009
      - Link:
        <https://health.data.ny.gov/Health/Hospital-Inpatient-Cost-Transparency-Beginning-200/7dtz-qxmr>
      - It can be accessed using API.
      - This dataset contains information of hospital inpatient cost
        submitted New York State Article 28 Hospitals from 2009 to 2017.
        There are 1.08 million rows and 14 columns. Columns in the
        dataset are Year, Facility Id, Facility Name, APR DRG Code, APR
        Severity of Illness Code, APR DRG Description, APR Severity of
        Illness Description, APR Medical Surgical Code, APR Medical
        Surgical Description, Discharges, Mean Charge, Median Charge,
        Mean Cost and Median Cost. Cost data presented in this dataset
        was calculated using facility specific audited RCCs file.
  - We may add more datasets as support when we start working on the
    project.

<br />

#### Analyses/visualizations/coding challenges

**Analyses:**

The goal of this project is to create a guide for the patients and
citizens in New York State that contains the history information of the
charge and cost in the 28 hospitals around them. The history of hospital
expense could give them some economical direction in transfer treatment
when hospitalization is needed. This guide would give the patients the
charge and cost of each hospital and detailed comparisons based on the
4-level severity standard. Hence the patient could have some consulting
information on the cost of each hospital in New York.

**Visualization:**

We plan to include the following plots:

  - Scatterplot is used to see the charge/cost distribution of each
    hospital.
  - Boxplots are used to see the charge/cost categorized by the severity
    and type of illness.
  - Histogram can used to compare the differences in charge/cost based
    on the locations (district of NYC) of hospitals.
  - ggplot will directly show the trend of charge/cost over time
    (2009-2017).

**Coding challenges:**

  - The dataset we found contains 14 columns and 1.08 million rows
    (observations). Since it can be considered as a large dataset, it
    might take a relatively long time for R studio to process the output
    when we run the code.
  - Also, since one of the goals in this project is to determine if
    there is a relationship between the locations and the charge/cost of
    these 28 hospitals, we also need to manually investigate the
    coordinates (determine which districts of NYC they belong to) of the
    hospitals so that we can make plot to see the differences.

<br />

#### Timeline

First week: 11/9-11/13

  - Meet with the teaching member and divide the work (coding and
    report)
  - Work on coding
  - Meet together on November 13th 3pm (Beijing time)

<br />

Second week: 11/16-11/20

  - Work on coding
  - Meet together on November 20th 3pm (Beijing time)

<br />

Third week: 11/23-11/27

  - Work on report & screencast
  - Meet together on November 27th 3pm (Beijing time)

<br />

Fourth week: 11/30-12/4

  - Work on report & screencast
  - Finalizing the project
  - Meet together on December 4th 3pm (Beijing time)

We will arrange additional meetings with each other or the teaching
member if needed.
