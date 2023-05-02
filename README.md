# Data Challenge

Obs: due to the existence off sensitive data on the code I won't add it here, only the results.

The challenge consisted in designing a data architecture that could collect, ingest, store, and deliver information about fuels in Brasil in a organized and clean way.

To solve the challenge, I had to use these tools:<br/>
• Airflow: Create DAG to orchestrate;<br/>
• Google Cloud Storage: For storing Raw and Cured data;<br/>
• Big Query: For curated data storage;<br/>
• DataStudio or Looker: For creating the Dashboard;<br/>
• Google Cloud Dataproc: For data processing with Spark;<br/>
• Google Cloud Run: API to collect Fuel data.

The dashboard created had to contain the following info:<br/>
• Average value per liter of Sale by Fuel by time;<br/>
• Top 10 Average Sale Value X Purchase by Brand;<br/>
• Sale by Region;<br/>
• Higher and lower fuel prices;<br/>
• Range in Period;<br/>
• Average purchase and sale value/liter;<br/>
• Fuel price breakdown by establishment;<br/>
• Fuel price breakdown by period.<br/>

Result:
https://streamable.com/kskts1
