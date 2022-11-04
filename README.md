# Replacing Bearings in a Milling Machine
+ Simulation of a Reliability Problem. Replacing Bearings in a Milling Machine
+ Discrete Event System Simulation. Author: Jerry Banks
+ A Reliability Problem
+ This example compares two replacement policies for replacing bearings in a milling machine.
+ The example is a Monte Carlo simulation, not a dynamic event-based model, since events and clock times are not included. Each bearing life is randomly generated 15 times and the resulting costs computed.

+ A milling machine has three different bearings that fail in service. The distribution of the life of each bearing is identical, as shown in Table 2.22, When a bearing fails, the mill stops, a mechanic is called, and he or she installs a new bearing (costing $32 per bearing). The delay time for the mechanic to arrive varies randomly, having the distribution given in Table 2.23. Downtime for the mill is estimated to cost $10 per minute. The direct on-site cost of the mechanic is $30 per hour. The mechanic takes 20 minutes to change one bearing, 30 minutes to change two bearings, and 40 minutes to change three bearings. The engineering staff has proposed a new policy to replace all three bearings whenever one bearing fails. Management needs an evaluation of the proposal, using total cost per 10,000 bearing-hours as the measure of performance.
