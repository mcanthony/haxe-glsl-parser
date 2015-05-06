#Feature Wishlist

- Parser in js worker
- Validator
- Minifier with DCE,
	examples https://code.google.com/p/glsl-unit/wiki/UsingTheCompiler
- Optimizer
	https://www.opengl.org/wiki/GLSL_Optimizations
	http://stackoverflow.com/questions/10880742/glsl-compiler-optimization-of-redundant-assignments-across-functions
	https://github.com/aras-p/glsl-optimizer/tree/master/src/glsl
- LazyGLSL: 
	- typing prepass (automatically resolve type mismatches where possible (ie 1.0*3))
	- add missing function prototypes
    - default function arguments
    - type inference for function returns and function parameters?
    - functions within functions
    - function reference passing?
    - extra built ins, PI, random() and others
- Complete Eval (currently just constant expressions)