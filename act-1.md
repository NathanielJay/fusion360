---
layout: default
title: 1-Getting Started
nav_order: 2
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

<img src="images/act-1/1.png" alt="3d orientation" style="float:right;width:180px;margin-left:10px;">

# **Getting Started with Fusion 360**

Fusion 360 has A LOT of features. Here’s a quick guide of tools and features to help get you started on your first project!

1.  Moving around
    -   **Hold down** the **mouse wheel** and **drag** to **move.**
    <img src="images/act-1/1-2.png" alt="snap to grid" style="float:right;width:180px;margin-left:10px;">
    -   **Press** the **shift key** while **holding down** the **mouse wheel** to **rotate.**
    -   **Scroll** the **mouse wheel** to **zoom** in and out.
    -   **Click** to **select.**

2.  Changing the view of your workspace
    -   In the top right corner of the workspace there is a cube. **Click** on different faces, edges, or corners to quickly see your design from different angles.
    -   At the bottom of the screen there’s a toolbar. **Click** the **Grids and Snaps** icon to change these features.

    <img src="images/act-1/3-2b.PNG" alt="not fully defined sketch" style="float:right;width:260px;margin-left:10px;">

3.  Sketch dimensioning
    -   Sketch lines will show up as blue or black, depending on how they’re dimensioned. Black lines are fully defined, meaning the line’s length and position has been completely described by dimensions. Blue lines are under-defined, meaning at least one dimension is missing. It’s best to have fully defined lines because they are controlled and cannot be accidentally moved.
    <img src="images/act-1/3b.PNG" alt="trimmed sketch" style="float:right;width:260px;margin-left:10px;">
    -   Dimension sketches such that they’re easy to read. They will likely need to be edited later.
    -   The **Trim** tool <img src="images/act-1/3-3.png" alt="" style="width:25px;"> can be used to remove excess sketch lines. This keeps the sketch clean and makes extruding or revolving it easier.

4.  Common features
    -   **Extrude** <img src="images/act-1/4.png" alt="extrude icon" style="width:25px;"> is used for moving a sketch in a straight line to create a 3D feature.
    -   **Revolve** <img src="images/act-1/4-2.png" alt="revolve icon" style="width:25px;"> is used for rotating a sketch around an axis to create a 3D feature. Make round parts using a revolve instead of a series of extrudes. Then you only need to edit one sketch.
    -   **Hole** <img src="images/act-1/4-3.png" alt="hole icon" style="width:25px;"> is a quick way to make several of the same hole type such as a clearance or threaded hole for a screw.
    -   **Fillet/Chamfer** <img src="images/act-1/4-4.png" alt="fillet icon" style="width:25px;"> <img src="images/act-1/4-5.png" alt="chamfer icon" style="width:25px;"> are tools used to modify the edges of a part. These features should only be used at the very end of designing a part. Otherwise, the wrong edges may be selected for dimensioning or errors may be caused.

    <img src="images/act-1/5.png" alt="measure tool" style="float:right;width:120px;margin-left:10px;">

5.  Measuring
    -   The Measure tool lets you quickly view a dimension without going into a sketch. Above the **Inspect** menu, click on the **Measure** <img src="images/act-1/5-2.png" alt="measure tool" style="width:30px;"> tool.
    -   **Click** on a surface, edge, or point. Geometric properties relating to that feature will appear.
    -   **Click** on a second surface, edge, or point. The distances between the two features will appear.

6.  Cross-section view
    <img src="images/act-1/6.png" alt="section analysis" style="float:right;width:180px;margin-left:10px;">
    <img src="images/act-1/5-3.png" alt="cross section view" style="float:right;width:120px;margin-left:10px;">
    -   Viewing an object through the middle can be useful (e.g. in activity 5, we will make interlocking parts). Viewing a cross-section is useful to ensure there is no interference between features.
    -   **Click** on the **Inspect** drop-down menu. Click on **Section Analysis. Click** on a plane that is parallel to the plane you want to view your object, then drag the cross-section plane to the area you want. Click **OK**.
    <img src="images/act-1/6-3.png" alt="analysis drop down" style="float:right;width:200px;margin-left:10px;">
    -   To turn the feature on and off, find the **Analysis** folder in the top left **Browser**. Click the eye next to the **Section** to turn its visibility on or off.

7.  Renaming features
    -   The design **Timeline** is at the bottom left of your screen and shows all changes made to your design.  It can quickly get messy, especially when designing parts with a lot of features. Renaming features helps to remind you of the feature’s purpose.
    <img src="images/act-1/6-2.png" alt="design timeline" style="float:right;width:240px;margin-left:10px;">
    -   **Right-click** on a feature, then click **Rename**. Type an appropriate name and hit the **Enter** key.
    -   Now when you hover your mouse over the feature in the **Timeline**, you will be able to see your custom name.

    <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/act-1/renaming.gif" alt="renaming" style="width:400px;margin-left:10px;">
    </div>

8.  Editing features
    -   A feature or sketch can be edited by **right-clicking** on it from the **Timeline**, then clicking **Edit Feature** or **Edit Sketch**. Dimensions and other parameters can then be changed.
    <img src="images/act-1/8.png" alt="lego brick top" style="float:right;width:240px;margin-left:10px;">
    -   After you make a part, you will almost certainly need to go back and edit various aspects of it. Often, editing time will exceed initial designing time. Consider the following questions when doing the initial design:
        -   What dimensions are the most likely to be modified?
        <img src="images/act-1/8-2.png" alt="lego brick bottom" style="float:right;width:240px;margin-left:10px;">
        -   If the outer dimensions of the part change, how do I want the other features to move with respect to the body?
        -   How should I setup a feature such that it changes (or doesn’t) when other features change? (e.g. in the Lego activity, it only takes one edit to change the Lego into a “short” Lego because one extrude depends on the length of another extrude).
    -   Sketches and features can be inserted into the middle of the **Timeline** by **dragging** this icon <img src="images/act-1/8-3.png" alt="timeline icon" style="width:20px;"> backwards (left) in the **Timeline**. Continue with sketching and feature creation as usual. Then move it back to the end of the **Timeline**. This is desirable when the part has been “finished” with fillets and chamfers but it turns out another feature needs to be added.
    
    <button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/act-1/timeline.gif" alt="using the timeline" style="width:240px;margin-left:10px;">
    </div>

<script>  

    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Design a Phone Stand](act-2.html){: .btn .btn-blue }
