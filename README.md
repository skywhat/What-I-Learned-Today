# What-I-Learned-Today
It is needless to be a big topic, even 1 minute reading is great!


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
   
