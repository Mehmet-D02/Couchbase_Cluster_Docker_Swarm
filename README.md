# Couchbase_Cluster_Docker_Swarm

# 1.Create stack with Yaml
docker stack deploy -c docker-couchbase.yaml couchbase

# After the couchbase services are running
# 2.Create the Couchbase cluster with cluster_create.sh
sudo chmod +x cluster_create.sh
./cluster_create.sh