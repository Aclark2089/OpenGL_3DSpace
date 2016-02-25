# OpenGL Project - 3D w/ Z Axis
__Authored By: R. Alex Clark__

### Task 3
>Could one rearrange their control points so that the curves form an exact circle (possibly in the limit for task 1)?

These curves are just approximations, there is no way for them to exactly fit a circle. We can increase the number of control points so that our approximation is very high. However, bezier curves can never perfectly fit a circle unless we are using an infinite number of points because of the approximating we do for the positions of c2 and c3, the control points between c1 and c4. The endpoints c1 and c4 coincide with the arc of the circle, but there will always be some distance between the circle's position and the bezier curve segment's tangent approximated points c2 and c3 that we calculated.
