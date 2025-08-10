<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="description" content="README for the Big Data Summer Training — NTI &amp; ITIDA." />
</head>
<body>
  <div class="container">
    <h1>Big Data Training — NTI</h1>
    <p>This repository contains lab work, Jupyter notebooks, and concise notes produced during the Big Data Summer Training. It focuses on practical commands, examples, and reusable snippets.</p>
    <h2>What you'll find here</h2>
    <ul>
      <li>Jupyter Notebooks &amp; lab exercises (organized by topic folders)</li>
      <li>Technical notes and key takeaways</li>
      <li>Practice examples, datasets, and use-case simulations</li>
      <li>Commands, configuration snippets, and environment setup</li>
    </ul>
    <h2>Topics covered</h2>
    <ul>
      <li>Big Data Era &amp; Kunpeng Architecture</li>
      <li>HDFS + ZooKeeper — distributed storage and cluster coordination</li>
      <li>HBase + Hive — NoSQL and distributed data warehousing (SQL-like)</li>
      <li>ClickHouse — OLAP database for fast analytics</li>
      <li>MapReduce + YARN — distributed processing and resource manager</li>
      <li>Spark + Flink — batch and stream processing</li>
      <li>Flume + Kafka — data ingestion and real-time messaging pipelines</li>
      <li>Elasticsearch — search and analytics</li>
    </ul>
    <h2>Tools &amp; technologies</h2>
    <table>
      <thead>
        <tr><th>Tool / Tech</th><th>Use case</th></tr>
      </thead>
      <tbody>
        <tr><td>Linux, SQL, Python</td><td>Foundations for scripting and querying</td></tr>
        <tr><td>HDFS</td><td>Distributed data storage</td></tr>
        <tr><td>Hive</td><td>SQL-style querying on big data</td></tr>
        <tr><td>HBase</td><td>NoSQL for large-scale datasets</td></tr>
        <tr><td>Kafka</td><td>Real-time messaging</td></tr>
        <tr><td>Spark &amp; Flink</td><td>Data processing engines (batch &amp; stream)</td></tr>
        <tr><td>ClickHouse</td><td>High-performance analytics</td></tr>
        <tr><td>Flume, Sqoop</td><td>Data ingestion from logs and DBs</td></tr>
        <tr><td>Elasticsearch</td><td>Search and analytics</td></tr>
        <tr><td>ZooKeeper</td><td>Cluster coordination</td></tr>
      </tbody>
    </table>
    <h2>Example commands</h2>
    <pre><code># HDFS (pseudo-distributed)
hdfs namenode -format
start-dfs.sh
start-yarn.sh

# Kafka (local)
bin/zookeeper-server-start.sh config/zookeeper.properties &
bin/kafka-server-start.sh config/server.properties</code></pre>
    <h2>Repository structure (suggested)</h2>
    <pre><code>/README.html        ← this file (HTML README)
/notebooks/          ← Jupyter notebooks organized by topic
/data/               ← sample datasets (small, non-sensitive)
/scripts/            ← helper scripts and setup commands
/notes/              ← short markdown notes and key takeaways</code></pre>
    <h2>Goal of this repo</h2>
    <ul>
      <li>Personal reference and step-by-step notes</li>
      <li>Complete recap of the training with runnable examples</li>
      <li>Practical showcase of Big Data skills for projects, interviews, or collaborations</li>
    </ul>
    <h2>Let's connect</h2>
    <p>If you'd like to collaborate or discuss Big Data topics, reach out on LinkedIn or open an issue in this repo.</p>
    [Duaa Abd-Elati](https://www.linkedin.com/in/duaa-abdelati-abdelazeem) Connect on LinkedIn 
    <footer>
      <small>Made during the NTI Big Data Summer Training — you may reuse or adapt this README.</small>
    </footer>
  </div>
</body>
</html>
