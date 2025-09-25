# FPMD

## Files in relax/algorithm

* `rf.py` — FPMD-R for MuJoCo environments
* `mf.py` — FPMD-M for MuJoCo environments
* `rf_v.py` — FPMD-R for DMControl environments
* `mf_v.py` — FPMD-M for DMControl environments

## Setup

* Install JAX:

  ```bash
  pip install --upgrade "jax[cuda12]==0.4.27" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
  ```
* Install other dependencies:

  ```bash
  pip install -r requirements.txt
  pip install -e .
  ```

## Run

* **State-based (MuJoCo)**: run `scripts/train_mujoco.py`.
* **Visual (DMControl)**: run `scripts/train_dmc_large_buffer.py`.
