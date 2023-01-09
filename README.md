# Introduction 

When a vehicle is manufactured by an automobile company, there are many tests and quality checks carried out to authenticate the performance of the car. Most of these tests and quality checks are time-consuming and require a lot of money to perform. Moreover, the testing of these cars requires intensive manual labor since these vehicle models are hand-made. Factory machines are not programmed with the technology to produce such types of cars. It ensures that the model being designed meets all the requirements set by the company and is ready to get into the production stage.

The work presented solves the problem of vehicle testing schedules using <b> Lawler’s algorithm </b>. Since the process is time-consuming, the advised method takes into consideration the available time and points out the tardy job/lateness that can either be removed or the processing time can be reduced by efficient means. This method would curb the problem for technical planners to use fewer resources and utilize all the time by simultaneously working on multiple testing. This method in the long run will help companies to save money, time, and resource workload.

# Procedure
## Algorithm

-  Set the value of k (k= number of unscheduled jobs/ numbers of available spaces)
- Calculate the value of τ

<p align="center"> <img  alt="equation"  src="assets/Equation.jpg"  width="75%" /></p>

- Create a pool of jobs, having no followers/successors
- Create a cost/penalty/tardiness pool
- Select a job having minimum tardiness and place the job in the last position
- Update the value of k, τ , Pool
- Proceed until you get the optimal schedule
- Follow the "Backward scheduling procedure"

## Case Study

Developed a case study to optimise the schedule of the vehicle testing using Lawler’s Algorithm. There are 10 jobs, each job performs quality checks in a specific area of the vehicle. It takes about 3-6 months to manufacture a Mercedes Benz customized vehicle. Assuming that 80% of the time is required to assemble the vehicle and the rest 20% of the time is required for testing. This leaves us with 36 days for testing (6 months to manufacture). There are 8 cars that are being tested simultaneously in the testing bench. The objective function is to reduce the lateness in each job.
<table>
<tr>
<th> Jobs </th>
<th> J1 </th>
<th> J2 </th>
<th> J3 </th>
<th> J4 </th>
<th> J5 </th>
<th> J6 </th>
<th> J7 </th>
<th> J8 </th>
<th> J9 </th>
<th> J10 </th>
</tr>
<tr> 
<th> Pi (Processing time) </th>
<th> 14 </th>
<th> 25 </th>
<th> 32 </th>
<th> 29 </th>
<th> 28 </th>
<th> 30 </th>
<th> 38 </th>
<th> 36 </th>
<th> 25 </th>
<th> 31 </th>
</tr>
<tr>
<th> Di (Due Date) </th>
<th> 18 </th>
<th> 28 </th>
<th> 26 </th>
<th> 20 </th>
<th> 30 </th>
<th> 37 </th>
<th> 35 </th>
<th> 32 </th>
<th> 35 </th>
<th> 37 </th>
</tr>

Solving the above 10/1/Tmax and find the optimal schedule.

## Network Diagram
<p align="center"> <img  alt="network_Diagram"  src="assets/Network_Diagram.png"  width="75%" /></p>

## Conclusion

With the increase in the demand for production as well as an increase in the costs of testing vehicles’ performances, Lawler’s algorithm is a very powerful tool for scheduling and finding out tardiness. Implementation of both ongoing processes in Mercedes with Lawler’s algorithm will prove to be more efficient and optimal. The overall time and costs can be saved that in turn will help in building the profits of the vehicle. Through Lawler’s algorithm we are able to reduce the lateness and find the most optimal schedule. This will improve the overall efficiency in the production facility.