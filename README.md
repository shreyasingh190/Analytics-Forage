# Deloitte Data Analytics Job Simulation

Work completed as part of the **Deloitte Data Analytics Job Simulation** on [Forage](https://www.theforage.com/) (November 2026). The simulation covered practical tasks in **data analysis** and **forensic technology**, using data from a manufacturing company (Daikibo) with factories in Berlin, Meiyo, Seiko and Shenzhen.

## What's in this repo

| File | Description |
| --- | --- |
| `images/Dashboard_1.png` | Tableau dashboard showing equipment downtime by factory and by device |
| `data/Task_5_Equality_Table.xlsx` | Excel table scoring job roles in each factory and classifying them by equality |

## 1. Downtime dashboard

![Downtime dashboard](images/Dashboard_1.png)

The dashboard has two views:

- **Downtime by Factory**: unhealthy count for each of the 4 factories.
- **Downtime by Device**: unhealthy count for each device type, split by factory.

**Key findings**

- Seiko (48) and Shenzhen (42) have the highest unhealthy counts. Meiyo has 11 and Berlin only 2.
- LaserWelder (Seiko) and LaserCutter (mostly Shenzhen) are the biggest sources of downtime, so these are the first devices to prioritise for maintenance.
- Other devices (CNC, ConveyorBelt, Furnace, HeavyDutyDrill, AirWrench) contribute much smaller counts.

## 2. Equality table

`data/Task_5_Equality_Table.xlsx` lists each factory and job role with an **Equality Score** and an **Equality class**:

| Equality class | Meaning in this table |
| --- | --- |
| Fair | Score close to zero |
| Unfair | Moderately negative score |
| Highly Discriminative | Strongly negative score |

**Key findings**

- Gaps are concentrated in management and leadership roles. For example, C-Level (-25) and VP (-26) at Meiyo are both Highly Discriminative.
- Seiko's Sr. Manager, Manager and Jr. Manager roles are all Highly Discriminative.
- Engineering roles are mostly Fair across all four factories.
- Berlin has the fewest problem areas: only its management roles are Unfair, and the rest are Fair.

## Tools used

- Tableau (dashboard)
- Microsoft Excel (equality table)

## Skills demonstrated

Data analysis, data visualisation, comparing metrics across groups, and turning findings into clear recommendations.

## Certificate

Certificate of Completion issued by Forage, November 13th, 2026.
