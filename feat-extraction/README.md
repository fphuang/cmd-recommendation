## Feature Enrichment interface

### Main features

1. Consume PubSub message from the gateway service
2. Look up the available pipeline engine and trigger it
    - DB: pipeline engine availability table
    - Transaction priority
3. Update the transaction status
4. Consume the message from the pipeline engine to update the pipeline engine availability


Key Concepts:
- Manage the multiple pipeline engine repo
- Transaction priority