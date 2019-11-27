How to Run it:



docker volume create --name=gitlab_log

docker volume create --name=gitlab_data

docker volume create --name=gitlab_config

docker volume create --name=redis_data

docker volume create --name=postgres_data

docker volume create --name=runner_config

docker-compose up -d
