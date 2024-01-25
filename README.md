# Football Data Engineering

This Python-based project crawls data from Wikipedia using Apache Airflow, cleans it and pushes it Azure Data Lake for processing.


## System Architecture
![system_architecture.png](assets%2Fsystem_architecture.png)

## Requirements
- Python 3.9 (minimum)
- Docker
- PostgreSQL
- Apache Airflow 2.6 (minimum)

## Getting Started

1. Clone the repository.
   ```bash
   git clone https://github.com/airscholar/FootballDataEngineering.git
   ```

2. Install Python dependencies.
   ```bash
   pip install -r requirements.txt
   ```
   
## Running the Code With Docker

1. Start your services on Docker with
   ```bash
   docker compose up -d
   ``` 
2. Trigger the DAG on the Airflow UI.

## How It Works
1. Fetches data from Wikipedia.
2. Cleans the data.
3. Transforms the data.
4. Pushes the data to Azure Data Lake.

!!!
Make sure to replace `your_access_key_here` with the actual Azure Container Access Key in the `.env` file.

## Tableau Dashboard
https://public.tableau.com/app/profile/aygyun.salim/viz/Football_Stadiums_Project/MainDasboard?publish=yes
![image](https://github.com/AygyunS/Football-data-engineering-project/assets/32463645/f6786db4-7d72-4103-b4f1-2ea48a702da7)




