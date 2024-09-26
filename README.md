The thesis presented here describes the development of a new method for locating the work coordinate
system (WCS) in 3-axis CNC milling machines using artificial vision, with the goal of improving
the repeatability of the workpiece zero setup process. The process begins with capturing images of pieces
with different geometric shapes placed on the machine’s worktable by the user. A camera mounted
on the top of the machine captures these images, which are then used as input for an algorithm that
processes the captured images, removes noise, performs segmentation, and converts them to binary
format. The algorithm generates the contour profile of the piece to represent dimensional variation
in the two-dimensional space domain. Subsequently, the Fourier transform is applied to analyze the
contour profile in the frequency domain, using Fourier descriptors that mathematically describe the
variation of the contour profile. The frequency spectra generated from the image of the actual piece
are compared with a reference image through a convolution process of signals, resulting in a third
signal that characterizes the variation between each frequency spectrum. Finally, geometric transformations
of translation and/or rotation are applied to determine the adjustment coordinates of the new
work coordinate system based on the detected dimensional variation. These values are entered into
the CNC machine control to execute the G and M code program for each piece to be machined, thus
adjusting the machining to the actual placement on the worktable and improving the repeatability of
the WCS.
