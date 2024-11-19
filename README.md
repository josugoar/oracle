# oracle

> Open request-response oracle supporting arbitrary data

## How to use

1. Deploy **Oracle.sol** or implement and deploy custom **IOracle.sol** interface.

2. Inherit from **OracleConsumer.sol** and deploy a contract that defines a callback for the oracle.

3. Define **ENDPOINT_URI**, **PRIVATE_KEY**, **ADDRESS**, **ABI** and **TASK_ID** in **.env** file and run **oracle_service** or use the provided interface in custom program.

4. Call the oracle from the oracle consumer to access off-chain data.
