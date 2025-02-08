# Build AI Agents with PhiData

![image](https://github.com/user-attachments/assets/890410f3-cdb5-45c1-bed8-dbf5733e8927) ![image](https://github.com/user-attachments/assets/3b63cff8-cd04-4cd1-9d63-30af3a1659d6)

This Repo explores the creation of autonomous AI agents using the PhiData platform, focusing on financial data analysis and information retrieval. The project is divided into three segments:

1. **Basic Simple Agent for Demonstration**
2. **Finance Agent Utilizing YFinance**
3. **A Team of Agents for Comprehensive Stock Analysis**

## Project Segments

### 1. Basic Simple Agent for Demonstration

In this initial segment, we develop a straightforward agent to demonstrate the foundational concepts of agentic AI. This agent serves as an introduction to building autonomous systems capable of performing tasks with minimal human intervention.

### 2. Finance Agent Utilizing YFinance

Here, we create a finance-focused agent that leverages the [YFinance](https://pypi.org/project/yfinance/) library to fetch stock information, perform analyses, and generate insights. This agent demonstrates how AI can be applied to financial data to assist in decision-making processes.

### 3. A Team of Agents for Comprehensive Stock Analysis

In the final segment, we design a collaborative system comprising multiple agents:

- **Analysis Agent**: Analyzes stock information to provide detailed insights.
- **News Retrieval Agent**: Fetches the latest news related to specific stocks using the [DuckDuckGo](https://pypi.org/project/duckduckgo-search/) search tool.

This collaborative approach showcases the power of agentic AI in handling complex, multi-faceted tasks.

## Tools and Technologies Used

- **PhiData**: An open-source platform for building, deploying, and monitoring agentic systems. [Learn more](https://medium.com/@shravankoninti/phidata-an-open-source-platform-to-build-ship-and-monitor-agentic-systems-adaade78b003)
- **Groq**: Provides high-performance API endpoints for large language models. [Documentation](https://docs.phidata.com/models/groq)
- **YFinance**: A Python library for accessing financial data from Yahoo Finance.
- **DuckDuckGo**: Utilized for retrieving the latest news related to specific stocks.
- **Model Used**: Llama3.3-70B Versatile

## Concepts of Agentic AI

Agentic AI refers to systems capable of autonomously performing tasks on behalf of users or other systems by designing workflows and utilizing available tools. These agents can make decisions, solve complex problems, and interact with external environments beyond their initial programming. [Read more](https://www.ibm.com/think/insights/agentic-ai)

Key characteristics of agentic AI include:

- **Autonomy**: Ability to operate without continuous human oversight.
- **Adaptability**: Capacity to adjust actions based on changing environments and new information.
- **Goal-Oriented Behavior**: Designed to achieve specific objectives set by developers or users.

## Model Selection for Cost-Effectiveness and Accuracy

In developing agentic AI systems, it's essential to balance cost and performance. Different agents within a system can utilize various language models based on their specific tasks:

- **Base Agents**: For routine tasks, employing smaller, cost-effective models can be sufficient.
- **Main Agents**: For complex tasks requiring higher accuracy, integrating advanced models like GPT-4.0 is advisable.

This strategy ensures that resources are allocated efficiently, maintaining both performance and cost-effectiveness.

**Note**: The performance of an agent is directly influenced by the quality of the language model employed. Utilizing more advanced models can enhance an agent's ability to perform complex tasks effectively.

---

By following this structure, the **Build AI Agents with PhiData** project demonstrates the practical application of agentic AI concepts, showcasing how different tools and models can be integrated to create autonomous systems tailored to specific tasks. 
