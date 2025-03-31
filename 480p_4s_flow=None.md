The videos were generated using Open-Sora v1.2, with reflow sampling schedule, for which we compared the default 30 uniformly-spaced sampling steps against 22 optimized steps.
The video resolution is 480 x 848. The video length is 4s. Flow is None.  

<table>
  <tr>
    <td colspan="4">prompt = "A soaring drone footage captures the majestic beauty of a coastal cliff, its red and yellow stratified rock faces rich in color and against the vibrant turquoise of the sea. Seabirds can be seen taking flight around the cliff's precipices. As the drone slowly moves from different angles, the changing sunlight casts shifting shadows that highlight the rugged textures of the cliff and the surrounding calm sea. The water gently laps at the rock base and the greenery that clings to the top of the cliff, and the scene gives a sense of peaceful isolation at the fringes of the ocean. The video captures the essence of pristine natural beauty untouched by human structures."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0000.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0000.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.9920608793744946 </td>
    <td> 'subject_consistency': 0.9820787148310406 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.9514087639232673 </td>
    <td> 'background_consistency': 0.9553996171101485 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9942360601774777 </td>
    <td> 'motion_smoothness':  0.9933384512963991</td>
  </tr>
<tr>
    <td> 'dynamic_degree': false  </td>
    <td> 'dynamic_degree': false </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.5573140382766724 </td>
    <td> 'aesthetic_quality':  0.5693199038505554 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  70.39899736292222 </td>
    <td> 'imaging_quality': 74.12417497821883 </td>
  </tr>
<table>

<table>
  <tr>
    <td colspan="2">prompt = "A majestic beauty of a waterfall cascading down a cliff into a serene lake. The waterfall, with its powerful flow, is the central focus of the video. The surrounding landscape is lush and green, with trees and foliage adding to the natural beauty of the scene. The camera angle provides a bird's eye view of the waterfall, allowing viewers to appreciate the full height and grandeur of the waterfall. The video is a stunning representation of nature's power and beauty."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0001.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0001.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9844053337479582 </td>
    <td> 'subject_consistency': 0.9888694805674033 </td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9589892094678217</td>
    <td> 'background_consistency':  0.9710004447710396 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9908184150455256 </td>
    <td> 'motion_smoothness':  0.9826438697871707</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false</td>
    <td> 'dynamic_degree':  true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.6305229663848877 </td>
    <td> 'aesthetic_quality': 0.6635090112686157 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  70.69646394019033 </td>
    <td> 'imaging_quality': 69.18425092510148 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A vibrant scene of a snowy mountain landscape. The sky is filled with a multitude of colorful hot air balloons, each floating at different heights, creating a dynamic and lively atmosphere. The balloons are scattered across the sky, some closer to the viewer, others further away, adding depth to the scene.  Below, the mountainous terrain is blanketed in a thick layer of snow, with a few patches of bare earth visible here and there. The snow-covered mountains provide a stark contrast to the colorful balloons, enhancing the visual appeal of the scene.  In the foreground, a few cars can be seen driving along a winding road that cuts through the mountains. The cars are small compared to the vastness of the landscape, emphasizing the grandeur of the surroundings.  The overall style of the video is a mix of adventure and tranquility, with the hot air balloons adding a touch of whimsy to the otherwise serene mountain landscape. The video is likely shot during the day, as the lighting is bright and even, casting soft shadows on the snow-covered mountains."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0002.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0002.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.987682035653898 </td>
    <td> 'subject_consistency':  0.9924546341494759 </td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9635892056002475 </td>
    <td> 'background_consistency': 	0.9596877900680693 </td>
  </tr>
<tr>
    <td> 'motion_smoothness': 0.9938602972648702 </td>
    <td> 'motion_smoothness': 0.9944292364194106 </td>
  </tr>
<tr>
    <td> 'dynamic_degree': false </td>
    <td> 'dynamic_degree': false </td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.6963335275650024 </td>
    <td> 'aesthetic_quality': 0.731239914894104 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  46.20846303304037 </td>
    <td> 'imaging_quality':  65.5180201436959 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "The vibrant beauty of a sunflower field. The sunflowers, with their bright yellow petals and dark brown centers, are in full bloom, creating a stunning contrast against the green leaves and stems. The sunflowers are arranged in neat rows, creating a sense of order and symmetry. The sun is shining brightly, casting a warm glow on the flowers and highlighting their intricate details. The video is shot from a low angle, looking up at the sunflowers, which adds a sense of grandeur and awe to the scene. The sunflowers are the main focus of the video, with no other objects or people present. The video is a celebration of nature's beauty and the simple joy of a sunny day in the countryside.
"</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0003.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0003.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9924598374579212 </td>
    <td> 'subject_consistency':  0.9920637539707788</td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.9845490408415841 </td>
    <td> 'background_consistency': 0.9878751547029703 </td>
  </tr>
<tr>
    <td> 'motion_smoothness': 0.9960820396961195 </td>
    <td> 'motion_smoothness':  0.9927000199110043</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false</td>
    <td> 'dynamic_degree':  false</td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.5972610712051392 </td>
    <td> 'aesthetic_quality': 0.5984370708465576 </td>
  </tr>
