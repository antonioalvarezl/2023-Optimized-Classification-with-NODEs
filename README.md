# Optimized Classification with NODEs
Codes from my article "Optimized Classification with Neural ODEs via Separability", jointly with Rafael Orive-Illera and Enrique Zuazua

We compute and represent a lower bound for the probability distribution of the number of discontinuities $k$ that the control functions of the neural ODEs need for binary classification of $N$ red points and $N$ blue points in $[0,1]^d$, via neural ODEs with a width of one neuron per layer.

These control functions $(w,a,b)$ are piecewise constant functions in time. 
The number of discontinuities that they exhibit bears some analogy to the number of layer changes needed in a discrete neural network for the same objective.

In this setting, the $2N$ points are randomly sampled from the uniform distribution in $[0,1]^d$.

# Citing
If you are using this toolbox for your scientific publication, we would be very appreciative if you were to cite the following article:

@misc{álvarezlópez2023optimized,
      title={Optimized classification with neural ODEs via separability}, 
      author={Antonio Álvarez-López and Rafael Orive-Illera and Enrique Zuazua},
      year={2023},
      eprint={2312.13807},
      archivePrefix={arXiv},
      primaryClass={math.OC}
}
