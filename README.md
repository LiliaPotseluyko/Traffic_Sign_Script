# Traffic_Sign_Script
This repository was created to share findings of the research paper about traffic signs 3D reconstruction and automation of road asset inspections. 
# Abstract
This study addresses the critical challenges in the 3D reconstruction of traffic signs for improved inspection and maintenance. Current practices in traffic sign detection, recognition, and localisation are reviewed, highlighting significant research gaps and limitations. We propose a novel approach leveraging mobile mapping data and image-based inspection to enhance the fidelity and detail of 3D traffic sign models for maintenance decision-making. The methodology involves a two-step semi-automated process: initially reducing manual workload during data preparation and performing 3D reconstruction based on extracted features. Our proposed solution integrates with Industry Foundation Classes (IFC) for seamless BIM workflows, providing a robust data model for traffic sign maintenance. Findings demonstrate the effectiveness of our approach in generating detailed, low-polygon models suitable for real-time updates, thus offering a promising direction for future research in procedural mesh generation and automated defect detection.
# Directions
Check YouTube Video for Instructions
Upload Unreal Project
1. place .las test file in the level
2. position the script in the world with any sign point cloud cluster
3. adjust parameters
4. convert sign textures to materials and place in the slots provided in parameters
5. finally tick last box to remove debug boxes, generate normals, lightmaps  and export script parameters to .csv
5. convert dynamic mesh to static