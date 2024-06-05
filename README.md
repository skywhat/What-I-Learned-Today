# What-I-Learned-Today
It is needless to be a big topic, even 1 minute reading is great!

# 06-04-2024
https://brooker.co.za/blog/2024/06/04/scale.html
Scale, and scalability, is not the major reason distributed systems are needed. Other practical reasons include
1. Availability, distributed systems achieve exponentially better availability at linear cost.
2. Durability, making multiple copies of data on multiple machines is the only credible way to make online data durable.
3. Utilization, achieve lower cost and higher utilization. https://brooker.co.za/blog/2023/03/23/economics.html
4. Latency, reduce tail latency by short-term system workload.
5. Specialization, allow components to be specialized for workloads that are latency-sensitive, throughput-sensitive, locality-sensitive, compute-intensive, memory-intensive etc.
6. Isolation, allow components to be optimized for the security properties.
7. Changes, allow for safe zero-impact patching and deployments.

# 05-01-2024
I start to have hands-on experience about Kubernetes, hpa is an interesting part about auto scaling. During my work, our service is not timely scaled up based on the simple metric of CPU utilization, but need to find a more comprehensive metric such as the combination of the metric of concurrency of requests with others.
https://kubernetes.io/docs/tasks/run-application/horizontal-pod-autoscale/

# 04-30-2024
[Why SQLite Uses Bytecode](https://sqlite.org/draft/whybytecode.html)
Looks like it is a big topic that I need to put much time here. Quickly went through this article is barely helpful.
https://www.sqlite.org/opcode.html

# 04-29-2024
[How an empty S3 bucket can make your AWS bill explode
](https://medium.com/@maciej.pocwierz/how-an-empty-s3-bucket-can-make-your-aws-bill-explode-934a383cb8b1)
1. Explicitly specify AWS regions when executing the request to avoid S3 API redirect cost.
2. Unauthorized requests ended up as being charged by PUT request, which is 0.005$ per 1k requests. https://aws.amazon.com/s3/pricing/

great discussion here. https://news.ycombinator.com/item?id=40203126
   
