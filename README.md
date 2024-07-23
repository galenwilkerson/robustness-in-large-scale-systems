# Robustness in Large-Scale Systems

This repository explores the robustness of large-scale systems through the lens of network theory, focusing on the properties of scale-free networks. The key metric investigated is the scaling exponent, a measure of the degree distribution's power-law behavior in such networks.

## Overview

Large-scale systems often exhibit scale-free properties, characterized by power-law degree distributions. This project investigates:
1. The calculation and interpretation of the scaling exponent in Barabási-Albert (BA) networks.
2. The impact of network modifications on the scaling exponent.
3. The robustness of network characteristics such as scaling exponents, fractal dimensions, and other structural properties.

## Key Concepts

- **Scaling Exponent**: Reflects the degree distribution in a network. A typical BA network has a scaling exponent around 3.
- **Power-Law Distribution**: Indicates the presence of hubs (nodes with very high degrees) in the network.
- **Rewiring Operations**: Changing the network structure by rewiring edges to alter the scaling exponent.

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/galenwilkerson/robustness-in-large-scale-systems.git
cd robustness-in-large-scale-systems
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

The primary notebook for this project is `large scale system characteristics.ipynb`, which includes the following steps:

1. **Generating a BA Network**: Create a Barabási-Albert network with a specified number of nodes and edges.
2. **Computing Degree Distribution**: Calculate the degree distribution of the network.
3. **Fitting a Power-Law**: Use the `powerlaw` library to fit a power-law distribution to the degree distribution.
4. **Plotting CCDF**: Plot the Complementary Cumulative Distribution Function (CCDF) of the degree distribution along with the power-law fit.
5. **Modifying the Network**: Rewire a fraction of the network edges and observe the impact on the scaling exponent.

## Project Structure

- `large scale system characteristics.ipynb`: Jupyter notebook containing the analysis and visualization.
- `requirements.txt`: List of required Python packages.

## References

- Barabási, A.-L., & Albert, R. (1999). Emergence of Scaling in Random Networks. Science, 286(5439), 509-512.
- Clauset, A., Shalizi, C. R., & Newman, M. E. J. (2009). Power-law distributions in empirical data. SIAM Review, 51(4), 661-703.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by research on network theory and complex systems.
- Special thanks to the contributors and the open-source community for their invaluable tools and libraries.
