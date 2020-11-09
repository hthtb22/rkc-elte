# rkc-elte
Course: https://github.com/feipaat/Numerical-Methods-for-ODEs-1.-ELTE-/blob/master/List_Group_Projects

Code files for project #3: RKC methods.

Written by Hoang Trung Hieu.

| File        | Mean        | Figure        |
| :---        |    :----:   |          ---: |
| cheb_poli.ipynb      | The Chebyshev polynomials      | Figure[1]   |
| abs_reg_without.ipynb   | Abs. stability region  of Undamped RKC - first order      | Figure[2]     |
| und_sec.ipynb   | Abs. stability region  of Undamped RKC - second order      | Figure[3]     |
| damped_first_order.ipynb   | Abs. stability region  of damped RKC - first order      | Figure[4]     |
| damped_second_order.ipynb   | Abs. stability region  of damped RKC - second order      | Figure[5]     |
| RKC_first_order.ipynb   | The first-order RKC program  for test problem     | Table[1]   |
| rkc5 stage.ipynb   | The RKC5 program for test problem    | Table[2]     |
| rkc10.ipynb   | The RKC10 program  for test problem     | Table[2]     |
| heat (1).ipynb   | The RKC10 program  for heat problem     | Figure[6.1]  +Table[3]   |
| heat (2).ipynb   | The RKC15,19,25 program  for heat problem     | Figure[6.2]+ Table[3]     |
| heat++.ipynb   | The RKC30,40,50 program  for heat problem     | Table[3]   |
| diffusion.ipynb   | The RKC10 program  for diffusion problem     | Figure[7]    |


# Remark.
1. Since all the equations we work with, the matrix do not contain $t$. In order to reduce the computational cost and to avoid mismatching dimension, I intentionally change the value of time in the loop.
2. Some programs are not really optimal in the way computing the Chebyshev polynomials, but I still keep it to show different way to work with it.
