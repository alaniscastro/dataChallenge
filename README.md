# Data Challenge

Obs: due to the existence off sensitive data on the code I won't add it here, but only the results.

The challenge consisted in designing a data architecture that could collect, ingest, store, and deliver information about fuels in Brasil in a organized and clean way.

To solve the challenge, I had to use these tools:
• Airflow: Create DAG to orchestrate;
• Google Cloud Storage: For storing Raw and Cured data;
• Big Query: For curated data storage;
• DataStudio or Looker: For creating the Dashboard;
• Google Cloud Dataproc: For data processing with Spark;
• Google Cloud Run: API to collect Fuel data.

The dashboard created had to contain the following info:
• Average value per liter of Sale by Fuel by time;
• Top 10 Average Sale Value X Purchase by Brand;
• Sale by Region;
• Higher and lower fuel prices;
• Range in Period;
• Average purchase and sale value/liter;
• Fuel price breakdown by establishment;
• Fuel price breakdown by period.

Result:
https://streamable.com/kskts1
