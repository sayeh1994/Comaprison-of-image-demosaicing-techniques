# Comaprison-of-image-demosaicing-techniques
This project is an in-depth look at 4 different image demosaicing techniques.

**Image Demosaicing:** A demosaicing (also de-mosaicing, demosaicking or debayering) algorithm is a digital image process used to reconstruct a full color image from the incomplete color samples output from an image sensor overlaid with a color filter array (CFA). It is also known as CFA interpolation or color reconstruction [[Wikipedia](https://en.wikipedia.org/wiki/Demosaicing)]. 

>> Outline
>>
>> 1.   Mosaicing
>> 2.   Demosaicing - Bilinear
>> 3.   Demosaicing - Malvar, He, and Cutler (2004)
>> 4.   Demosaicing - Menon (2007)
>> 5.   Deep Joint Design of Color Filter Arrays and Demosaicing
>> 6.   Comparion and Discussion

The state-of-the-arts were implemented using the [colour-demosaicing library](https://github.com/colour-science/colour-demosaicing.git). And the Deep Joint Design of Color Filter Arrays and Demosaicing was implemented by using the author's [GitHub code](https://github.com/bernardohenz/deep_joint_design_cfa_demosaicing.git).

## References

1.   https://wiki.apertus.org/index.php/OpenCine.Nearest_Neighbor_and_Bilinear_Interpolation
2.   Ali Pourramezan Fard, Image Demosaicing: Bilinear Interpolation VS High-Quality Linear Interpolation, Oct (2020).
3.   Pascal Getreuer, Malvar-He-Cutler Linear Image Demosaicking, Image Processing On Line, 1 (2011), pp. 83–89. https://doi.org/10.5201/ipol.2011.g_mhcd
4.   Menon, D., Andriani, S., & Calvagno, G. (2007). Demosaicing With Directional Filtering and a posteriori Decision. IEEE Transactions on Image Processing, 16, 132-141.
5.   Henz, B., Gastal, E.S., & Neto, M.M. (2018). Deep Joint Design of Color Filter Arrays and Demosaicing. Computer Graphics Forum, 37.
