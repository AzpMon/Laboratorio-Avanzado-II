## Physic context of the problem


Let $\hat{H}$ be a hamiltonian in a quantum Hilbert space $\mathcal{H}$, then for its ground state:


<p align="center">
	$\hat{H} \ket{\Psi_0} = E_0 \ket{\Psi _0}$
</p>

with $E_0$ its eigenvalue, then the expected value:

<p align="center">
$\braket{H}_{\Psi_0} = \bra {\Psi _0} \hat{H} \ket{\Psi_0} =E_0\braket{\Psi |  \Psi}   = E_0$
</p>


For an arbitrary $\ket{\Psi} \in \mathcal{H}$, it can be showed:


<p align="center">
$\bra{\Psi _0} \hat{H} \ket{\Psi_0} \leq \bra{\Psi} \hat{H} \ket{\Psi} \Rightarrow \braket{H}_{\Psi_0} \leq   \braket{H}_{\Psi}$
</p>

Given $\hat{H}$, if we want to obtain the ground state we can propouse a parametrized state (an ansatz):


<p align="center">
	$\ket{\Psi (θ)} = \hat{W}_\theta \ket{0}^{\otimes n}$
</p>


and so we can attempt to find the parameters that characterize the ground state:


<p align="center">
$\ket{\Psi_0} = \hat{W}_θ \ket{0}^{\otimes n}$
</p>


then ,due the expected value of the hamiltonian in the groun states is less or equal to the expected value for an  arbitrary state, for  the ground state we must  find  the parameters of the operator     $\hat{W}$(θ)    that minimize the expected value for the Hamiltonian  $\hat{H}$  in    $\hat{W}$(θ) $\ket{0}^{\otimes n}$  , i,e   $\braket{H}$ $_{\Psi(θ)}$



We can encode our minimization problem of a cost function, the expected value, with a Variational Quantum Algorithm and  use tools like Pennylane! 


## Authors

#### Quantum Codebreakers

- [@Arnoldo Valdez](https://www.github.com/arnoldodany44)
- [@Alejandro Monroy](https://www.github.com/)
- [@Francisco Costa](https://www.github.com/podxboq)
- [@Sofía Salazar](https://www.github.com/nsalazard)
- [@Julio Moreno](https://www.github.com/pyspdev)

