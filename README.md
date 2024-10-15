# SkyHack-FlyHigh
 
## Problem Statement
As United Airlines continues its journey to become the best airline in the history of aviation, it is crucial to provide world-class customer service, for which one of the key areas of focus is our call center operations. Call centers play a critical role in ensuring customer issues are resolved quickly and efficiently, but we face challenges in improving metrics such as Average Handle Time (AHT) and Average Speed to Answer (AST).

- Your task is to optimize these key call center metrics, helping reduce resolution times and providing faster, more efficient service to our customers. You are required to analyze our existing call center data to identify inefficiencies, determine the drivers of long AHT and AST, and suggest strategies to enhance customer satisfaction, reduce escalations, and improve overall operational efficiency.

## Background
In today’s competitive airline industry, providing efficient and reliable customer service is crucial for customer retention and loyalty. Our call center, which handles customer inquiries, complaints, and service requests, is an essential touchpoint for many of our passengers. However, the growing demand and complexity of services have made it increasingly important to optimize the operations of this critical channel.

*Average Handle Time (AHT)* and *Average Speed to Answer (AST)* are essential metrics that significantly impact call center performance by shaping customer satisfaction and operational efficiency. AHT measures the total time agents spend on each call, from answering to disconnecting, and provides insights into where processes can be streamlined. Reducing AHT without sacrificing quality allows agents to handle more calls with existing resources, improving service levels and controlling costs. Meanwhile, AST tracks how quickly customers reach assistance through self-service tools like IVR systems. A lower AST minimizes customer wait times, enhancing their experience and reducing call abandonment, ultimately supporting a more efficient and customer-friendly operation.

- United Airlines uses a mix of human agents and IVR systems to address customer needs. While IVR systems help automate simple tasks and reduce call volume for human agents, there’s an opportunity to streamline this process and better allocate resources between self-service and agent-based resolutions.

- How are AHT and AST Calculated?
-- AHT (Average Handle Time):
Time from when the agent picks up the call to when they hang up
Formula:
AHT = Total Handle Time / Total Number of Calls

-- AST (Average Speed to Answer):
Time spent by the customer in queue till the agent answers the call
Formula:
AST = Total Waiting Time / Total Number of Calls

## Deliverables:
1. Long average handle time (AHT) affects both efficiency and customer satisfaction. Explore the factors contributing to extended call durations, such as agent performance, call types, and sentiment. Identify key drivers of long AHT and AST, especially during high volume call periods. Additionally, could you quantify the percentage difference between the average handling time for the most frequent and least frequent call reasons?

2. We often observe self-solvable issues unnecessarily escalating to agents, increasing their workload. Analyse the transcripts and call reasons to identify granular reasons associated to recurring problems that could be resolved via self-service options in the IVR system. Propose specific improvements to the IVR options to effectively reduce agent intervention in these cases, along with solid reasoning to support your recommendations.

3. Understanding the primary reasons for incoming calls is vital for enhancing operational efficiency and improving customer service. Accurately categorizing call reasons enables the call center to streamline processes, reduce manual tagging efforts, and ensure that customers are directed to the appropriate resources. In this context, analyze the dataset to uncover patterns that can assist in understanding and identifying these primary call reasons. Please outline your approach, detailing the data analysis techniques and feature identification methods you plan to use. Optional task, you may utilize the `test.csv` file to generate and submit your predictions

Things to Note:

- Demonstrate your ability to write SQL/Python/R for the above stated tasks. Submit your code files along with instructions to run them. 
- Based on your analysis, provide actionable recommendations for optimizing call center performance. Share the story behind the data and suggest further areas of investigation that could deepen our understanding of underlying issues.
- Summarize your findings and recommendations in a concise, data-driven presentation (7-8 slides).
- Optional: Submit your predictions using the `test.csv` file in the following format: `test_<name>.csv` (e.g., `test_johndoe.csv`). The file should include the following columns:** 
call_id: The unique identifier for each call.

primary_call_reason: The predicted primary reason for each call.

## Submissions:

- Code Files, with instructions to run them
- Presentation (.ppt format)
- Optional: Test.csv
