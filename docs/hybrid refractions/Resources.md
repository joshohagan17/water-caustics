
# Main article
- Hybrid refractions chapter - Ray tracing gems 2 2021 - page 457
# Other hybrid techniques
## Hybrid raytraced shadows and reflections - [Anagnostou](https://interplayoflight.wordpress.com/author/thinkinggamer/) 2019
https://interplayoflight.wordpress.com/2018/07/04/hybrid-raytraced-shadows-and-reflections/
- Good blog
## Hybrid screen-space reflections - [Anagnostou](https://interplayoflight.wordpress.com/author/thinkinggamer/) 2019
https://interplayoflight.wordpress.com/2019/09/07/hybrid-screen-space-reflections/
- Good blog.
## EA SEED hybrid ray tracing - 2019
chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://link.springer.com/content/pdf/10.1007/978-1-4842-4427-2_25.pdf
- Good paper.
## [Adventures in Hybrid Rendering](https://diharaw.github.io/post/adventures_in_hybrid_rendering/) - Wijetunga 2021
https://diharaw.github.io/post/adventures_in_hybrid_rendering/
- Has a lot about sampling and filtering as well.
# Code
Picking a popular framework doesn't matter much as any of these frameworks are very easy to quickly learn and start writing code in. Just use the code that suits you best to make your hobby project.
## Decision
1. Try out Falcor python.
2. If that doesn't work, try out AMD hybrid reflections sample.
## NVidia Falcor
https://github.com/NVIDIAGameWorks/Falcor
- Real-time rendering framework supporting ray-tracing
- Has 500 forks
- Has Python for quick prototyping!
- Actively maintained through github commits
- Hello DXR sample
	- https://github.com/NVIDIAGameWorks/Falcor/tree/master/Source/Samples/HelloDXR
- Setup guide (written by a thirdparty)
	- https://bipul-mohanto.github.io/posts/2024/08/NVIDIAFalcorForBiggnersSeries/
## NVidia Donut
https://github.com/NVIDIA-RTX/Donut
- Real-time rendering framework with ray-tracing support
- Actively maintained through github commits
- I can't find any videos or tutorials on it, making me think that it's not as popular as Falcor.
## NVidia RTXPT
https://github.com/NVIDIA-RTX/RTXPT
- A code sample derived from Falcor
- The sample is all in one file unfortunately, which makes it a bit harder to use.
## AMD hybrid reflections (FidelityFX code)
https://github.com/GPUOpen-LibrariesAndSDKs/FidelityFX-SDK/blob/main/docs/samples/hybrid-reflections.md
## AMD stochastic screen space reflections (SSSR) (FidelityFX code)
https://github.com/GPUOpen-LibrariesAndSDKs/FidelityFX-SDK/blob/main/docs/samples/stochastic-screen-space-refle