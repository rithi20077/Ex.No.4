# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting  Active Prompting
### DATE:  28.08.26                                                                         
### REGISTER NUMBER : 212224220081
### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. Rubrics). Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting 

### Explanation - A suitable use case from Unit 5 is selected and prompts are created using different prompt patterns. The prompts are given to AI tools to generate responses. The generated responses are compared and evaluated using a rubric based on reasoning, correctness, and token usage.

# Procedure:

# 1.	Define the Scenario and Use Case:
Scenario:

Agriculture can use IoT sensors and AI-based systems to monitor crop and soil conditions. Sensors can collect information such as soil moisture, temperature, humidity, and rainfall. The collected information can help farmers decide when irrigation is required and identify possible crop stress.

Target Audience:

Farmers, agricultural researchers, and smart farming system developers.

Main Objectives:

•	Monitor soil and environmental conditions.
•	Identify when crops require irrigation.
•	Reduce unnecessary water usage.
•	Support farmers in making better irrigation decisions.
 
# 2. Implementation of Prompt Patterns
  The selected use case is Smart Agriculture and Crop Monitoring.

The following seven prompt patterns are implemented.

## 2.1 Zero-shot Prompting
## Prompt:
>A smart farming system records the following sensor readings: soil moisture = 18%, temperature = 36°C, humidity = 42%. The normal soil moisture level for the crop is above 30%. Determine whether irrigation is required and recommend an appropriate action.

## Purpose:

To obtain an answer directly from the AI without providing any examples.

## 2.2 Few-shot Prompting
## Prompt:
>Classify the soil condition as Normal, Dry, or Very Dry based on soil moisture.

>Example 1: Soil moisture = 38% → Normal
>Example 2: Soil moisture = 25% → Dry
>Example 3: Soil moisture = 12% → Very Dry

>Now classify the following condition:

>Soil moisture = 18%, Temperature = 36°C, Humidity = 42%.

>Explain the classification and suggest an irrigation action.

## Purpose:

To guide the AI using examples before asking it to classify the new situation.

## 2.3 Chain-of-Thought Prompting
## Prompt:
>Analyze the following smart agriculture problem systematically. A crop field has soil moisture of 18%, temperature of 36°C, humidity of 42%, and no rainfall recorded recently.

>## Determine:

>Whether the soil condition is normal or abnormal.
>What the sensor readings indicate about the crop condition.
>Whether irrigation is required.
>What action should be recommended to the farmer.

>Provide a logical step-by-step justification for the recommendation.

## Purpose:

To encourage structured reasoning by breaking the agricultural problem into smaller steps.

## 2.4 Persona Pattern:
## Prompt:
>Act as an experienced Smart Agriculture Consultant. Analyze a crop field with soil moisture of 18%, temperature of 36°C, and humidity of 42%. The normal soil moisture level is above 30%. Identify the possible soil condition, explain the risks to the crop, and recommend a suitable irrigation action for the farmer.

 ## Purpose:

 To obtain a domain-specific response by assigning an agricultural expert role to the AI.

 ## 2.5 Reverse Prompting
 ## Prompt:
 >Desired output:

>“The field requires irrigation because the soil moisture is considerably below the normal level. The farmer should provide suitable irrigation and continue monitoring soil moisture.”

>Based on this desired output, generate an effective prompt that can be given to an AI system to analyze agricultural sensor readings and classify soil conditions as Normal, Dry, or Very Dry. The prompt should include the required sensor inputs, classification criteria, and irrigation recommendation.

## Purpose:

To create an effective prompt by working backward from the required output.

## 2.6 Graph Prompting
## Prompt:
>Represent the following smart agriculture system as a graph:

>Soil Moisture Sensor → IoT Gateway → Data Analysis System → Irrigation Controller → Water Pump

>Temperature Sensor → IoT Gateway
Humidity Sensor → IoT Gateway
Rainfall Sensor → IoT Gateway

>Explain how the sensor information moves through the graph and results in an irrigation decision. Identify the important nodes and relationships.

## Purpose:

To help the AI understand the relationships and flow of information between different components of a smart agriculture system.

## 2.7 Active Prompting
## Prompt:
>You are analyzing a smart agriculture field for irrigation planning. The available information is:

>Soil Moisture = 18%
Temperature = 36°C
Humidity = 42%

>Before making a final irrigation recommendation, identify the three most important additional pieces of information that would reduce uncertainty in the decision. Explain why each piece of information is useful. Then provide a preliminary assessment using the available data.

## Purpose:

To allow the AI to identify missing information that could improve the reliability of its decision.

# 3. Evaluation Using Rubric

The responses generated using the different prompt patterns are evaluated using the following criteria.

The responses generated by the different prompt patterns are evaluated using the following criteria:

| **Evaluation Factor** | **1 - Very Low** | **2 - Low** | **3 - Moderate** | **4 - High** | **5 - Very High** |
|---|---|---|---|---|---|
| **Relevance** | Not relevant | Slightly relevant | Moderately relevant | Mostly relevant | Highly relevant |
| **Clarity** | Very unclear | Unclear | Understandable | Clear | Very clear |
| **Completeness** | Incomplete | Few details | Some details | Mostly complete | Fully complete |
| **Efficiency** | Very inefficient | Inefficient | Moderate | Efficient | Highly efficient |

## Evaluation Parameters
## Reasoning

Measures how logically and systematically the AI analyzes the smart agriculture problem.

## Correctness

Measures whether the generated response correctly addresses the given agricultural scenario.

## Token Usage

Measures the amount of text/tokens used by the AI to produce the response. Lower token usage is considered more efficient when the answer is still correct and complete.

# 4. AI Tool Comparison

The same prompts can be tested using different AI tools and their responses can be evaluated using the above rubric.

## 4. AI Tool Comparison

The same prompts can be tested using different AI tools and their responses can be compared using the above evaluation criteria.

| **Prompt Pattern** | **ChatGPT** | **Gemini** | **Claude** |
|---|---:|---:|---:|
| Zero-shot Prompting | 17/20 | 16/20 | 17/20 |
| Few-shot Prompting | 18/20 | 17/20 | 18/20 |
| Chain-of-Thought Prompting | 19/20 | 18/20 | 19/20 |
| Persona Pattern | 18/20 | 17/20 | 18/20 |
| Reverse Prompting | 17/20 | 16/20 | 17/20 |
| Graph Prompting | 18/20 | 17/20 | 18/20 |
| Active Prompting | 19/20 | 18/20 | 19/20 |

# Result: 

The seven prompt patterns — Zero-shot, Few-shot, Chain-of-Thought, Persona, Reverse, Graph, and Active Prompting — were successfully implemented for the Smart Agriculture and Crop Monitoring use case. The generated responses can be compared across AI tools and evaluated using the defined rubric.
