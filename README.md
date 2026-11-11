# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE

1. Open Fusion 360, create a new design.
<img width="830" height="627" alt="Screenshot 2026-11-11 204637" src="https://github.com/user-attachments/assets/a583fbcc-f8d7-4521-bbbb-539277177442" />
2. Create a new sketch on XY plane.
3. Draw a vertical centre line through origin and make it a construction line.
<img width="388" height="240" alt="Screenshot 2026-11-11 205255" src="https://github.com/user-attachments/assets/db587a18-f011-4975-8689-282a0368023e" />
4. Draw a horizontal centre line through origin and make it a construction line.
5. Take origin as centre of the whole sketch.
6. Draw a circle of R16 with centre at origin for the centre hole.
<img width="517" height="395" alt="Screenshot 2026-11-11 204552" src="https://github.com/user-attachments/assets/b4809d40-13bc-409a-9db3-84a8741d7b91" />
7. Draw a circle of R32 with centre at origin for the outer ring of centre hub.
8. Draw a circle of R40 with centre at origin as construction circle for outer profile reference.
9. Draw one rectangle of width 6 on the vertical centre line between R16 circle and R32 circle in the upper portion. This forms one spoke.
10. Select the rectangle and apply Circular Pattern.
<img width="375" height="252" alt="Screenshot 2026-11-11 205445" src="https://github.com/user-attachments/assets/f24d2fa5-3817-4a40-a69a-3b2da9611db1" />
11. In Circular Pattern, select centre point as origin, quantity as 6, angle as 360°.
12. Click OK to create 6 spokes at 90° to each other.
13. Trim the portion of R16 circle falling inside the spokes.
<img width="530" height="430" alt="Screenshot 2026-11-11 204601" src="https://github.com/user-attachments/assets/0610420c-9f88-417b-94d3-a8412a052969" />

14. Trim the portion of R32 circle falling inside the spokes.
15. Trim the inner portions of the rectangles to form 4 curved openings in centre hub.
16. click ok
17. Draw a construction point at 50 mm right and 60 mm above origin. This is centre of top right hole.
18. Draw a circle of R15 with this point as centre for top right hole.
19. Draw a construction point at 50 mm right and 60 mm below origin. This is centre of bottom right hole.
20. Draw a circle of R15 with this point as centre for bottom right hole.
21. Draw a construction point on horizontal centre line at 70 mm right from origin. This is centre of middle right hole.
22. Draw a circle of R15 with this point as centre for middle right hole.
23. Draw a circle of R21 with centre as top right hole centre for top right outer lobe.
24. Draw a circle of R21 with centre as middle right hole centre for middle right outer lobe.
25. Draw a circle of R21 with centre as bottom right hole centre for bottom right outer lobe.
26. Draw a tangent arc of R20 between top right R21 lobe and middle right R21 lobe to form concave portion.
<img width="546" height="323" alt="Screenshot 2026-11-11 204608" src="https://github.com/user-attachments/assets/2648e849-9e5e-41d9-8e64-674d5a7eca29" />
27. Draw a tangent arc of R20 between middle right R21 lobe and bottom right R21 lobe to form concave portion.
28. Draw a tangent arc of R40 between bottom right R21 lobe and centre R40 circle to form lower outer profile.
29. Draw a tangent arc of R20 between top right R21 lobe and centre R32 circle to form upper outer profile.
30. Select all geometry on right side - R15 holes, R21 lobes, R20 arcs and R40 arc.
31. Apply Mirror command.
<img width="487" height="417" alt="Screenshot 2026-11-11 204613" src="https://github.com/user-attachments/assets/4f76f8fd-e70d-4ba1-a921-5c47969fe73e" />

32. Select vertical centre line as mirror line.
33. Click OK to create top left, middle left and bottom left holes and lobes on left side.
34. Apply Trim command and trim all inner overlapping portions of R21 lobe circles.
35. Trim inner overlapping portions of R20 arcs and R40 arc.
36. Trim the portion of R40 construction circle falling inside the outer profile.
37. Trim the portion of R32 circle falling outside the outer profile.
38. Check that 6 holes of R15, 1 centre hole of R16 and 4 centre openings are clearly formed.
39. Apply dimensions - 50 mm from vertical centre line to top right hole, 50 mm from vertical centre line to bottom right hole, 60 mm from horizontal centre line to top holes, 60 mm from horizontal centre line to bottom holes, 20 mm from left outer edge to bottom left hole centre.
<img width="562" height="513" alt="Screenshot 2026-11-11 204618" src="https://github.com/user-attachments/assets/66ca77cb-776b-408f-a04e-4b8ebc48e3f2" />

40. Apply radius dimensions - R15 for all 6 outer holes, R21 for all 6 outer lobes, R20 for all concave arcs, R16 for centre hole, R32 for centre ring, R40 for lower outer arc.
41. Verify all centres, arcs and holes are fully constrained.
42. Save the sketch and finish sketch.
 <img width="436" height="421" alt="Screenshot 2026-11-11 210017" src="https://github.com/user-attachments/assets/0b7777e3-feb2-4411-a354-1760815cba87" />
 43.THen click excrude
    <img width="945" height="752" alt="Screenshot 2026-11-11 214354" src="https://github.com/user-attachments/assets/0935ab5c-162e-4766-90b8-a6f0b33ded00" />
    


 ## SKETCH
 ![image](https://user-images.githubusercontent.com/113594316/198233336-dd9f5c19-481b-486a-928a-99c32a732f89.png)

 ## OUTPUT
 <img width="975" height="711" alt="Screenshot 2026-11-11 214306" src="https://github.com/user-attachments/assets/79a879d5-5c43-40f7-b2d3-70654ab5e628" />

 
 
 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
