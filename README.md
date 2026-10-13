# Fourier Optics for Inference 01 — Fourier Optics for Engineers

How a lens computes a Fourier transform and a 4f system a convolution, in one pass of light: where the Fourier plane is, how the pattern scales with wavelength and why the light must be coherent; spatial light modulators, what a pixelated detector reads, and coherent (balanced) detection; on-chip slab lenses and butterfly meshes, and a photonic link module's signal path, its binary bit planes and the fibre's own spectrum; and the precision and energy bill: ENOB, noise, passes, and the converters around the optics. Every concept has a figure, and every mechanism an animation driven by a tested model.

**22 slides** (00–13 plus 02b, 02c, 07b, 08b–08e and 10b; the original ids are unchanged, so links into the deck still land on the same topics), with a figure on every slide (**28 figures**, several multi-panel), **10 of them stepped animations** (play, pause, step, scrub, speed, reset; paused under reduced motion). The animations and figures are drawn from small model functions (an FFT, paraxial ray transfer, balanced detection, an NRZ low-pass and eye, bit-plane arithmetic), checked by a node test and in the browser. The fixed-band experiment numbers on slide 08e are read at build time from DeMo_Fixed_Band_Experiment at commit b1f62d3.

Topics: 4f system, Convolution theorem, Coherent detection, Photonic link module, Bit planes, ENOB, Conversion energy.

**Live site:** https://brendanjameslynskey.github.io/FOptInf_01_Fourier_Optics_for_Engineers/

Part of the [Fourier Optics for Inference series](https://github.com/BrendanJamesLynskey/LLM_Hub_Fourier_Optics_Inference). Every number comes from [analysis/results.md](https://github.com/BrendanJamesLynskey/LLM_Hub_Fourier_Optics_Inference/blob/main/analysis/results.md), written by [analysis/flop_share.py](https://github.com/BrendanJamesLynskey/LLM_Hub_Fourier_Optics_Inference/blob/main/analysis/flop_share.py); illustrative coefficients are labelled on the slides. Every concept used here is explained, with links, in the [series glossary](https://brendanjameslynskey.github.io/LLM_Hub_Fourier_Optics_Inference/#glossary). Sister series: [LLM Inference Simulators](https://github.com/BrendanJamesLynskey/LLM_Hub_Inference_Simulators), [FHE Accelerator Simulators](https://github.com/BrendanJamesLynskey/FHE_Hub_Accelerator_Simulators).

Licence: CC BY 4.0.
