# Exception Insights

## LookupError
**What it usually indicates:**
A lookup operation failed to find the requested key or index

**Most likely causes:**
- Attempting to access a missing key or element
- Invalid index or identifier used in a lookup
- Data structure does not contain the requested item

**Typical fix direction:**
Review the lookup operation and ensure the key, index, or identifier exists before accessing it

## TimeoutError
**What it usually indicates:**
An operation exceeded the allowed time limit and was aborted

**Most likely causes:**
- Slow or unresponsive external resource
- Network latency or connectivity issues
- Operation requires more time than configured timeout

**Typical fix direction:**
Increase the timeout value if appropriate, or optimize the operation to complete within the allowed time
