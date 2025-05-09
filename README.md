# CMPE-258-Assignment-7-Effective-AI-Agents-Design-Patterns-using-Langraph

This repository demonstrates various design patterns for building effective AI agents using LangGraph and Crew.ai frameworks. Each pattern is implemented in separate Colab notebooks with debug traces and comprehensive documentation.

## Design Patterns Implemented

### 1. Sequential Chain

A simple pattern where steps are executed in a predetermined sequence, with each step building on the output of the previous one.

### 2. Branching Logic

Demonstrates how to implement conditional branching in agent workflows, allowing the system to follow different paths based on conditions.

### 3. Loops and Cycles

Shows how to implement iterative processes where steps are repeated until a certain condition is met.

### 4. Dynamic State Management

Illustrates how to maintain and update state throughout the agent's execution cycle, allowing for context preservation.

### 5. Human-in-the-Loop

Implements patterns that incorporate human feedback and intervention at critical decision points.

### 6. Tool Usage

Demonstrates how agents can use external tools and APIs to extend their capabilities.

### 7. Supervision and Reflection

Shows mechanisms for self-monitoring, error detection, and performance improvement through reflection.

### 8. Multi-Agent Teams

Implements collaborative patterns where multiple specialized agents work together to solve complex tasks.

## Framework Implementations

### LangGraph

The LangGraph implementations utilize the LangChain framework with LangGraph for building complex agent workflows. Each notebook includes:

- Complete implementation of the pattern
- Integration with LangSmith for tracing and debugging
- Visualization of the agent's execution graph
- Detailed explanations of each component

Key features demonstrated:
- State management with TypedDict
- Graph construction with Pydantic models
- Use of conditional edges and cycles
- Integration with various LLM providers
- Advanced tracing and debugging with LangSmith

### Crew.AI

The Crew.AI implementations demonstrate the same patterns using the Crew.AI framework, which specializes in multi-agent systems. Each notebook includes:

- Complete implementation of the pattern
- Agent role definitions and team composition
- Task delegation and coordination mechanisms
- Process visualization and debugging

Key features demonstrated:
- Agent specialization and role assignment
- Task hierarchy and delegation
- Inter-agent communication
- Process supervision and orchestration

## Video Walkthroughs

This repository includes detailed video walkthroughs of all implemented patterns:

1. **LangGraph Walkthrough**: A comprehensive demonstration of all patterns implemented in LangGraph, including LangSmith traces and debugging.

2. **CrewAI Walkthrough**: A detailed walkthrough of the same patterns implemented in Crew.AI, highlighting differences in approach and capabilities.

**[Watch Complete Video Demonstrations on YouTube](https://youtu.be/4ngHNNSvwf0)**

The video demonstrations include:
- Pattern explanations and theoretical background
- Implementation details and code walkthroughs
- Live executions with example inputs
- Analysis of execution traces
- Debugging techniques and common issues
- Performance considerations
- Comparative analysis between frameworks
- Best practices and recommendations for production use

## Requirements

- Python 3.10+
- LangChain
- LangGraph
- Crew.AI
- OpenAI API key (or other LLM provider)
- LangSmith API key (for tracing LangGraph implementations)
- Various dependencies specified in each notebook

## Usage

1. Clone this repository
2. Open the notebooks in Google Colab
3. Add your API keys in the designated cells
4. Execute the notebooks to see the patterns in action

## References

- [Building Effective Agents (YouTube)](https://www.youtube.com/watch?v=aHCDrAbH_go)
- [LangGraph Workflows Tutorial](https://langchain-ai.github.io/langgraph/tutorials/workflows)
- [Workflow and Agents Notion Page](https://mirror-feeling-d80.notion.site/Workflow-And-Agents-17e808527b1780d792a0d934ce62bee6)
- [DeepLearning.AI - AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [Crew.AI Documentation](https://docs.crewai.com/)

## Implementation Details

Each notebook follows a consistent structure:

1. **Introduction**: Explanation of the pattern and its applications
2. **Setup**: Installation of dependencies and API configuration
3. **Implementation**: Step-by-step implementation of the pattern
4. **Demonstration**: Example use cases and execution results
5. **Tracing and Debugging**: Visualization of the execution flow
6. **Analysis**: Discussion of advantages, limitations, and best practices
7. **Extensions**: Suggestions for extending or customizing the pattern
