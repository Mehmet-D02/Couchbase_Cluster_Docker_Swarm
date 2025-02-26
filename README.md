# Couchbase Cluster Setup on Docker Swarm

## 🚀 Quick Start

Follow these steps to set up a Couchbase Cluster on Docker Swarm.

---

## 📦 1. Deploy the Stack

Deploy the Couchbase services using the provided Docker Compose YAML file:

```bash
docker stack deploy -c docker-couchbase.yaml couchbase
```

✅ This command initializes the Couchbase services on your Docker Swarm environment.

---

## 🛠️ 2. Create the Couchbase Cluster

Once the Couchbase services are running:

1. Make the cluster creation script executable:
   ```bash
   sudo chmod +x cluster_create.sh
   ```

2. Run the script to initialize the Couchbase cluster:
   ```bash
   ./cluster_create.sh
   ```

✅ This script automates the cluster creation and configuration process.

---

## ✅ Result

After these steps, your Couchbase cluster will be up and running on Docker Swarm, ready for use!