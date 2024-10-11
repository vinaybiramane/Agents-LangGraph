# Viral Instagram Caption Generator

This project demonstrates the creation of advanced AI agents using LangChain and LangGraph to generate viral Instagram post captions. It showcases three different approaches, each building upon the previous one:

1. LangChain Agent from Scratch
2. Reflection Agent for Writing Viral Instagram Captions
3. Reflexion Agent with Additional Tools (Tavily Search)

## 1. LangChain Agent from Scratch

This section demonstrates how to build a basic LangChain agent that generates Instagram captions.

Key components:
- Azure OpenAI integration
- Custom prompt templates
- Basic chain structure

## 2. Reflection Agent for Writing Viral Instagram Captions

Building upon the basic agent, this section introduces a reflection mechanism to improve caption quality.

Key features:
- Self-critique and reflection
- Iterative improvement process
- Pydantic models for structured output

## 3. Reflexion Agent with Additional Tools (Tavily Search)

The final evolution of the agent incorporates external tools and a more complex workflow.

Highlights:
- Integration with Tavily Search API for real-time information
- LangGraph for managing complex agent workflows
- Multiple iterations of research and refinement

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/viral-instagram-caption-generator.git
   cd viral-instagram-caption-generator
   ```

2. Install dependencies:


3. Set up environment variables:
   Create a `.env` file with your API keys:
   ```bash
   AZURE_OPENAI_API_KEY=your_azure_openai_api_key
   AZURE_OPENAI_ENDPOINT=your_azure_openai_endpoint
   TAVILY_API_KEY=your_tavily_api_key
   ```

4. Run the Jupyter notebook:


5. Follow the notebook cells to generate viral Instagram captions using different agent configurations.

## Project Structure

- `reflexion_agent.ipynb`: Main Jupyter notebook containing all agent implementations
- `requirements.txt`: List of Python dependencies
- `.env`: Environment variables (not tracked in git)

## Dependencies

- langchain
- langgraph
- azure-openai
- tavily-python
- pydantic
- jupyter

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

