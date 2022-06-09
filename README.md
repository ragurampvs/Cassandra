**Table of Contents**
**Cassandra**
    Introduction
        Big Data & NoSQL
        Cassandra
    Installation & Configuration (Both Apache & DataStax)
        Prerequisite 
        Best Practices for PRODUCTION settings
        Installation (tar-ball based)
        Configuration
        CQLSH
    Data Architecture
        Nodes, Data Center & Racks
        Ring & Tokens
        Vnodes
        Gossip
        Snitch
        Replication
        Consistency
        Hinted HandOff
        Read & Write Path 
           Queries & Co-Ordinator node
           MemTable, SSTable & Commit Logs
           Bloom Filter, Caching
        Ani-Entropy, Repair & Merkle tree
        Compaction 
           Deletion & Tombstone
    CQL
    Data Modeling
    Monitoring 
        OpsCenter 
        Other tools (DataDog/Grafana & Promethus)
        OpenSource Reaper tool (Used for enabling repair for Cassandra Cluster)
    Performance & Tuning --> Include JVM Tuning
    Backup & Restore
        DSBulk
        CQLSH Copy
        Snapshot
        SSTableLoader
    Security
        Authentication and Authorization
            Password Authenticator
            Using CassandraAuthorizer
            Role-Based Access Control
        Encryption
            SSL, TLS, and Certificates
            Node-to-Node Encryption
            Client-to-Node Encryption
        JMX Security - Enabling JMX Access

