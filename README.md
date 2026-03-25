A collection of case studies designed to explore the fundamentals of AI and AI-Agents. 

**gd_optimisation** - This case study develops a path from calculus-based analysis to first-
order optimization. We begin by analyzing a one-dimensional function, deriving its piecewise form, stationary points, and global minimizers. We then relate the analysis to gradient descent (GD) and stochastic gradient descent (SGD): step-size choices, behavior near non-smooth points, and typical failure modes... [more details](gd_optimisation/README.md)


**nn_backpropagation** - This project introduces the essential “NN math” for a tiny feed-forward neural network: affine maps, nonlinear activations, scalar loss, and the backpropagation algorithm as a structured application of the chain rule. It implements a fully manual NumPy implementation (forward and backward) to PyTorch with and without autograd, and finally to nn.Module/nn.Sequential... [more details](nn_backpropagation/README.md)

**attoLLM** - This develops the core ideas behind modern transformer-based language models at a scale suitable for from-scratch implementation. Starting from sequence modeling and content-based attention, it
derive scaled dot-product attention, specialize it to self-attention, and assemble multi-head attention, position-wise feedforward networks, residual connections, and positional encodings into a standard transformer block. It then build a tiny decoder-only transformer language model, specify its training objective and sampling procedures, and map each concept to a set of NumPy/PyTorch implementations in an accompanying Colab
notebook... [more details](attoLLM/README.md)

**incident_agent** - This project is an example of agentic AI - a software that suggests solutions based on previous results and can take action by calling tools based on the generated plan. It uses a LLM stub for planning, MCP tools for gathering system data, and a simple semantic memory layer to understand and suggest a multi-step action plan for infrastructure issues... [more details](incident_agent/README.md)
