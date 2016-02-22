# ZRJC
Zephyr Rest Java Client

1. Import the jar file. 
2. Create the client 
    ZephyrRestClient client = ZephyrRestClientUtil.createZephyrRestClient(accessKey, secretKey, userName, zephyrBaseUrl);
3. Access the required APIs.
    JsonNode executionJson = client.getExecutionRestClient().getExecution(executionId, projectId, issueId);
