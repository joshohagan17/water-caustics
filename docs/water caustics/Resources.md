## Approach
- Start with the ray tracing gems chapter as it has the most details and is game engine agnostic.
- Look at the alternative NVidia blog if I need more understanding of the details.
## Real-time ray tracing of caustics (Ray tracing gems 2)
- Book chapter
	- Ray-guided water caustics (page 486)
- NVidia video presentation
	- https://www.nvidia.com/en-us/on-demand/session/gtcspring21-s32968/
	- Slides
		- [[water caustics nvidia ray tracing presentation slides.pdf]]
- Alternative NVidia blog
	- Part 2 - https://developer.nvidia.com/blog/generating-ray-traced-caustic-effects-in-unreal-engine-4-part-2/
- Holger Gruen original presentation
	- https://developer.nvidia.com/video/GDC-19/RAYTRACED_WATER_CAUSTICS_DXR
### Source code
I'll look at the source code if I get stuck, but I won't read all of it before starting my project as there is a lot of it, and probably a lot of Unreal-specific code as well.

[Code repo](https://github.com/NvRTX/UnrealEngine/tree/NvRTX_Caustics-4.26)
- Commits - https://github.com/NvRTX/UnrealEngine/pull/9/commits/b1b2fd8e9caa7f0458aab562d4caffed0d7a1143


## How to render caustics - cg article
https://www.chaos.com/blog/what-are-caustics-and-how-to-render-them-the-right-way?srsltid=AfmBOoqZ-fFJIyxbTlwrsNc_Qz9UtOpol0lhHYVIRcIUazLNXW25sO7O
Gives a good overview of what caustics are in rendering.


# Broader water caustics resources
## Real-Time Underwater Spectral Rendering 2024 - [Nestor Monzon](https://onlinelibrary.wiley.com/authored-by/Monzon/Nestor), [Diego Gutierrez](https://onlinelibrary.wiley.com/authored-by/Gutierrez/Diego), [Derya Akkaynak](https://onlinelibrary.wiley.com/authored-by/Akkaynak/Derya), [Adolfo Muñoz](https://onlinelibrary.wiley.com/authored-by/Mu%C3%B1oz/Adolfo)
- Talks about spectral rendering photo-realistic underwater scenes in real-time
- Might be too difficult for me to implement for all of the details as I don't have access to the source code.
- Although they implemented their technique in the Unity HDRP, I feel that the ray-tracing gems technique applies a lot more to games and integrating caustics into an existing game (it is NVidia as well!)
- I can still grab useful parts of this paper later if I want to.
## Kougianos, Moustakas 2025 paper, based on Gruen
https://www.sciencedirect.com/science/article/pii/S0097849321001230
This paper doesn't seem to do much different to the ray-tracing gems chapter.
## Hybrid caustics, screen space and ray tracing - WANG 2025, thesis
chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://kth.diva-portal.org/smash/get/diva2:1948920/FULLTEXT01.pdf
Does a hybrid approach between screen space and ray-traced, but I want to do just ray-traced for my hobby project.
## Approximating caustics in a traditional renderer - Renou 2020
https://medium.com/@martinRenou/real-time-rendering-of-water-caustics-59cda1d74aa
Doesn't use ray-tracing.
## CPU ray traced caustics - Pregent 2025
https://carleton.scholaris.ca/items/1aaa7215-cf60-478f-a592-3f0c23ca893f/full
Uses offline ray tracing.

