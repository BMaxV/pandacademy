From (nearly) zero to knowing what rendering and shaders are all abouta
======================================================================

These courses assume that you...
* understand basic Python (you don't need to know the whole standard
  library by heart, but sentences like "So we'll import a class from 
  this module, instantiate an object from it, and call these methods"
  should not scare you any more)
* can `pip install panda3d` (preferably in a virtualenv, but it's your
  system...)
* can verify that your system is running OpenGL 4.30 or higher (e.g. by
  running `glxinfo`)
* are not afraid of math. Computer graphics is one of the purest
  expressions of computing being mathematics in motion, so a basic
  fluency in several fields of math will be necessary to get anywhere
  with anything. For a start though, we will mostly get away with `sin`,
  `cos`, and multiplying a matrix with a vector.

These courses are also nowhere near complete yet. The planned curriculum
is:
- [X] [Hello Panda3D](hello_panda3d/hello_panda3d.md): Getting the basics out of the way.
- [ ] [Panda3D GraphicsEngine et al deep dive](cpu_rendering/cpu_rendering.md)
- [X] [Procedural modeling and animation](geometric_modeling.md) (TODO: lacks shapekeys)
- [ ] Rendering and shaders (needs refactoring and comments)
- [ ] A ShowBase-less Hello World to explain what is going on on top of
      all the rendering stuff