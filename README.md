# Agentic AI Demo

This project demonstrates the concept of agentic AI and how it differs from traditional agents. It provides a practical implementation that showcases how AI systems can autonomously plan, execute tasks, and adapt to changing environments with minimal human intervention.

## What is Agentic AI?

Agentic AI refers to AI systems that can:
- Set their own goals based on high-level directives
- Plan and execute complex tasks autonomously
- Learn from interactions and adapt behavior
- Maintain long-term memory and context
- Coordinate multiple specialized tools and sub-agents
- Self-critique and improve performance

## Key Differences from Traditional Agents

| Traditional Agents | Agentic AI |
|-------------------|------------|
| Follow rigid, predefined rules | Develop flexible strategies based on goals |
| Execute single tasks | Handle complex multi-step workflows |
| Limited tool usage | Dynamically selects and coordinates multiple tools |
| Require explicit instructions | Operate with high-level objectives |
| Limited memory and adaptation | Learns from past experiences |
| Single-domain expertise | Integrates knowledge across domains |

## Project Structure

- `src/`: Core agentic AI implementation
- `examples/`: Sample use cases and demonstrations
- `utils/`: Helper functions and utilities
- `config/`: Configuration files
- `data/`: Sample data for demonstrations

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set up your OpenAI API key:
   ```
   export OPENAI_API_KEY=your_api_key_here  # Linux/macOS
   set OPENAI_API_KEY=your_api_key_here     # Windows CMD
   $env:OPENAI_API_KEY='your_api_key_here'  # Windows PowerShell
   ```
4. Run the demo using the provided scripts:
   ```
   # Windows
   run_demo.bat
   
   # Linux/macOS
   ./run_demo.sh
   ```
   
   Or run specific demos directly:
   ```
   # Research demo
   python run_demo.py --demo research --topic "climate change" --depth medium
   
   # Task planner demo
   python run_demo.py --demo task --goal "plan a company event" --complexity medium
   
   # Tool orchestration demo
   python run_demo.py --demo tools --task "analyze and summarize data about renewable energy" --detail medium
   
   # Self-improvement demo
   python run_demo.py --demo improvement --task "create a marketing strategy" --iterations 3
   
   # Comparison demo
   python run_demo.py --demo comparison --task "find information about machine learning"
   ```

## Examples Included

- Research Assistant: Autonomously researches topics, synthesizes information, and generates reports
- Task Planner: Breaks down complex goals into actionable tasks and executes them
- Tool Orchestration: Demonstrates how agentic AI can coordinate multiple specialized tools
- Self-Improvement: Shows how agentic AI can critique its own performance and adapt over multiple iterations
- Comparison Demo: Directly compares traditional agents with agentic AI on the same tasks

## License

MIT
