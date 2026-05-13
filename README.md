# Paper
> "**A self-heating-based physics-guided neural network for fatigue life prediction of polymer matrix composites**"  
> Dr. Aravind Premanand, Gaurav Sharma, Prof. Dr. Frank Balle  

## Repository Structure

- `Jupyter notebooks/`: Contains the jupyter notebook implementing the code step by step for each dataset
- `Datasets/`: Original Data collected via experiments and cited through papers
- `requirements.txt`: List of packages used.

## Abstract
With the increasing use of polymer matrix composites (PMCs) in different engineering applications, there is a greater focus on their durability under cyclic loading conditions. Consequently, large efforts have been made to obtain accurate and reliable fatigue life models that encompass the complexity
of composite materials within a short time frame. This investigation employs a physics-informed neural network (PINN) with self-heating behavior embedded as soft physics constraints to predict the fatigue life of different PMCs reported in the literature. Due to the limited size of the data for each
PMC, which ranges from 12 to 21 samples, Monte-Carlo simulations were used to generate synthetic data that adhere to the distribution of the experimental data. K-fold cross validation is performed on the proposed PINN architecture to enable good prediction accuracy and generalization capability for small datasets. This model is applied to different PMCs loaded under
cyclic loading conditions, and the results show that fatigue life can be predicted using load levels and stabilized surface temperature with reasonable accuracy even for PMCs that exhibit scatter.

## Getting Started

### Prerequisites

Make sure Python 3.8+ and `pip` are installed.

To install the required libraries:

```bash
pip install -r requirements.txt
```
### How to Run
```bash
git clone https://github.com/Gaurav-Sharma21/MachineLearningWithPINN.git
cd MachineLearningWithPINN
```
### Running the notebook
To start the notebook in your browser
```bash
jupyter notebook
```
Then open the corresponding jupyter notebook from the Interface 
