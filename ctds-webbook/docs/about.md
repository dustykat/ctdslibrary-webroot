# About this document

This website is a collection of worked examples for instructors to illustrate how to incorporate Computational Thinking, Nature Inspired Design, and Social Technical issues into CECE Year 2-4/5 course.

This prototype library is built on a Raspberry Pi 4 (4GB) running Ubuntu 20.XX.
A complete backup is located at [github-url-here]
The actual site is hosted on an AWS Lightsail Instance [fqdn-url-here]

## On-Line Library Author's Notes

- Inserting Code Fragments

To insert a code fragment such as `print('Hello World')` simply indent in the source file used to generate the document

    print('hello world')

Multiple lines

```
Fenced code blocks are like Standard
Markdown’s regular code blocks, except that
they’re not indented and instead rely on
start and end fence lines to delimit the
code block.
```


These fragments can be cut-and-paste into a JupyterLab notebook.

- Inserting Images

If the image is taken from a URL, use the following:

    ![image-name (a local tag)](url_to_image_source)

Such as:

    ![image-name](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqn40YbupkMAzY63jYtA6auEmjRfCOvCd0FA&usqp=CAU)

Which will render a black swan:

![image-name](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQqn40YbupkMAzY63jYtA6auEmjRfCOvCd0FA&usqp=CAU)

If the image is local to the host replace the url with the path to the image.

- Inserting URL links

This is a variation of images, but without the `!`, such as

    [link-name-that-will-display](url_to_link_destimation)
    
For example the code below will link to the black swan search results:

    [link-to-images-of-black-swans](https://www.google.com/search?q=images+of+black+swan&client=safari&rls=en&sxsrf=ALeKk03oIoQ387TWjJoKzX-D_b7o1to43Q:1613002985584&tbm=isch&source=iu&ictx=1&fir=L2P5MiS1ICLTxM%252CC6BDdJoXT9KcEM%252C_&vet=1&usg=AI4_-kTXrBMpj__xL5IkGCshrXTp04fX3w&sa=X&ved=2ahUKEwiCneivyODuAhVJBs0KHY88CaAQ9QF6BAgUEAE&biw=1447&bih=975#imgrc=i_lxoojURNE3XM)

[link-to-images-of-black-swans](https://www.google.com/search?q=images+of+black+swan&client=safari&rls=en&sxsrf=ALeKk03oIoQ387TWjJoKzX-D_b7o1to43Q:1613002985584&tbm=isch&source=iu&ictx=1&fir=L2P5MiS1ICLTxM%252CC6BDdJoXT9KcEM%252C_&vet=1&usg=AI4_-kTXrBMpj__xL5IkGCshrXTp04fX3w&sa=X&ved=2ahUKEwiCneivyODuAhVJBs0KHY88CaAQ9QF6BAgUEAE&biw=1447&bih=975#imgrc=i_lxoojURNE3XM)

- Inserting LaTex-like mathematical typesetting

Lets try ordinary Latex mathematics 

first:

    \begin{equation} 
    F(x) = \int_{-\inf}^{x}{f(\tau)d \tau}
    \end{equation}

\begin{equation} 
F(x) = \int_{-\inf}^{x}{f(\tau)d \tau} 
\end{equation}

then:

    \begin{equation} 
    \delta x
    \end{equation}

Ok, so we don't get the eqn numbering, but we can typeset mathematics!  In-line math is not working just yet $ \Delta x $.