<tr>
    <td> 'imaging_quality':   72.28787366081687 </td>
    <td> 'imaging_quality':  76.96138868144914 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A serene underwater scene featuring a sea turtle swimming through a coral reef. The turtle, with its greenish-brown shell, is the main focus of the video, swimming gracefully towards the right side of the frame. The coral reef, teeming with life, is visible in the background, providing a vibrant and colorful backdrop to the turtle's journey. Several small fish, darting around the turtle, add a sense of movement and dynamism to the scene. The video is shot from a slightly elevated angle, providing a comprehensive view of the turtle's surroundings. The overall style of the video is calm and peaceful, capturing the beauty and tranquility of the underwater world."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0004.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0004.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.9292732049332987 </td>
    <td> 'subject_consistency':  0.9053296446800232</td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9553271000928217 </td>
    <td> 'background_consistency': 0.9546285194925742 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9972397223249887 </td>
    <td> 'motion_smoothness':  0.9874696068154725</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false</td>
    <td> 'dynamic_degree':  true</td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.5284085273742676 </td>
    <td> 'aesthetic_quality':  0.5335869789123535 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  44.90290544547287 </td>
    <td> 'imaging_quality':  42.67089200487324 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A vibrant underwater scene. A group of blue fish, with yellow fins, are swimming around a coral reef. The coral reef is a mix of brown and green, providing a natural habitat for the fish. The water is a deep blue, indicating a depth of around 30 feet. The fish are swimming in a circular pattern around the coral reef, indicating a sense of motion and activity. The overall scene is a beautiful representation of marine life."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0005.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0005.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency':  0.910533811691964 </td>
    <td> 'subject_consistency':  0.894588364917453</td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9432723545792079</td>
    <td> 'background_consistency': 0.9490326229888614 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.99565589185884 </td>
    <td> 'motion_smoothness':  0.9814788653682123</td>
  </tr>
<tr>
    <td> 'dynamic_degree': true </td>
    <td> 'dynamic_degree': true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.45283586859703064 </td>
    <td> 'aesthetic_quality': 0.43133744597435 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  37.50576213761872</td>
    <td> 'imaging_quality': 39.52080311494715 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A bustling city street at night, filled with the glow of car headlights and the ambient light of streetlights. The scene is a blur of motion, with cars speeding by and pedestrians navigating the crosswalks. The cityscape is a mix of towering buildings and illuminated signs, creating a vibrant and dynamic atmosphere. The perspective of the video is from a high angle, providing a bird's eye view of the street and its surroundings. The overall style of the video is dynamic and energetic, capturing the essence of urban life at night."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0006.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0006.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.9548802250918775 </td>
    <td> 'subject_consistency': 0.938259107936727 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.949530573174505 </td>
    <td> 'background_consistency':  0.9325664255878713</td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9669518876274305 </td>
    <td> 'motion_smoothness':  0.9430160631705513</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false</td>
    <td> 'dynamic_degree':  true</td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.5762754678726196 </td>
    <td> 'aesthetic_quality': 0.5683530569076538 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  51.74699906741871 </td>
    <td> 'imaging_quality': 46.693933898327394 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A snowy forest landscape with a dirt road running through it. The road is flanked by trees covered in snow, and the ground is also covered in snow. The sun is shining, creating a bright and serene atmosphere. The road appears to be empty, and there are no people or animals visible in the video. The style of the video is a natural landscape shot, with a focus on the beauty of the snowy forest and the peacefulness of the road."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0007.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0007.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9830722097713168 </td>
    <td> 'subject_consistency':  	0.997665008695999 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.9736835744121287 </td>
    <td> 'background_consistency':  0.9939593324566832 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9902234974256998</td>
    <td> 'motion_smoothness': 0.9945257616922555 </td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false </td>
    <td> 'dynamic_degree':  false </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.5640044212341309 </td>
    <td> 'aesthetic_quality':  0.6308417320251465 </td>
  </tr>
<tr>
    <td> 'imaging_quality': 50.592345593022365 </td>
    <td> 'imaging_quality': 55.87703098970301 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "The dynamic movement of tall, wispy grasses swaying in the wind. The sky above is filled with clouds, creating a dramatic backdrop. The sunlight pierces through the clouds, casting a warm glow on the scene. The grasses are a mix of green and brown, indicating a change in seasons. The overall style of the video is naturalistic, capturing the beauty of the landscape in a realistic manner. The focus is on the grasses and their movement, with the sky serving as a secondary element. The video does not contain any human or animal elements."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0008.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0008.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency':  0.9243165773920493 </td>
    <td> 'subject_consistency':  0.9142468320851279</td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9523297300433168</td>
    <td> 'background_consistency':  0.9584525835396039 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9737508531544169 </td>
    <td> 'motion_smoothness': 0.9696150538110946 </td>
  </tr>
<tr>
    <td> 'dynamic_degree':  true</td>
    <td> 'dynamic_degree': true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.5639747977256775 </td>
    <td> 'aesthetic_quality': 0.5521793961524963 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  50.34590814627853 </td>
    <td> 'imaging_quality': 48.30371841729856 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A serene night scene in a forested area. The first frame shows a tranquil lake reflecting the star-filled sky above. The second frame reveals a beautiful sunset, casting a warm glow over the landscape. The third frame showcases the night sky, filled with stars and a vibrant Milky Way galaxy. The video is a time-lapse, capturing the transition from day to night, with the lake and forest serving as a constant backdrop. The style of the video is naturalistic, emphasizing the beauty of the night sky and the peacefulness of the forest.
"</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 22 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3DNone/sample_0009.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3DNone/sample_0009.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9682016620541564</td>
    <td> 'subject_consistency':  0.9828780783285008 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.9757768989789604 </td>
    <td> 'background_consistency':  0.980647625309406 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9973488844699305 </td>
    <td> 'motion_smoothness':  0.9957079471240803</td>
  </tr>
<tr>
    <td> 'dynamic_degree': false </td>
    <td> 'dynamic_degree':  false </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.6389329433441162 </td>
    <td> 'aesthetic_quality':  0.6392085552215576 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  31.342033236634496 </td>
    <td> 'imaging_quality':  46.88513602462469 </td>
  </tr>
</table>
