# Educational Notebooks for Lattice QCD

This folder contains comprehensive Jupyter notebooks designed to accompany the theoretical documentation in the `docs/` folder. Each notebook provides hands-on implementation and analysis exercises that reinforce the concepts covered in the lecture series.

## Notebook Structure

### Phase 1: Foundations (Weeks 1-2)
- **`exercise_1_1_free_particle.ipynb`**: Introduction to path integrals using the free particle as a concrete example. Students implement path integral simulation, study the continuum limit, and understand measure factors.

- **`exercise_1_2_harmonic_oscillator.ipynb`**: Monte Carlo simulation of the quantum harmonic oscillator. Covers basic Monte Carlo methods, autocorrelation analysis, and parameter optimization.

### Phase 2: Monte Carlo Methods (Weeks 3-4)
- **`exercise_2_1_metropolis_algorithm.ipynb`**: Implementation and analysis of the Metropolis-Hastings algorithm for field theory. Studies acceptance rates, step size optimization, and equilibration.

- **`exercise_2_2_markov_chains.ipynb`**: Deep dive into Markov chain properties, detailed balance, ergodicity, and convergence analysis.

### Phase 3: Advanced Algorithms (Weeks 5-6)
- **`exercise_3_1_hmc_optimization.ipynb`**: Comprehensive study of Hybrid Monte Carlo including leapfrog integration, energy conservation, parameter optimization, and comparison with Metropolis.

- **`exercise_3_2_field_theory_applications.ipynb`**: Application of Monte Carlo methods to scalar field theory, measurement of observables, and finite size scaling.

### Phase 4: Critical Phenomena and Acceleration (Weeks 7-8)
- **`exercise_4_1_critical_slowing_down.ipynb`**: Analysis of critical slowing down, implementation of multigrid acceleration, and exploration of machine learning acceleration techniques.

- **`exercise_4_2_advanced_topics.ipynb`**: Advanced acceleration methods including cluster algorithms, parallel tempering, and normalizing flows.

## Learning Objectives

Each notebook is designed to achieve specific educational goals:

1. **Conceptual Understanding**: Connect theoretical concepts to practical implementations
2. **Technical Skills**: Develop programming skills in scientific computing and simulation
3. **Analysis Techniques**: Learn statistical analysis methods for Monte Carlo data
4. **Critical Thinking**: Understand limitations, trade-offs, and optimization strategies
5. **Research Preparation**: Gain experience with methods used in current research

## Prerequisites

- Basic Python programming knowledge
- Familiarity with NumPy, Matplotlib, and SciPy
- Understanding of basic quantum mechanics and statistical mechanics
- Linear algebra and calculus background

## Required Packages

```python
import numpy as np
import matplotlib.pyplot as plt
import scipy
from tqdm import tqdm
import sklearn  # For machine learning exercises
```

## How to Use

1. **Sequential Learning**: Work through notebooks in order, as later exercises build on earlier concepts
2. **Interactive Exploration**: Modify parameters and explore "what if" scenarios
3. **Discussion Questions**: Each notebook includes thought-provoking questions for deeper understanding
4. **Extensions**: Advanced students can tackle the suggested extensions
5. **Documentation Reference**: Refer to corresponding sections in `docs/` for theoretical background

## Assessment Integration

These notebooks support the assessment framework outlined in `docs/SYLLABUS.md`:

- **Weekly Reports** (20%): Document findings and analysis from each notebook
- **Mid-term Project** (20%): Comprehensive analysis using techniques from multiple notebooks  
- **Final Project** (20%): Independent research project building on notebook techniques
- **Participation** (20%): Active engagement with notebook exercises and discussions
- **Practical Exam** (20%): Hands-on implementation and debugging

## Technical Notes

- **Performance**: Some exercises involve intensive computations; runtime estimates are provided
- **Memory**: Large lattices may require significant memory; guidance on resource management included
- **Visualization**: Extensive plotting for intuitive understanding of complex phenomena
- **Error Handling**: Robust implementations with proper error checking and user guidance

## Pedagogical Features

- **Progressive Complexity**: Each notebook builds systematically on previous knowledge
- **Multiple Approaches**: Different methods compared for same problems
- **Real-world Context**: Connections to current research and applications
- **Interactive Elements**: Widgets and dynamic visualizations where appropriate
- **Debugging Guides**: Common pitfalls and troubleshooting tips included

## Extensions and Projects

Advanced students can explore:

- **Custom Algorithms**: Implement novel Monte Carlo methods
- **Performance Optimization**: Parallelization and GPU acceleration
- **Machine Learning Integration**: Neural network-guided sampling
- **Research Applications**: Apply methods to current physics problems

## Support and Resources

- **Code Documentation**: All functions are well-documented with docstrings
- **Mathematical Background**: LaTeX equations explain underlying theory  
- **Literature References**: Connections to research papers and textbooks
- **Troubleshooting**: Common issues and solutions documented

These notebooks provide a comprehensive, hands-on introduction to lattice QCD methods that prepares students for both theoretical understanding and practical research applications.
