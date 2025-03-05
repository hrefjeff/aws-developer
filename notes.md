# SQS, SNS, & Kinesis

## Intro
  a. Synchronous vs. Asynchronous communication
  b. Decouple apps with SQS (queue model), SNS (pub/sub model), Kinesis (real time streaming)

## SQS

1. Producer sends message to queue (process this order, process this video)
2. Consumer polls the queue for messages (I see an order, I'll start processing it)
3. Oldest services provided by Amazon
4. Unlimited throughput, unlimited # of messages in queue
5. Default 4 days of retention, max of 14 days
6. Low latency (<10 ms on publish/receive)
7. Limitation of 256KB per messsage sent
8. Can have duplicate messages, they can be out of order
9. 
