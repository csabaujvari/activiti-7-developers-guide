## Scenario Set 4: Gateways
- [Exclusive Gateway with two User Tasks assigned to User 1 and User 2]()
  - Due a simple expression User 1 should see a task created after the exclusive gateway
- [Exclusive Gateway with Expression Error]()
  - It should fail at deployment time
  - For now we see an exception after the gateway is executed. The exception is reported by the first sequence flow that fails.
- [Parallel Gateway with two User Tasks assigned to User 1 and User 2]()
  - User 1 should see a task assigned after the parallel gateway
  - User 2 should see a task assigned after the parallel gateway
  - User 3 shouldn’t see any task
- [Parallel Gateway with two User Tasks assigned to Group 1 and Group 2]()
  - User 1 should see a task created after the parallel gateway
  - User 2 should see a task created after the parallel gateway
  - User 3 should see both tasks as candidate
