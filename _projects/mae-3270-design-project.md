---
layout: project
title: MAE 3270 Design Project
description: Advanced CAD Project
technologies: [Autodesk Fusion][MATLAB][Ansys]
image: /assets/images/torque-wrench-cad.jpg
---

For MAE 3270, I was assigned to design a non-ratcheting, 3/8 inch drive instrumental torque wrench rated for 600 in-lbf. The design was required to attain at least an 1 mV/V output at the rated torque of 600 in-lbf, a safety factor of at least 4 for yield or brittle failure, a safety factor of at least 2 for crack growth, and a fatigue stress factor of at least 1.5. The material used must also be a steel, aluminum, or titanium alloy.

![CAD]({{ "/assets/images/mae-3270-design-project/cad.png" | relative_url }}){: .inline-image-r style="width: 200px"}

I iterated the design, modifying the geometry as well as the material, using MATLAB before modeling the  design using Fusion.

![Dimensions]({{ "/assets/images/mae-3270-design-project/dimensions.png" | relative_url }}){: .inline-image-r style="width: 200px"}

I used Ti-6Al-4V (aged) as the material as it has a relatively low Young's modulus, for maximizing the output, and adequate yield strength, fracture toughness, and fatigue strength, for maximizing the safety factors.

![Material properties]({{ "/assets/images/mae-3270-design-project/material-properties.png" | relative_url }}){: .inline-image-r style="width: 200px"}

I created boundary conditions and loaded the torque wrench using Ansys, setting the displacement at the drive to 0 in all directions and applying a force of 37.5 lbf in the Y direction at the end of the torque wrench.

![Boundary conditions]({{ "/assets/images/mae-3270-design-project/boundary-conditions.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Load]({{ "/assets/images/mae-3270-design-project/load.png" | relative_url }}){: .inline-image-r style="width: 200px"}

I modeled the normal strain and maximum principal stress.

![Normal strain]({{ "/assets/images/mae-3270-design-project/normal-strain.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Maximum principal stress]({{ "/assets/images/mae-3270-design-project/maximum-principal-stress.png" | relative_url }}){: .inline-image-r style="width: 200px"}

I also modeled the normal stress, the deformation, and the strain at the strain gauge location.

![Normal stress]({{ "/assets/images/mae-3270-design-project/normal-stress.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Deformation]({{ "/assets/images/mae-3270-design-project/deformation.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Strain gauge location]({{ "/assets/images/mae-3270-design-project/strain-gauge.png" | relative_url }}){: .inline-image-r style="width: 200px"}

The maximum normal stress was 27.958 ksi, the load point deflection was 0.3722 in, and the strain at the strain gauge location was 1084.2 microstrains.

I calculated the torque wrench sensitivity using the strain from the model and obtained 1.0842 mV/V.

I selected