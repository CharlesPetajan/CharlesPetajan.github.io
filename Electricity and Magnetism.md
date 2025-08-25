---
title: Electricity and Magnetism
layout: default
---

# Coulomb

This one is easy. The force of repulsion between two point charges is proportional to both point charges and square-inversely proportional to the distance between them.

$$ 
F_{Coulomb} = k \frac{q_{1} q_{2}}{R^2}
$$

where k is a constant that depends on units. This law is more useful that forces between point charges, since we can either approximate small sections of voluminous charges as points for numerical computation, or we can integrate over infinitesimal point charges across voluminous charges for a pen and paper analysis.

# Gauss

This law requires good set up to create the symmetry necessary for useful results. The idea is that the integral of the electric field over a closed, 3D surface will be proportional to the charge enclosed in the 3D surface.

Integral Form

$$
\oint_{\partial V} \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{\text{enc}}}{\varepsilon_0}
$$

Differential Form

$$
\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}
$$

Note that we only consider the component of the electric field normal to the surface element. The integral here is a neat "reason" for Coulomb's inverse square relationship, because the area of a sphere is proportional to its radius squared, so the electric field at a point from a point charge is equal to the supposed point charge in the middle of the sphere an imaginary sphere with an edge touching our point divided by the area of the sphere.

![](/images/inverse_square.png)

Getting back to the "set up" comment, not every charge is a point and not every surface we make will be sphereical. In other words, the electric field may be dependendent on *where* you are on the surface. In this case, we must either use different methods or be extra clevor about our shape we draw in our system. An example that comes to mind is the study of a infinite, parallel planes of charge, where we can use a cylinder whose axis is normal to the plane. The side of the cylinder will only have electric field parallel to them, so we can just consider the ends of the cylinder, over which the electric field is uniform!

![](/images/plane_of_charge.png)

# Ampere

# Biot-Savart

# Faraday

# More!
