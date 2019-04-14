# IST Generalized Perspective Projection Dataset

The subjective assessment of the generalized perspective projection (parameterized with projection center d) was conducted using eight omnidirectional images, in equirectangular format, taken from the Salient360! dataset [1]. The spatial resolution of images 2, 6, and 8 is 7500×3750 pixels (8K), and for the remaining ones is 3840×1920 pixels (4K). The selected images have different types of contents, including indoor and outdoor scenes, objects near and far away from the camera, and the presence or absence of people. For each image, the viewports were rendered for three different viewing directions: front view, 45° to the right, and 45° to the left; for each viewing direction, ten viewports were produced, each one corresponding to a pair (d, FoV), with d∈{0,0.25,0.5,0.75,1} and "FoV"∈{90°,110°}. Higher values of d have not been considered, since the amount of distortion (fisheye effect) introduced by these projections is visually annoying to many of viewers. The viewport has a spatial resolution of 856×856 pixels.

The Stimulus Comparison Adjectival Categorical Judgment (SCACJ) was selected as an evaluation method, since it is easier for subjects to select the most pleasant viewport, in a pair of viewports rendered with different projections, than to directly rate the viewports. Since the rectilinear projection (d=0) is typically used for the rendering of 360° images and videos, the resulting viewports were used as reference stimulus. More details about the subjective assessment procedure can be found in [2].


# References

[1]	J. Gutiérrez, E. David, A. Coutrot, M. Perreira Da Silva, P. Le Callet, “Introducing UN Salient360! Benchmark: A platform for evaluating visual attention models for 360 contents”, International Conference on Quality of Multimedia Experience (QoMEX), Sardinia, Italy, May. 2018.

[2] F. Jabar, J. Ascenso and M.P. Queluz, "Objective Assessment of Perceived Geometric Distortions in Viewport Rendering of 360° Images", to be published.
