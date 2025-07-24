# Snowflake-Hackathon
Bridging art, culture and tourism - Snowflake - streamlit Dashboard
🇮🇳 Indian Tourism Insights Dashboard
A data-driven tourism storytelling dashboard built using Snowflake and Streamlit that showcases regional art, culture, and tourist data across Indian states.




🚀 Features
✅ Interactive dashboard with state-wise analysis

✅ Top 10 tourist places and hotels (with images)

✅ Charts: Growth, Trends, Sites, Revenue, and more

✅ Built using Streamlit and deployed inside Snowflake

🛠️ Tech Stack
Component	Tool
Frontend	Streamlit (inside Snowflake)
Backend	Snowflake (Free Tier)
Data Format	CSV from data.gov.in
Visualization	Seaborn, Plotly, Matplotlib
Versioning	GitHub

📂 Folder Structure
=
my_tourism_dashboard/

├── streamlit_app.py  # Main app

├── Images/                       # Additional pages

├── data/tourism_data.csv        # CSV dataset

├── images/state_images/         # Top places images

├── utils/helpers.py             # Reusable code

├── environment.yml              # Python dependencies


🔧 Setup Instructions
1. Create a Snowflake Project
SQL


CREATE DATABASE TOURISM_DB;
CREATE SCHEMA TOURISM_SCHEMA;

3. Load Data
Upload tourism_data.csv into a table called TOURISM_DATA inside TOURISM_DB.TOURISM_SCHEMA.

4. Open Streamlit in Snowflake
In Snowsight:

Go to Projects > Streamlit

Click + Streamlit App

Choose your Warehouse, Database, and Schema

Paste the content of streamlit_app.py or connect GitHub source

4. Run Locally (Optional)
bash
Copy
Edit
streamlit run streamlit_app.py
📊 Visualizations Included
Bar chart: Annual Growth Rates

Line chart: Visitor Trends (Year-over-Year)

Word cloud: Top Tourist Sites

Heatmap: Correlation of Metrics

Scatter: Revenue vs Visitors

Bar chart: Monument Visits by Region

📽️ Demo & Links


🌐 Live App (Snowflake): (https://app.snowflake.com/btcdwng/crb65094/#/streamlit-apps/TOURISM_DB.TOURISM_SCHEMA.WWFX78HDIA9JG74G?ref=snowsight_shared)

📦 GitHub Repo: [Insert link]



📜 License & Open Source
This project uses:

Streamlit

Snowflake Free Tier

Plotly

data.gov.in (Government Open Data License)



#TEAM  MEMBERS:
#1.HARI HARAN
#2.MAHESWARAN
#3.NANDHAGOPAL
#4.RAMAR

