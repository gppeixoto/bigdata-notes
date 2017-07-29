# bigdata-notes

## AI / Machine Learning

### Fairness / Model Auditing
- FairML: Auditing Black-Box Predictive Models [[blog](http://blog.fastforwardlabs.com/2017/03/09/fairml-auditing-black-box-predictive-models.html)]
- [oxford] European Union regulations on algorithmic decision-making and a “right to explanation” [[arxiv](https://arxiv.org/pdf/1606.08813.pdf)]


### Scalable Machine Learning

- Billion-scale similarity search with GPUs [[arxiv](https://arxiv.org/pdf/1702.08734.pdf)]
- [uber] Scalable Machine Learning as a Service [[arxiv](http://proceedings.mlr.press/v67/li17a/li17a.pdf)]
- Distributed XGBoost on YARN [[docs](https://xgboost.readthedocs.io/en/latest/tutorials/aws_yarn.html)]
- Clipper: A Low-Latency Online Prediction Serving System [[slideshare](https://www.slideshare.net/SparkSummit/clipper-a-lowlatency-online-prediction-serving-system-spark-summit-east-talk-by-dan-crankshaw)][[paper](https://rise.cs.berkeley.edu/wp-content/uploads/2017/02/clipper_final.pdf)]
- Ray: A distributed execution framework for emerging AI applications [[talk](https://www.oreilly.com/ideas/ray-a-distributed-execution-framework-for-emerging-ai-applications-full-keynote-post)][[github](https://github.com/ray-project/ray)]

### Analytics
- [fb] Prophet - Forecasting at scale [[docs](https://facebookincubator.github.io/prophet/)]

## Spark

- Mastering Apache Spark 2 [[gitbook](https://www.gitbook.com/book/jaceklaskowski/mastering-apache-spark/details)]
- Databricks Spark Knowledge Base [[gitbook](https://www.gitbook.com/book/databricks/databricks-spark-knowledge-base/details)]
- Open Sourcing TensorFlowOnSpark: Distributed Deep Learning on Big-Data Clusters [[link](https://yahoo.tumblr.com/post/157196637189/open-sourcing-tensorflowonspark-distributed-deep)]

### Spark Streaming

- Long-running Spark Streaming on YARN Cluster [[link](http://mkuthan.github.io/blog/2016/09/30/spark-streaming-on-yarn/)]
- 24/7 Spark Streaming on YARN in Production [[link](https://www.inovex.de/blog/247-spark-streaming-on-yarn-in-production/)]


## General Architecture

- Questioning the Lambda Architecture [[oreilly](https://www.oreilly.com/ideas/questioning-the-lambda-architecture)]
- Using Presto in Our Big Data Platform on AWS [[medium](https://medium.com/netflix-techblog/hadoop-platform-as-a-service-in-the-cloud-c23f35f965e7)]
- Hadoop Platform as a Service in the Cloud [[medium](https://medium.com/netflix-techblog/hadoop-platform-as-a-service-in-the-cloud-c23f35f965e7)]
- The Log: What every software engineer should know about real-time data's unifying abstraction [[lkdn](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying)]
- Data Infrastructure at Airbnb [[medium](https://medium.com/airbnb-engineering/data-infrastructure-at-airbnb-8adfb34f169c#.qf6fnbkxq)]
- Spinning Up a Free Hadoop Cluster: Step by Step [[medium](https://blog.insightdatascience.com/spinning-up-a-free-hadoop-cluster-step-by-step-c406d56bae42#.k30g6iamd)]
- Personalization at Spotify using Cassandra [[link](https://labs.spotify.com/2015/01/09/personalization-at-spotify-using-cassandra/)]
- IoT Analytics Platform [[link](https://blog.codecentric.de/en/2016/07/iot-analytics-platform/)]
- Running Presto and Spark on the Netflix Big Data Platform [[slideshare](https://www.slideshare.net/AmazonWebServices/bdt303-running-spark-and-presto-on-the-netflix-big-data-platform)]
- Running Presto in our Big Data Plaftform on AWS [[link](http://techblog.netflix.com/2014/10/using-presto-in-our-big-data-platform.html)]
- [netflix] Can Spark Streaming survive Chaos Monkey? [[link](http://techblog.netflix.com/2015/03/can-spark-streaming-survive-chaos-monkey.html)]
- [soundcloud] A Better Model of Data Ownership [[link](https://developers.soundcloud.com/blog/a-better-model-of-data-ownership)]

## Pipeline

### Airflow

- Airflow + Kubernetes (discussion) [[youtube](https://www.youtube.com/watch?v=5BU3YPYYRno)]
- Airflow at WePay [[link](https://wecode.wepay.com/posts/airflow-wepay)]
- A Guide on How To Build An Airflow Server/Cluster [[link](https://stlong0521.github.io/20161023%20-%20Airflow.html)]
- How Agari Uses Airbnb's Airflow As A Smarter Cron [[link](http://highscalability.com/blog/2015/9/3/how-agari-uses-airbnbs-airflow-as-a-smarter-cron.html)]
- Airflow: Tips, Tricks, and Pitfalls [[link](https://medium.com/handy-tech/airflow-tips-tricks-and-pitfalls-9ba53fba14eb#.efdfqp58p)]
- Scheduling Spark jobs with Airflow [[link](https://blog.insightdatascience.com/scheduling-spark-jobs-with-airflow-4c66f3144660#.3iqu1n40e)]
- Automated Model Building with EMR, Spark and Airflow: [[link](https://www.agari.com/automated-model-building-emr-spark-airflow/)]
- Advanced Airflow: TriggerDagRunOperator: [[link](https://www.linkedin.com/pulse/airflow-lesson-1-triggerdagrunoperator-siddharth-anand)]
- Running Apache Airflow Workflows as ETL Process on Hadoop: [[link](https://www.slideshare.net/RobertSanders49/running-apache-airflow-workflows-as-etl-processes-on-hadoop)]

## Monitoring

- Monitoring Spark on Hadoop with Prometheus and Grafana [[link](http://rokroskar.github.io/monitoring-spark-on-hadoop-with-prometheus-and-grafana.html)]
- Monitoring Spark with Graphite and Grafana [[link](http://www.hammerlab.org/2015/02/27/monitoring-spark-with-graphite-and-grafana/)]

## SysOps

- spark-ec2 [[github](https://github.com/amplab/spark-ec2)]
- yarn-ec2 [[github](https://github.com/tqchen/yarn-ec2)]
- kube-yarn [[github](https://github.com/Comcast/kube-yarn)]
- apache-spark-on-k8s [[github](https://github.com/apache-spark-on-k8s/spark)]
- Spark Cluster using Multi-Node Kubernetes and Docker [[link](https://datasterix.com/2016/09/03/spark-cluster-using-multi-node-kubernetes-and-docker/)]
- hdfs2cass - Hadoop mapreduce job to bulk load data into Cassandra [[github](https://github.com/spotify/hdfs2cass)]
