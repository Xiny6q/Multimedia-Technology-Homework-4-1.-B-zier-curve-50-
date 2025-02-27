Download link :https://programming.engineering/product/multimedia-technology-homework-4-1-bezier-curve-50/

# Multimedia-Technology-Homework-4-1.-B-zier-curve-50-
Multimedia Technology Homework 4 – 1. Bézier curve (50%)
Bézier curve (50%)

You are given 1 raster image (bg.png) and 1 path object (Bézier curve, extracted as points.txt) and a sample script to draw the point and line (problem1.py).


bg.png

Plot cubic Bézier curves(slide 14~17) and point on the bg.png by using 2 different settings, and draw low detail curve in blue and high detail in red.

Low detail curve: t = {0, 0.5, …, 1.0}；High detail curve: t = {0, 0.01, 0.02,

…, 1.0} ,and save the result as 1a.png with 2 curves on bg.png.

Discuss how you implement the Bézier curve and the differences between high and low detail curves.

Scale up the img by 4 and plot it.

I. bg.png is scaled using Nearest-neighbor interpolation.

the coordinates of the curve is scaled before the curve is drawn, also you should use the setting of high detail curve.

3D Models (50%)

Launch the script (problem2.ipynb) to implement the translation and illumination of bunny.obj and a 3D surface respectively. Here, we use plotly, a python graphing library, to help us render 3D graphics.



bunny.obj 3D surface

Shift the center of the bunny to (0, 0, 0) and save the figure as 2a.png. Center is defined as [(max(x) + min(x)) / 2, (max(y) + min(y)) / 2, (max(z) + min(z)) / 2] where x, y, z are the vertices of the object.

Based on (a), implement the rotation matrix to rotate the bunny to face the screen(like the following example). Discuss how you implement the rotation matrix and save the 3D figure as 2b.png.


Based on (b), try to put a cubic under the foot of the bunny and save the result as 2c.png.

Given a surface, try different ambient strength ka, diffuse strength kd, specular strength ks in the following settings:

I. (ka , kd , ks) = (0.1, 0.8, 0.05) and (ka , kd , ks) = (0.9, 0.8, 0.05)

(ka , kd , ks) = (0.8, 0.1, 0.05) and (ka , kd , ks) = (0.8, 0.9, 0.05)

III. (ka , kd , ks) = (0.8, 0.8, 0.2) and (ka , kd , ks) = (0.8, 0.8, 2.0)

Plot the result for each condition with 2 subplots and discuss the difference between each setting. Results are saved as 2d_1.png, 2d_2.png, 2d_3.png respectively. You can refer to the following link for more information.

plotly lighting reference:https://plotly.com/python/reference/#surface-lighting

Reminder

Your code should display and output your results so that we can judge if your code works correctly.

You should provide a README file about your execution instructions.

Please compress your code, input images, result images, report and README in a zip file named HW4_{Student-ID}.zip and upload it to eeclass.

If you encounter any problem, please post your problems/questions on eeclass.

Please follow the file structure below:
