# 0x03. Queuing System in JS

## Tasks
### 0. Install a redis instance
- Download, extract, and compile the latest stable Redis version (higher than 5.0.7 - [https://redis.io/download/):](https://redis.io/download/)

### 1. Node Redis Client
- Install node_redis using npm

### 2. Node Redis client and basic operations
- In a file 1-redis_op.js, copy the code you previously wrote (0-redis_client.js).

### 3. Node Redis client and async operations
- Using promisify, modify the function displaySchoolValue to use ES6 async / await

### 4. Node Redis client and advanced operations
- In a file named 4-redis_advanced_op.js, let’s use the client to store a hash value

### 5. Node Redis client publisher and subscriber
- In a file named 5-subscriber.js, create a redis client:

### 6. Create the Job creator
- Create a queue with Kue

### 7. Create the Job processor
- In a file named 6-job_processor.js:
	* Create a queue with Kue
	* Create a function named sendNotification

### 8. Track progress and errors with Kue: Create the Job creator

### 9. Track progress and errors with Kue: Create the Job processor
- Create an array that will contain the blacklisted phone numbers. Add in it 4153518780 and 4153518781 - these 2 numbers will be blacklisted by our jobs processor.

### 10. Writing the job creation function

### 11. Writing the test for job creation
- Now that you created a job creator, let’s add tests:

### 12. In stock?
- Create an array listProducts containing the list of the following products:
