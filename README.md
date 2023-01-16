# Algebraic-Equation-in-PINN

As the newly prevalent techniques, Physics Informed Neural Network (PINN), came out, it has solved several higher dimensional space equation, such as Navier-Stokes 
equation, Schrödinger equation, etc. With respect to its capability in solving PDEs, ODEs, I was wondering what if I deploying such model in simple algebraic equations
to universally approximate the outcomes ? 

Since I'm now stuying how to renew, reconstruct the parameters on Shue et al.[1997/1998] (Emprical magnetopause model, utilizing in-situ observations from satellite
such as THEMIS, Interbal ...), I was on got recruited by J.H. Shue to his research team to tackle on different methods to fit his model. 

The picture below is the function form of Shue et al.[1997/1998], which is clearly an algebraic equation. Now that I pursuing solving this equation to inverse the 
parameters of it. I have to examine what on earth the PINN can be applied on simple algebraic equation ? That's why I validated it via sinusodial wave (Sine).
