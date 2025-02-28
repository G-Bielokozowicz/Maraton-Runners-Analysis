# Marathon Runners Statistical Analysis 
![Runners-Boylston-Street-Boston-Marathon-April-18-2016-2610626098](https://github.com/user-attachments/assets/eed03006-ecd2-4540-85cf-62810fd77819)

A comprehensive analysis of marathon runners' performance, demographics, and global trends using a dataset of over 1.4 million entries. This project explores relationships between age, gender, country, event characteristics, and athletic performance.




## Dataset Overview

The dataset contains the following columns:

| Column Name                     | Description                              | Data Type   |
|---------------------------------|------------------------------------------|-------------|
| Year of event                   | Year the event took place                | `int64`     |
| Event dates                     | Dates of the event (start/end)           | `object`    |
| Event name                      | Name of the event                        | `object`    |
| Event distance/length           | Original distance description            | `object`    |
| Event number of finishers       | Total finishers in the event             | `int64`     |
| Athlete performance             | Official performance time (hh:mm:ss)     | `object`    |
| Athlete country                 | Athlete's nationality                    | `object`    |
| Athlete year of birth           | Birth year of athlete                    | `int64`     |
| Athlete gender                  | Gender (M/F)                             | `object`    |
| Athlete average speed           | Average speed in km/h                    | `float64`   |
| Athlete ID                      | Unique athlete identifier                | `int64`     |
| Athlete age                     | Age at time of event                     | `int64`     |
| Month of event                  | Month the event occurred (1-12)          | `int64`     |
| Country Code                    | ISO country code of event location       | `object`    |
| Event distance (km)             | Standardized distance in kilometers      | `float64`   |
| Athlete run time (h)            | Performance time converted to hours      | `float64`   |

## Data preparation

The following steps were taken to prepare the data for analysis:

- Extracting country code from event name
- Calculating athlete age
- Converting athlete performance from HH:MM:SS string to more usable format
- Removing null values and outliers


# Data analysis

## Athlete statistics

Even though there's 3 times more man than women, all statistics show similar distribution for each gender.

![obraz](https://github.com/user-attachments/assets/6f9c78dd-9c11-4791-96f3-bf145a083c6d)

![obraz](https://github.com/user-attachments/assets/c9611574-880c-4c26-b699-12f44336b7ad)

In shorter runs (50km and 56km) the performance time barelly decreases with age, but in 100km run there's a massive dip

![obraz](https://github.com/user-attachments/assets/9b2874c5-97ee-4669-b8e2-629d1de18f3f)

![obraz](https://github.com/user-attachments/assets/fa925950-a270-4637-95d2-2abe9889f44a)

The 56km and 100km distances have very sharp increase in the average speed at 8 km/h

![obraz](https://github.com/user-attachments/assets/e35d6c77-90b6-48e0-8b35-e144d109dbfa)


## Yearly trends analysis

Over time the average speed of the athlete has been decreasing.

![obraz](https://github.com/user-attachments/assets/470f2779-cc56-4036-8ced-dd115d978ec6)

Number of events per year has been steadily increasing over time, with big dip when COVID-19 happened.

![obraz](https://github.com/user-attachments/assets/3eab3344-8f7a-451e-b107-e64ad4b3f9fd)


Number of participants in events has also been steadily increasing over time.

![obraz](https://github.com/user-attachments/assets/7c2241fd-fcce-4332-b23c-db778a143c40)

The average performance time is slightly increasing. 

![obraz](https://github.com/user-attachments/assets/31b5b25d-d329-41cd-9588-934cf5bac624)

## Country analysis

The top country by number of athletes is different for each race distance. In 50km it's USA, in 56km events it's South Africa and in 100km events it's Japan

![obraz](https://github.com/user-attachments/assets/8d840753-39a3-403d-8d33-814b99e533d8)

USA hosts the most 50km and 100km events, while France is hosting the most 56km events.

![obraz](https://github.com/user-attachments/assets/c20ef90e-082d-4ef2-9715-0a84d2b6dccf)

The fastest runners are mostly from African countries

![obraz](https://github.com/user-attachments/assets/ccff2f05-22ab-4762-8b82-e361e5df3888)


