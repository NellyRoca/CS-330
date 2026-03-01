# CS-330

Computational Graphics and Visualization
#Final Project Reflection

For this course, I created a fully interactive 3D desktop scene featuring a notebook, pen, and desk lamp. The project demonstrates my ability to design and develop a complete 3D environment using C++ and OpenGL, including object modeling, texturing, lighting, camera movement, and projection control. The repository includes the 3D Scene ZIP folder and the Design Decisions document explaining my implementation choices.

#How do I approach designing software?

When designing software, I start by breaking the problem down into smaller, manageable components. For this project, I first analyzed the 2D reference image and identified the basic shapes that would make up each object. Instead of thinking about the final result all at once, I separated the scene into individual parts: desk, notebook, pen, and lamp. From there, I focused on how those pieces would fit together spatially.

I approach design visually and structurally at the same time. I think about both appearance and underlying organization. Planning object transformations, lighting placement, and camera navigation early made development smoother later on.

#What new design skills has this project helped me craft?

This project strengthened my ability to translate real-world objects into simplified geometric representations. Learning how to approximate complex objects using primitive shapes improved my spatial reasoning and modeling efficiency.

I also developed stronger skills in designing lighting systems. Understanding how a single point light affects surfaces, shadows, and highlights required thinking about depth and realism in a more intentional way.

Another important skill I improved was designing user interaction. Implementing intuitive camera controls forced me to consider how a user experiences and navigates a 3D space.

#What design process did I follow?

My process followed an iterative and layered approach:

Create basic shapes and position them correctly.

Add textures to improve realism.

Implement lighting and refine material properties.

Add camera controls and projection switching.

Refine and test repeatedly.

I built the scene gradually rather than trying to complete everything at once. Each milestone added another layer of complexity, and I refined earlier components as I progressed.

#How could this design approach apply to future work?

This structured, incremental approach can apply to any large programming project. Breaking a complex problem into modular parts reduces errors and improves organization. Iterative development also allows for testing and refinement at each stage, which leads to stronger final results.

In future software or graphics projects, I will continue to prototype core functionality first and then build additional features on top of a stable foundation.

#How do I approach developing programs?

When developing programs, I focus on writing clean, modular code. I avoid placing all logic into one function and instead separate responsibilities into different classes and helper functions.

In this project, I separated scene setup, lighting configuration, shader communication, object rendering, and camera movement into different areas of the program. This made debugging much easier, especially when adjusting lighting or fixing transformation issues.

I also prioritize readability and commenting so that I can quickly understand my own code later.

What new development strategies did I use?

One major strategy I used was iterative debugging. Lighting and camera movement required careful tuning. I frequently tested small adjustments rather than making large changes all at once.

I also improved my understanding of transformation matrices and vector math. Instead of randomly adjusting values, I began thinking more mathematically about how translation, scaling, and rotation interact.

Managing shader uniform variables efficiently was another skill I strengthened, particularly when passing lighting and material properties to the GPU.

#How did iteration factor into development?

Iteration was critical throughout the entire project. The first versions of my objects looked flat because the lighting values were not balanced correctly. Through repeated testing and adjustment of ambient, diffuse, and specular components, I was able to improve depth and realism.

Camera controls also required iteration. Small sensitivity adjustments made a big difference in usability. Each milestone built on previous work, and I refined earlier code multiple times before reaching the final version.

#How has my development approach evolved?

At the beginning of the course, I focused mainly on making the program function. By the end, I paid much more attention to structure, realism, and user experience.

I became more comfortable troubleshooting graphical issues such as flat shading, incorrect light positioning, and projection problems. I also improved at planning before coding, which reduced unnecessary rewrites.

Overall, my coding approach became more methodical and organized as the project progressed.

#How can computer science help me reach my goals?

Computer science provides the foundation for problem-solving, logical thinking, and technical development. Projects like this one strengthen my ability to design systems from concept to completion.

Understanding graphics programming expands my skill set beyond standard application development and opens opportunities in areas like simulation, visualization, gaming, and interactive software.

#How do computational graphics and visualizations support my educational pathway?

Computational graphics deepen my understanding of mathematics, linear algebra, and real-time systems. Concepts like vectors, matrices, lighting models, and projection transformations connect directly to core computer science topics.

This experience strengthens my technical foundation and prepares me for advanced coursework involving graphics engines, simulations, and systems programming.

#How do computational graphics and visualizations support my professional pathway?

From a professional perspective, this project demonstrates my ability to:

Work with C++ and OpenGL

Build interactive 3D applications

Implement lighting and shading models

Organize and modularize complex codebases

Debug visual and performance issues

These skills are valuable in industries such as game development, simulation software, visualization tools, and user interface design. Even outside of graphics-specific roles, the problem-solving and system design skills gained from this project are directly transferable to software engineering positions.


[CS330 Final Project.zip](https://github.com/user-attachments/files/25664681/CS330.Final.Project.zip)

[CS330 Final project reflection.docx](https://github.com/user-attachments/files/25664682/CS330.Final.project.reflection.docx)
