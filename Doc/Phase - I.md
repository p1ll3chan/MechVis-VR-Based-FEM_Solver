
## Problem Statement

- A user should **feel**:
	- where X, Y, Z are
	- what a vector means
	- what changing coordinates means
	- what angle means in space
---
## Methodology

1)  Create coordinate frame
+ Like X , Y , Z  =>  Red , Blue , Yellow

2)  Apply one-vector visualisation
	- 2-D View
	- Use X and Y input for representing the **vector point (ray)** & Angle (θ) 
	- Formula to apply
		$x=r\cos\theta,\qquad y=r\sin\theta$
	- Change x and y value to observe and plot r and θ and visa versa
	
	-  3-D View
	- ==Work in progress==
	
3)  Coordinate point location in *Cartesian component form*
	- This is where vector space starts becoming intuitive.
	- When we point in the void it should display the location in that format
	- Hint : Pick a point with two figures, it displays the location in that format form it respective origin
	- $v=3i+2j+4k$
	- Meaning:
		- 3 in X
		- 2 in Y
		- 4 in Z

4) Process in producing *Projection*
	- Take vector A and project onto B.
	- That teaches:
		- dot product
		- directionality
		- shadow interpretation
	- Formula
		 $\operatorname{proj}_{\mathbf b}(\mathbf a)=\frac{\mathbf a\cdot\mathbf b}{\lVert\mathbf b\rVert^2}\mathbf b$
			$a=p+r,r⊥b$
	- 
5) Then add angle for understanding **Cartesian angle form**
	- Apply the same formula for focusing builds intuition for α, β, γ.
	- $x=r\cos\theta,\qquad y=r\sin\theta$
	

---
# Your first Unity scene should contain:

### Scene Objects

- Axis_X
- Axis_Y
- Axis_Z
- Vector_A
- Projection line
- Angle arc
- Coordinate labels
---
# Your logic pipeline

Input:

(x,y,z)(x,y,z)(x,y,z)

↓

Magnitude:

∣v∣=x2+y2+z2|v| = \sqrt{x^2+y^2+z^2}∣v∣=x2+y2+z2​

↓

Direction

↓

Projection

↓

Rotation

↓

Transformation matrix

↓

VR later

This is the natural growth.