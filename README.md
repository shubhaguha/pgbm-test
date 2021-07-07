See [`pgbm`](https://github.com/elephaint/pgbm).

```bash
python3.8 -m venv pgbm-env
source pgbm-env/bin/activate

pip install -U pip
pip install pgbm

# Dependencies for examples
pip install scikit-learn matplotlib

# PyTorch example (CPU)
pip install torch torchvision torchaudio
python3.8 elephaint/pgbm/examples/pytorch/example01_bostonhousing_cpu.py

# Numba example
pip install numba
python3.8 elephaint/pgbm/examples/numba/example01_bostonhousing_cpu.py
```
