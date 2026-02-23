$
\newcomand{\pdv}[2][]{\frac{\partial #1}{\partial #2}}

z=\sqrt{4-x^2-2y^2}\\
\pdv{z}{x}= -\frac{x}{\sqrt{4-x^2-2y^2}}, \pdv{z}{y}= -\frac{2y}{\sqrt{4-x^2-2y^2}}\\
\eval{\pdv{z}{x}}_{x=1,y=-1}=-1\\
\eval{\pdv{z}{y}}_{x=1,y=-1}=2\\
z-1=-(x-1)+2(y+1)\\
\boxed{z=-x+2y+4}
$