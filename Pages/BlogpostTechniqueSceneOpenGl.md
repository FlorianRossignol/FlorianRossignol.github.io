Table of Contents
=============

[3D API OPENGL](#3dopengl)

[GLSL/SHADER](#GLSLSHADER)

[VAO/VBO](#VAO/VBO)

[Light Technique](#LightTechnique)

[Load Model](#Load/Model)

[Load cubemap](#LoadCubemap)

[Final Scene](#Final/Scene)

<a name="headers"/>

## 3d opengl
For my project i need to create an 3d scene using graphical api.

I used Learn open gl to create my 3d scene !

![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/opengl_logo.png)

## GLSLSHADER

Gls is another proggraming language based on c.
Gls content as usefull feature like matrix and vector, i based my shader in opengl.

![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/maxresdefault.jpg)

I create my first triangle in opengl !

![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/Triangle3d.png)
![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/shader.png)

## VAO/VBO

Vao is an object 3d object contain vbo and ebo, if u draw an object
u do to but in in vao.

Example location in shader.

## LightTechnique

I based my light for Phong model

Phong model is based white 3 model of light, ambiant + diffuse + specular.

Ambiant is based whit no light reflect an object,
diffuse is based whit reflect in an object
and specular based on an reflective propreties of n object 

![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/giphy.gif)

## Load/Model

After rendering my object white phong technique for light, i need to load an 3d object /obj
white stb lib i can load whit several function an 3d object dirrectly in my scene!

![](image 3d object)

## LoadCubemap
After loading a model we need to load a cubemap, a cubemap is an texture white 6 faces,
i choose an basic texture map 

![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/Cubemap.png)

## Final/Scene
Lets go to set all toghether white object and model load,

this is the final result !

![](https://FlorianRossignol.github.io/Images/Scene3dOpengl/giphy2.gif)

## Conclusion

- I need to practice more ! now several day and my vacation i go to setup multiple project, beacause 
- I have some show commings in my final scene i dont implement effect and other.
- I implement framebuffer but cant have time to setup some effect/ exemple ssao etc
  i dont have to go in the computer graphic beaucause i dont have the capacitate.
