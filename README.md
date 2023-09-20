# CIAMOD
### Applications of computational methods and artificial intelligence to the study of moduli spaces

## Table of Contents

1. [Project Objectives](#project-objectives)
2. [Getting Started](#getting-started)
    1. [Prerequisites](#prerequisites)
    2. [Installation](#installation)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)

## Project Objectives

Traditionally, mathematics has been the driving force behind advancements in AI and computing. Recent developments like ChatGPT have invigorated the debate around whether computers can assist mathematicians in theorem proving. This project aims to explore the possibility of using AI and computing to advance our understanding of various open problems in theoretical mathematics.

Specifically, the project employs cutting-edge computing and artificial intelligence techniques to study problems related to the geometry of moduli spaces of bundles and additional structure bundles such as parabolic, Higgs, and twisted Higgs. These moduli spaces have recently gained much attention in algebraic geometry and appear in various fields like representation theory, number theory, the classification of solutions to PDEs, and multiple formulations of particle physics models.

The research focuses on the following areas:

### Stability Chambers Analysis in Parabolic Bundle Moduli Spaces

The geometry of parabolic bundle moduli spaces depends non-trivially on the selected parabolic weights and bundle degrees for its construction. Pairs of these parameters are grouped into stability chambers, where the moduli do not vary and can be represented as regions of a hypercube. Some chambers are also related by transformations identifying their moduli spaces. The objective is to estimate the number of distinct parabolic moduli spaces and to study their birational geometry using computer-assisted techniques.

### Motivic Decompositions of Vector Bundle and L-Higgs Bundle Moduli Spaces

Grothendieck's motive of a variety is an invariant that provides extensive information about its geometry. Manipulating motivic formulas and understanding when two distinct expressions can represent the same variety is complex but mathematically interesting. The goal is to develop a software package that allows efficient manipulation and comparison of these motives, and apply it to low-rank proofs of the Mozgovoy Conjecture on the motive of the L-Higgs moduli.

### Study of Generalized Markov Triples and Their Relation to Higgs Moduli Spaces

Markov triples are integer solutions to the equation \(x^2 + y^2 + z^2 = 3xyz\). These triples structure themselves in so-called Markov Trees, subject to famous conjectures in Number Theory. The generalized triples are solutions to \(x^2 + y^2 + z^2 = 3xyz + m\). The theory behind these triples is yet to be developed. We propose using computational techniques to explore various conjectures about their structure. Additionally, starting from Fricke's identities that relate Markov triples to points in representation moduli spaces, we aim to delve into the relationship between generalized triples and parabolic Higgs bundle moduli spaces.

## Getting Started

### Prerequisites

- Python >= 3.7
- PyTorch >= 1.9.0
- NumPy

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/your_username/AI_for_Math_Development.git
   ```
2. Install the required packages
   ```sh
   pip install -r requirements.txt
   ```
## Usage

Instructions on how to run the software or code will be updated soon.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file in each repository for details.

## Acknowledgments

Special thanks to everyone who contributed to the project:

- David Alfaya Sánchez (PI), Department of Applied Mathematics, ICAI, IIT
- Javier Rodrigo Hitos, Department of Applied Mathematics, ICAI
- Luis Ángel Calvo Pascual, Department of Quantitative Methods, ICADE
- Anitha Srinivasan, Department of Quantitative Methods, ICADE
- José Portela González, Department of Quantitative Methods, ICADE, IIT
- Jaime Pizarroso Gonzalo, Department of Telematics and Computing, ICAI
- Tomás Luis Gómez de Quiroga, Institute of Mathematical Sciences, UAM-UCM-UC3M-CSIC
- Daniel Sánchez Sánchez, Student of the Degree in Mathematical Engineering and Artificial Intelligence, ICAI
- Alejandro García Martínez de Guinea, Student of the Degree in Mathematical Engineering and Artificial Intelligence, ICAI
- Sergio Herreros Pérez, Student of the Degree in Mathematical Engineering and Artificial Intelligence, ICAI

Citation placeholders will be filled as research progresses.

