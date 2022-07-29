# Simulation Course Projects
## Probelm Statment
A workshop repairs all kinds of small machines. The workshop consists of five workstations and the flow of orders inside the workshop is as shown below:

<img width="656" alt="Screenshot 2022-07-29 175133" src="https://user-images.githubusercontent.com/102898063/181769386-08ef03ad-657d-4a85-965f-06fa5bbb6dbe.png">

Normal orders arrive at station A in 16±12 minutes. Urgent orders are received every 5±2 hours and except at station C, where they are placed on the conveyor belt along with all other orders and cleaning and degreasing operations are performed on them, they have a higher priority in the rest of the stations. The duration of handling orders and carrying out repairs at the first arrival of each order at each station is as follows:

<img width="546" alt="Screenshot 2022-07-29 175352" src="https://user-images.githubusercontent.com/102898063/181769797-37dc3b2b-63d3-45f3-9e11-8db1e2281fac.png">
These periods are true for all orders that go through one of two sequences, 𝐴 → 𝐵 → 𝐶 → 𝐷 → 𝐸 or 𝐴 → 𝐵 → 𝐷 → 𝐸. However, about 10% of orders leave from station D to station B to receive more service (which takes 27 ± 8 minutes). Then they are sent to D and finally to E.
The path of these orders is as follows:

<img width="277" alt="Screenshot 2022-07-29 181616" src="https://user-images.githubusercontent.com/102898063/181773816-f07b6e73-80bd-40cc-91d5-1f9d5809037f.png">

The degreasing station C is closed every two hours, one hour after the opening of the station, for daily maintenance and repair work, which takes 2 ± 10 minutes. But these normal maintenance and repair work will not be done until the maintenance of the possible machines at station C is completed.

A) First, introduce the system state variables. Then determine the main events and draw all the required flow charts. Then run the simulation model ten times independently, so that each time is equivalent to an 8-hour simulation run after a initialization of 2 hours. The main performance measure is the average response time, i.e. the sum of the time an order stays in the workshop. The workshop is never empty in the morning, but the model will be empty at the beginning of the setup period. Therefore, run the model for after 2 hours of the setup period and Collect data until 10 hours. This warm-up period reduces the downward bias of the average response duration estimate. Note that the 2-h warm-up period is a means of loading the simulation model at a more realistic level than the empty level. Additionally, using the simulation program, generate the tracking report in the desired time intervals. Also, using the 10 sample results, obtain the point and interval estimates of the following variables:

- Average response time (throughout the day and by different time periods)
- Average waiting time for mahchines in queues
- Average service time at workstations
- utilization each work station
- Average length of queues
- The longest waiting time in the queue
Generate the required random numbers with the mixed congruential method and make sure of their uniformity and independency.

B) The management is trying to add another worker in the busiest station (A, B, C, D). Does doing this significantly improve the average response time and other variables above?

C) As an alternative to option B, management intends to replace machine C with a faster machine with 15 minutes of service time. Would this significantly improve the average response time and the other variables above?
