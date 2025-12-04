# Final Project progess check in  
### Real-Time Water Surface & Caustics Demo  
*(Progress Report)*

---

## **Project Description**

I am working on this final project by myself.  
My goal is to create a small real-time scene with a moving water surface. The water rises and falls over time, shows bright highlights, and changes appearance depending on the viewing angle—similar to a real lake. When viewed from the side, the water becomes more reflective, and when viewed from above, it appears more transparent.  

Under the water, there is a ground plane where I plan to display soft, animated caustic patterns—the shimmering light traces you can see when sunlight shines through water.  

I am building the project using **OpenGL** and **GLSL shaders**. Because it focuses on water animation, reflection, transparency, and caustics, the final output will look completely different from any previous assignment in the course.

---

## **Progress Update**

Right now, the project is about halfway finished.  
I have already set up the main rendering framework and created a subdivided plane to serve as the water surface. The plane moves up and down based on several wave functions, creating simple animated waves.

I added basic lighting as well, so the water surface shows shifting highlights as the waves move.  
I also implemented a simple Fresnel effect: from shallow angles, the water reflects more light, and from a top-down angle, the water looks clearer.

The underwater ground plane is already visible, and I have started working on the animated caustics. The caustics move across the ground, but still need more refinement to look natural.

---

## **Plan for the Next Stage**

Before December 8th, I expect the project to reach near-final quality. My next goals are:
1. Improve surface normal calculations so the highlights look smooth and stable  
2. Refine the caustics pattern and motion  
3. Add preset wave modes such as calm, windy, and storm  
4. Make the camera movement smoother and add preset viewpoints  
5. Adjust lighting and colors to polish the final scene  

---

## **Concerns & Challenges**

Here are the three issues I am most concerned about:
1. **Normal Calculation** — If the normals are not computed well, reflections may flicker or look incorrect.  
2. **Caustics Tuning** — The caustics can easily become too bright or too fast, so balancing them requires experimenting.  
3. **Performance** — A dense water mesh with several wave functions may reduce the frame rate, so I may need to find a balance.



