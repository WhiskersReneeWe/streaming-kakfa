# streaming-kakfa

Answers

1. changing values on the SparkSession property parameters increases or decreases processedRowsPerSecond.
2. I use spark.default.parallelism and spark.streaming.kafka.maxRatePerPartition to maximize processedRowsPerSecond.
