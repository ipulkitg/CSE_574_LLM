# CSE_574_LLM


## Overview
Welcome to a showcase of my assignment exploring the application of reasoning and planning to enhance Large Language Models (LLMs) in problem-solving. This project focuses on the implementation of the Chain-of-Thought (CoT) method (Wei et al., 2022) to prompt LLMs in solving a series of questions. Additionally, I have implemented standard few-shot and standard zero-shot methods for comparative analysis. The chosen LLM for this task is the powerful 13B open-sourced Llama2.

Implemented Prompting Methods
Few-shot CoT (explicit CoT demonstrations)
Zero-shot CoT (prompting with "Let’s think step by step")
Standard Few-shot (prompting with examples)
Standard Zero-shot (prompting without examples)
Technical Setup: Llama2 in Google Colab
To begin, I successfully set up the 13B Llama2 LLM in Google Colab. I utilized a provided notebook that installed all required packages and loaded the LLM model. For a step-by-step guide, I followed the video tutorial. The assignment specified the use of the free T4 GPU on Google Colab, and I made sure to provide clear evidence of the successful execution in the submitted .ipynb file.

Testing CoT: Showcasing Problem Solving
Once Llama2 was deployed successfully, I conducted comprehensive testing of the four prompting methods on three distinct test cases. I performed each test case five times for robust evaluation, calculated the average accuracy for each method, and visually represented the results through insightful bar charts.

Test Case 1 - Math World Problem
Question:
"A waiter had 14 customers. If 3 left and 39 more arrived, how many customers would he have?"

Test Case 2 - Date Understanding Problem
Question:
"The concert was scheduled for 06/01/1943 but delayed by one day. What is the date 10 days ago?"

Test Case 3 - Coinflip Problem
Question:
"A coin is heads up. Ka flips the coin. Sherrie flips the coin. Is the coin still heads up?"

Evaluation and Visualization
I meticulously evaluated the performance of each prompting method, calculated the average accuracy for each test case, and created visually appealing bar charts to showcase the comparative analysis. The results provide insights into the effectiveness of different prompting strategies.

Conclusion
Thank you for exploring this showcase of my work. This assignment reflects my dedication to leveraging cutting-edge technologies for problem-solving and showcases my proficiency in deploying and evaluating large language models. Feel free to reach out for further discussions or collaborations!
