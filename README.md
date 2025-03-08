# Comparing Pixel and Perceptual Loss for a Novel Video Super-Resolution Method

With the ongoing need for high-fidelity videos in different areas of entertainment, Video
Super-Resolution (VSR) has become a pivotal area of research, transcending its roots in
gaming to broader applications such as medical imaging and surveillance.

Despite the simplicity of the model and inherent limitations of the VSR task, our findings illustrate that the perceptual losstrained model produces more visually coherent images than its MSE counterpart, even
though traditional metrics like Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity
Index Measure (SSIM) showed similar or slightly better values for the MSE model. 

## Setting Up the Environment

1. Clone the git repository to your machine (makes a copy).

2. To set up the project environment, make sure you have Anaconda/Conda [installed](https://www.anaconda.com/download), then open the command prompt on your machine.

3. Use the ```cd``` command in the command prompt to navigate to where you cloned the repository (where the files for the project are located on your computer).

4. Type the following into the command prompt, one at a time:

```bash
>>> conda env create -f environment.yml
>>> conda activate pytorch_vsr
```

5. Now, when working on the project, you'll have an environment that is exactly the same as mine, meaning all the packages are exactly the same.
If you restart your computer and ever see that the environment is `base`, then make sure to re-type into the command prompt the 2nd line from above.

6. When working on the project, I would suggest using PyCharm (students get premium for free) or Visual Studio Code. When running code, it will prompt
you to choose an interpreter/kernel, and you can choose the `pytorch_ldm_vsr` python environment, which will make sure it's running code with the specific
versions specified for the project.
