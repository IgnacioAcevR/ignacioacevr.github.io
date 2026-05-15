# Notes on Dispersive Equations

The idea I have in mind for these notes is to explain in my own words the classical book *"Non Linear Dispersive Equations: Local and Global Analysis"* by Terence Tao. This is a big project due to the consistency required each day to finish the task, where I will try to solve all the proposed exercices in the book.

## Chapter 1: Ordinary Differential Equations

### 1.1 General Theory

This section introduce the concept of an ODE an the associated Cauchy problem. Throughout this chapter, $\mathcal{D}$ will denote a finite dimensional vector space, endowed with the norm $\|\cdot\|_\mathcal{D}$. An *ordinary differential equation* is an equation which governs certain function $u:I\to\mathcal{D}$ mapping certain time interval $I\subset \mathbb{R}$ to the vector space $\mathcal{D}$. The most general form is the *fully nonlinear* ODE
$$
\tag{1}
G(u(t), \partial_t u,..., \partial_t^k u(t), t) = 0,
$$
where $k\geq1$ and $G:\mathcal{D}^{k+1}\times I \to X$ takes values in another finite-dimensional vector space $X$.

- $u\in \mathcal{C}_{loc}^k(I\to D)$ is a *classical solution* if ([1]()) holds for all $t\in I$.
- $\mathcal{D}$ is refered as the *state space*. One can view a PDE as a limiting case of ODE as dim($\mathcal{D}$) $\to \infty$.
