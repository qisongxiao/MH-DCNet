# MH-DCNet  
The datasets of **MH-DCNet: An improved flow field prediction framework coupling neural network with physics solver**  
Authors: Qisong Xiao, Xinhai Chen, Jie Liu, Chunye Gong, Yufei Sun  

## Dataset Description
- **Flow field dataset**: Fixed geometry (NACA0012) with varying flow conditions (different Mach numbers and angles of attack).
- **Airfoil dataset**: Varying geometries (from the [UIUC airfoil database](https://m-selig.ae.illinois.edu/ads/coord_database.html)) under a fixed flow condition (Mach = 0.5, AoA = 5°).
- **Hybrid dataset**: Varying geometries (from the [UIUC airfoil database](https://m-selig.ae.illinois.edu/ads/coord_database.html)) under varying flow conditions (different Mach numbers and angles of attack).

---

If you find this work useful, please cite our paper:

```bibtex
@article{xiao2024mh,
  title={MH-DCNet: An improved flow field prediction framework coupling neural network with physics solver},
  author={Xiao, Qisong and Chen, Xinhai and Liu, Jie and Gong, Chunye and Sun, Yufei},
  journal={Computers \& Fluids},
  volume={284},
  pages={106440},
  year={2024},
  publisher={Elsevier}
}
