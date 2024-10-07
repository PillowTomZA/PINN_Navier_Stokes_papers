# Research papers for Physics-Informed Neural Network (PINN)

This repository is inspired by [Intelligent Design and Robus Learning Laboratory (IDRL)](https://github.com/idrl-lab/PINNpapers?tab=readme-ov-file).

This is structured to first help readers gain a general understanding of Physics-Informed Neural Network, with a targeted focus on fluid-mechanics-related papers later. Finally, links to different PINN packages, frameworks, and non-PINN papers are shown in the last section.

Last updated: 2024-10-07


## Table of Content
- [Original Paper](#original-paper)
- [Literature Reviews](#literature-reviews)
- [Fluid Mechanics](#fluid-mechanics)
- [PINN Packages](#pinn-packages)
- [Frameworks, Mitigating Pathologies](#frameworks-and-mitigating-pathologies)
- [Non-PINN Papers](#non-pinn-papers)
- [Acknowledgement](#acknowledgements)

## Original Paper
1. **Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations**, *M. Raissi, P. Perdikaris, G.E. Karniadakis*, Journal of Computational Physics, 2019. [[paper](https://www.sciencedirect.com/science/article/pii/S0021999118307125)][[code](https://github.com/maziarraissi/PINNs)]

## Literature Reviews
1. **Physics-informed machine learning**, *George Em Karniadakis, Ioannis G Kevrekidis, Lu Lu, Paris Perdikaris, Sifan Wang, Liu Yang*, Nat. Rev. Phys., 2021. [[paper](https://www.nature.com/articles/s42254-021-00314-5#citeas)]
2. **Physics-informed neural networks (PINNs) for fluid mechanics:
a review**, *Shengze Cai, Zhiping Mao, Zhicheng Wang, Yin,
Minglang, George Em Karniadakis*, Acta Mech. Sin., 2022. [[paper](https://link.springer.com/article/10.1007/s10409-021-01148-1)]
3. **Deep learning in computational mechanics**, *Stefan Kollmannsberger, Davide D'Angella, Moritz Jokeit, Leon Herrmann*, **UNKNOWN_JOURNAL**, 2021. [[paper](http://dx.doi.org/10.1007/978-3-030-76587-3)]
4. **Scientific Machine Learning Through Physics--Informed Neural
Networks: Where we are and What's Next**, *Salvatore Cuomo, Vincenzo Schiano Di Cola, Giampaolo,
Fabio, Gianluigi Rozza, Maziar Raissi, Piccialli,
Francesco*, J. Sci. Comput., 2022. [[paper](https://arxiv.org/abs/2201.05624)]
5. **The old and the new: Can physics-informed deep-learning replace
traditional linear solvers?**, *Stefano Markidis*, Front. Big Data, 2021. [[paper](https://arxiv.org/abs/2103.09655)]
6. **Physics-informed neural networks for heat transfer problems**, *Shengze Cai, Zhicheng Wang, Sifan Wang, Perdikaris,
Paris, George Em Karniadakis*, J. Heat Transfer, 2021. [[paper](https://doi.org/10.1115/1.4050542)]
7. **Physics-informed neural network (PINN) evolution and beyond: A
systematic literature review and bibliometric analysis**, *Zaharaddeen Karami Lawal, Hayati Yassin, Daphne
Teck Ching Lai, Azam Che Idris*, Big Data Cogn. Comput., 2022. [[paper](https://doi.org/10.3390/bdcc6040140)]
8. **A review of physics-informed machine learning in fluid mechanics**, *Pushan Sharma, Wai Tong Chung, Bassem Akoush, Ihme,
Matthias*, Energies, 2023. [[paper](https://doi.org/10.3390/en16052343)]
9. **A review of physics-informed machine learning in fluid mechanics**, *Pushan Sharma, Wai Tong Chung, Bassem Akoush, Ihme,
Matthias*, Energies, 2023. [[paper](https://www.mdpi.com/1996-1073/16/5/2343)]

## Fluid Mechanics
1. **Physics-informed deep learning for incompressible laminar flows**, *Chengping Rao, Hao Sun, Yang Liu*, Theor. Appl. Mech. Lett., 2020. [[paper](https://www.sciencedirect.com/science/article/pii/S2095034920300350)][[code](https://github.com/Raocp/PINN-laminar-flow)]
2. **Investigation of physics-informed deep learning for the
prediction of parametric, three-dimensional flow based on
boundary data**, *Philip Heger, Daniel Hilger, Markus Full, Hosters,
Norbert*, Comput. Fluids, 2024. [[paper](https://www.sciencedirect.com/science/article/pii/S0045793024001348)]
3. **On physics-informed deep learning for solving Navier-stokes
equations**, *Cahya Amalinadhi, Pramudita S Palar, Rafael Stevenson, Lavi Zuhal*, 2022. [[paper](https://www.researchgate.net/publication/357562862_On_Physics-Informed_Deep_Learning_for_Solving_Navier-Stokes_Equations)]
4. **NSFnets (Navier-Stokes flow nets): Physics-informed neural
networks for the incompressible Navier-Stokes equations**, *Xiaowei Jin, Shengze Cai, Hui Li, Karniadakis,
George Em*, J. Comput. Phys., 2021. [[paper](https://www.sciencedirect.com/science/article/pii/S0021999120307257)]
5. **Physics-informed neural networks for high-speed flows**, *Zhiping Mao, Ameya D Jagtap, George Em Karniadakis*, Comput. Methods Appl. Mech. Eng., 2020. [[paper](https://www.sciencedirect.com/science/article/pii/S0045782519306814)]
6. **Active training of physics-informed neural networks to aggregate
and interpolate parametric solutions to the Navier-Stokes
equations**, *Christopher J Arthurs, Andrew P King*, J. Comput. Phys., 2021. [[paper](https://www.sciencedirect.com/science/article/pii/S002199912100259X)]
7. **Dynamic weight strategy of physics-informed neural networks for
the 2D Navier-Stokes equations**, *Shirong Li, Xinlong Feng*, Entropy (Basel), 2022. [[paper](https://arxiv.org/abs/2005.05092)]
8. **Physics-informed neural networks for solving Reynolds-averaged
Navier--Stokes equations**, *Hamidreza Eivazi, Mojtaba Tahani, Philipp Schlatter, Ricardo Vinuesa*, Phys. Fluids (1994), 2022. [[paper](https://pubs.aip.org/aip/pof/article/34/7/075117/2847279/Physics-informed-neural-networks-for-solving)][[code](https://github.com/Shengfeng233/PINN-for-turbulence)]
9. **Turbulence modeling for physics-informed neural networks:
Comparison of different RANS models for the backward-facing
step flow**, *Fabian Pioch, Jan Hauke Harmening, Andreas
Maximilian Muller, Franz-Josef Peitzmann, Dieter Schramm, Ould el
Moctar*, Fluids, 2023. [[paper](https://www.mdpi.com/2311-5521/8/2/43)]
10. **Three-dimensional physics-informed neural network simulation in
coronary artery trees**, *Nursultan Alzhanov, Eddie Y K Ng, Yong Zhao*, Fluids, 2024. [[paper](https://www.mdpi.com/2311-5521/9/7/153)]
11. **Surrogate modeling for fluid flows based on physics-constrained
deep learning without simulation data**, *Luning Sun, Han Gao, Shaowu Pan, Jian-Xun Wang*, Comput. Methods Appl. Mech. Eng., 2020. [[paper](https://www.sciencedirect.com/science/article/pii/S004578251930622X)]
12. **On the choice of activation functions in physics-informed
neural network for solving incompressible fluid flows**, *Duong V Dung, Nguyen D Song, Pramudita S Palar, Lavi R Zuhal*, American Institute of Aeronautics and Astronautics, 2023. [[paper](https://doi.org/10.2514/6.2023-1803)]

## PINN Packages
1. **DeepXDE: A deep learning library for solving differential equations**, *Lu Lu, Xuhui Meng, Zhiping Mao, George Em Karniadakis*, SIAM Review, 2021. [[paper](https://arxiv.org/abs/1907.04502)][[code](https://github.com/lululxvi/deepxde)][[documentation](https://deepxde.readthedocs.io/en/latest/)]
2. **SciANN: A Keras/TensorFlow wrapper for scientific
computations and physics-informed deep learning using artificial
neural networks**, *Ehsan Haghighat, Ruben Juanes*, Comput. Methods Appl. Mech. Eng., 2021. [[paper](https://www.sciencedirect.com/science/article/pii/S0045782520307374)][[code](https://github.com/ehsanhaghighat/sciann)][[documentation](https://www.sciann.com/)]
3. **NVIDIA SimNet™: An AI-Accelerated Multi-Physics
Simulation Framework**, *Oliver Hennigh, Susheela Narasimhan, Mohammad
Amin Nabian, Akshay Subramaniam, Kaustubh Tangsali, Fang,
Zhiwei, Max Rietmann, Wonmin Byeon, Sanjay Choudhry*, **ICCS**, 2021. [[paper](https://link.springer.com/chapter/10.1007/978-3-030-77977-1_36)]


## Frameworks, and mitigating pathologies
1. **Understanding and mitigating gradient pathologies in
physics-informed neural networks**, *Sifan Wang, Yujun Teng, Paris Perdikaris*, **UNKNOWN_JOURNAL**, 2020. [[paper](https://arxiv.org/abs/2001.04536)]
2. **An extended physics informed neural network for preliminary
analysis of parametric optimal control problems**, *Nicola Demo, Maria Strazzullo, Gianluigi Rozza*, **UNKNOWN_JOURNAL**, 2021. [[paper](https://arxiv.org/abs/2110.13530)]
3. **Physics-informed neural networks with hard constraints for
inverse design**, *Lu Lu, Rapha{\"e}l Pestourie, Wenjie Yao, Wang,
Zhicheng, Francesc Verdugo, Steven G Johnson*, SIAM J. Sci. Comput., 2021. [[paper](https://epubs.siam.org/doi/10.1137/21M1397908)][[code](https://github.com/lululxvi/hpinn)]
4. **Locally adaptive activation functions with slope recovery for
deep and physics-informed neural networks**, *Ameya D Jagtap, Kenji Kawaguchi, George Em Karniadakis*, Proc. Math. Phys. Eng. Sci., 2020. [[paper](https://royalsocietypublishing.org/doi/10.1098/rspa.2020.0334)]
5. **A practical PINN framework for multi-scale problems with
multi-magnitude loss terms**, *Yong Wang, Yanzhong Yao, Jiawei Guo, Zhiming Gao*, J. Comput. Phys., 2024. [[paper](https://www.sciencedirect.com/science/article/pii/S0021999124003619)]

## Non-PINN papers
1. **Navier--stokes Generative Adversarial Network: a
physics-informed deep learning model for fluid flow generation**, *Pin Wu, Kaikai Pan, Lulu Ji, Siquan Gong, Feng, Weibing, Wenyan Yuan, Christopher Pain*, Neural Comput. Appl., 2022. [[paper](https://www.researchgate.net/publication/359075523_Navier-stokes_Generative_Adversarial_Network_a_physics-informed_deep_learning_model_for_fluid_flow_generation)]
2. **Geometry aware physics informed neural network surrogate for
solving Navier--Stokes equation (GAPINN)**, *Jan Oldenburg, Finja Borowski, Alper {\"O}ner, Klaus-Peter Schmitz, Michael Stiehm*, Adv. Model. Simul. Eng. Sci., 2022. [[paper](https://amses-journal.springeropen.com/articles/10.1186/s40323-022-00221-z#citeas)]
3. **Physics-driven learning of the steady Navier-Stokes
equations using deep Convolutional neural networks**, *Hao Ma, Yuxuan Zhang, Nils Thuerey, Xiangyu Hu, Oskar J Haidn*, arXiv physics.flu-dyn 2106.09301, 2021. [[paper](https://arxiv.org/abs/2106.09301)]

## Acknowledgements
This project uses code from [PINNpapers](https://github.com/idrl-lab/PINNpapers/tree/main) by [weipengOO98](https://github.com/idrl-lab/PINNpapers/commits?author=weipengOO98), available at https://github.com/idrl-lab/PINNpapers/tree/main under the MIT License.