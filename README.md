# VisualizeWithJulia
The repository contains some of the codes I wrote to create slightly more advanced 
animations of dynamical systems. All the codes are easy to read and modify. Feel free
to use it to enhance it further. If you create something nice, I'd love to see it. 
Email: naveen.maindola95@gmail.com

I was using Julia 1.10 when I wrote these. Please make sure to use julia 1.10 or later.
Else, some compatibility issues may emerge from packages.

Also, all packages are imported in the begin of the files. You can add them if you dont 
already have. Use:

using Pkg;
Pkg.add("Name") # Pkg.add("LaTeXStrings") for example

Also, sprite.zip file contains some HD sample sprites prepared in keynote which you can directly in the code. You can use your own sprites ofcourse. But this code works with NxN size (1500x1500 size sprites). Minor tweaking will require while the attractor rotates to adjust a MxN size sprite. 
