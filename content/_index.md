## Abstract

The course introduces programming primitives for parallel algorithms on GPUs for a wide variety of applications in computer graphics. Various parallel algorithms can be decomposed into programming primitives that share similar patterns. This course focuses on studying these programming primitives and their applicability in computer graphics, specifically in the context of massively parallel processing on GPUs. The course begins by establishing a theoretical foundation, followed by practical examples and real-world applications. We explain two pivotal algorithms: parallel reduction and parallel prefix scan in detail, discussing their variants and different implementations. Afterward, we provide a collection of more advanced techniques and tricks applicable across various domains. At the end of the course, we also briefly discuss code optimization.

## Course Materials
- [Course notes](sa-courses-notes.pdf)
- [Course slides](sa-course-slides.pptx)
- [Sample code](https://github.com/amdadvtech/Orochi/tree/course/Course)

## Course Content

- Introduction
- Parallel reduction and prefix scan
- Programming primitives
- Linear probing
- Radix sort
- Code optimization

## Citation
If you find the course useful, please use the following BibTeX entry for citation:
```
InProceedings{Meister2023,
 author = {Daniel Meister and Atsushi Yoshimura and Chih-Chen Kao},
 title = {GPU Programming Primitives for Computer Graphics},
 booktitle = {ACM SIGGRAPH Asia 2023 Courses},
 series = {SIGGRAPH Asia 2023},
 year = {2023},
 location = {Sydney, Australia},
 publisher = {ACM},
 address = {New York, NY, USA}
}
```

## Presenters

### Daniel Meister
{{<gallery caption-effect="fade" >}}
{{<figure src="crs_114s2-auth2_pic_0.png" class="no-photoswipe">}}
{{</gallery >}}

Daniel Meister is a researcher and software engineer at AMD. Before that, he was a postdoctoral researcher at the University of Tokyo under the mentorship of Prof. Toshiya Hachisuka and Prof. Nobuyuki Umetani. He received a Ph.D. degree advised by Prof. Jiri Bittner at the Czech Technical University in Prague. His research interests include real-time ray tracing, acceleration data structures, global illumination, GPGPU, and machine learning for rendering.

### Atsushi Yoshimura

{{<gallery caption-effect="fade" >}}
{{<figure src="crs_114s2-auth2_pic_1.jpg" class="no-photoswipe">}}
{{</gallery >}}

Atsushi Yoshimura is a software engineer and also a researcher at AMD. His career started as a software engineer in the field of installation and art. Although his bachelor's education was welfare taking advantage of computer science, his current interest is toward computer graphics, especially ray-traced global illumination even including deep-learning-based techniques for graphics. Currently, he develops Radeon ProRender and conducts related research.

### Chih-Chen Kao

{{<gallery caption-effect="fade" >}}
{{<figure src="crs_114s2-auth2_pic_2.jpg" class="no-photoswipe">}}
{{</gallery >}}

Chih-Chen Kao is a researcher and software engineer at AMD. Before that, he has been working on autonomous driving. He received his Ph.D. degree in Computer Science from National Taiwan University, Taipei, Taiwan, in 2017. His research interests include real-time ray tracing, physically based rendering, heterogeneous computing, and deep learning in computer graphics.

<!-- `beautifulhugo` supports content on your front page. Edit `/content/_index.md` to change what appears here. Delete `/content/_index.md` if you don't want any content here. -->

## Contact Us
Please Feel free to ask us any questions. You can send us emails to any of Daniel Meister (daniel.meister@amd.com), Atsushi Yoshimura (atsushi.yoshimura@amd.com), or Kao ChihChen (chihchen.kao@amd.com).

## Advanced Rendering Research Group
{{<figure src="ARR.png" width="500px" class="no-photoswipe" link="https://gpuopen.com/advanced-rendering-research/">}}
The presenters are from [**Advanced Rendering Research Group** (***ARR***)](https://gpuopen.com/advanced-rendering-research/) at [**AMD**](https://www.amd.com/en.html). They are working on research related to graphics and rendering for CPU and GPU architectures. For more details, please refer to our [publications](https://gpuopen.com/learn/publications/).

## Attend the Course at SIGGRAPH Asia 2023
The course will be held [Thursday, 14 at 9:00am-11:00am at Meeting Room C4.6, Level 4 (Convention Centre)](https://asia.siggraph.org/2023/presentation/?id=crs_114&sess=sess107).
We are looking forward to seeing you at [SIGGRAPH Asia 2023](https://asia.siggraph.org/2023/)!

{{<figure src="sa-course-slides.png" width="600px" class="no-photoswipe">}}