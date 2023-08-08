# Prerequisites
Install pyenv

# Set up environment using pyenv
```bash
pyenv install anaconda3-2023.03
```
```bash
cd <path-to-repo>
```
```bash
pyenv local anaconda3-2023.03
```
```bash
python --version
```
```bash
conda create -n qiskit-runtime python=3.10.9
```
```bash
conda activate qiskit-runtime
```
```bash
pip install qiskit[visualization]
```
```bash
pip install qiskit-ibm-runtime
```
```bash
pip install ipykernel
```
```bash
python -m ipykernel install --user --name=qiskit-runtime --display-name="Qiskit (runtime)"
```
```bash
pip install rise
```
```bash
juptyer notebook
```