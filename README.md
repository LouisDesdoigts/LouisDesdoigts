<p align="center">
<a href="https://github.com/LouisDesdoigts">
    <img src="https://github-stats-alpha.vercel.app/api?username=louisdesdoigts&cc=22272e&tc=37BCF6&ic=fff&bc=0000">
</a>
</p>

---

# Louis Desdoigts  

Hi, I’m Louis 👋  
I’m a Postdoctoral Researcher at **Leiden Observatory** 🌙🔭 working in instrumentation and methods for Astrophysics with [Sebastiaan Haffert](https://github.com/syhaffert). I completed my PhD at Sydney University under the guise of [Peter Tuthill](http://www.physics.usyd.edu.au/~gekko/) and [Benjamin Pope](https://github.com/benjaminpope/).

My PhD focused on differentiable programming in astronomy — building end-to-end forward models where the entire optical + detector chain is treated as one differentiable system. Autodiff makes this practical for the first time, so most of my work involved designing the software, algorithms, and numerical tools needed to actually do this in real instruments. This included developing hybrid forward models (physics-based models with small embedded ML components for the messy or unknown parts) and figuring out how to apply them to real observational problems.

I first built and tested these ideas for the [**Toliman** space telescope](https://toliman.space/), and then extended them significantly for the **JWST NIRISS interferometer**, where detector non-linearities and charge-migration effects require a full physics–ML treatment. These projects fed directly into the modelling philosophy laid out in my thesis: treat simulation and inference as the same object, and model the whole measurement process instead of stitching together many independent steps.

I’m now applying the same approach to both ground- and space-based high-contrast imaging systems. My current focus is **wavefront sensing and control**, especially for **MagAO-X** 🔧✨, and looking ahead toward modelling challenges on the next generation of ELTs. Most of my work is methods-driven — statistics, algorithms, differentiable modelling, detectors — but the underlying motivation is exoplanet science and pushing high-contrast imaging closer to its physical limits.

📧 **Contact:**  
• louis.desdoigts@leidenuniv.nl  
• louis.desdoigts@sydney.edu.au  
<br clear="left" />

---

## 🧰 Software

I'm an open-source extremist when it comes to software, and most of my projects are aimed at either modelling instruments in a fully differentiable way, or buidling the infrastructure needed to work with these models. These packages are designed for clarity and scientific use rather than hiding complexity.

### [**Zodiax**](https://github.com/LouisDesdoigts/zodiax)
A ƒramework designed to make with building and working with object-orented, scientific models in [JAX](https://github.com/jax-ml/jax) easier by extending [Equinox](https://github.com/patrick-kidger/equinox)

### [**∂Lux**](https://github.com/LouisDesdoigts/dLux)
End-to-end differentiable phsyical optical modelling in JAX, built on Zodiax.

### [**AMIGO**](https://github.com/LouisDesdoigts/amigo)  
Hybrid physical–ML forward model for JWST NIRISS AMI. Models optics, detector physics, electronics, ramp behaviour, and charge-migration effects directly from raw ramps. Built on ∂Lux.

## 📄 Publications (selected)

- *AMIGO: A data-driven calibration of JWST NIRISS AMI* https://arxiv.org/abs/2510.09806
- *Image reconstruction with the AMIGO forward model* https://arxiv.org/abs/2510.10924
- *Differentiable Optics with dLux II: Optical design maximising Fisher information* https://arxiv.org/abs/2406.08704
- *Differentiable Optics with dLux I: Deep calibration of Flat Field and Phase Retrieval with Automatic Differentiation* https://arxiv.org/abs/2406.08703
- *Phase Retrieval and Design with Automatic Differentiation* https://arxiv.org/abs/2107.00952
- *PhD thesis “From Stars to Sensors”* - end-to-end modelling philosophy, hybrid methods, differentiable inference (link coming soon!)
