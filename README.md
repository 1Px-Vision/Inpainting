# Inpainting

Image inpainting is a technique used to fill in missing or damaged parts of images with new content, using data from surrounding areas or external sources. This field can be divided into two broad 
approaches: traditional techniques and deep learning techniques. Traditional methods are great for fixing small missing sections and producing high-quality outcomes. However, they cannot create new, unseen
objects or produce results that make sense within the context of the entire image. On the other hand, deep learning approaches have greatly improved image inpainting by generating contextually appropriate
content and inventing objects not initially present in the image. Despite these advances, deep learning for image inpainting still faces challenges such as handling images of any size or shape,
creating high-resolution textures, and minimizing the computational power and time required for training. Our approach, which combines GAN-UNet architecture, focuses on enhancing the preservation of image
structure edges. We address the optimization challenge using the augmented Lagrangian second-order method and the alternating direction method of multipliers. Numerical tests demonstrate that our
method repairs images more efficiently, preserve greater detail, and outperforms several recent techniques in peak signal-to-noise ratio and structural similarity.

