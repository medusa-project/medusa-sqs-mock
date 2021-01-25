# SQS Mock for Medusa
Creates ElasticMQ queues mocking the Medusa-related queues in AWS Simple Queue Service for local development and testing.

## ElasticMQ Docker setup

# Dependency: Docker
<https://docs.docker.com/get-docker/>

# Clone the repository
$ git clone https://github.com/medusa-project/medusa-sqs-mock.git
$ cd medusa-sqs-mock

# Invoke
```docker build -t sqs-mock .```
```docker run --name sqs-mock -p 9324:9324 -d sqs-mock```
