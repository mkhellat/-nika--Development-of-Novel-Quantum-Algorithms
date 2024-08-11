# Development-of-Novel-Quantum-Algorithms
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 3
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Classiq. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1PGNUShboB4ik_JHZGcIPTh3KYi-aajzp/view?usp=sharing) to view the project description.

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.


### Team Information:
Team Member 1:
 - Mohammadreza Khellat: 
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-fvfEVepBZ3Z5pnp


Team Member 2:
 - Omid Abbasi: 
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx): WQ24-swBRhj7onRJZfRj



### Project Solution:
_Include a comprehensive summary of all important information about your project solution here._
All necessary code files and any additional information required to judge your project solution should be included in the repository.

The Quantum algorithm for the Hamiltonian simulation of a 1-dimensional
classical system of $N$ coupled oscillators have been thoroughly
reviewed.

In the end, our strategy for the deployment of the simulation in
Classiq has been to prepare a simple encoding, represent the
Hamiltonian as a matrix, and evolve it using the Suzuki Trotter.

We encountered an issue with Suzuki Trotter `qbv` parameter
reported at [commit
ac68f1db23ddece86e25c6d2ed0f86d0369940ea](https://github.com/womanium-quantum/Development-of-Novel-Quantum-Algorithms/commit/ac68f1db23ddece86e25c6d2ed0f86d0369940ea). A
closer study of the issue hinted us towards modifying the function
`matrix_to_pauli_terms(matrix)` to make sure that no redundant identity
Pauli terms are added to the operator and the size of our Hamiltonian
operator is not unnecessarily increased.

### Project Presentation Deck:
_Upload/ Link a 3min. presentation deck here._

See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)

