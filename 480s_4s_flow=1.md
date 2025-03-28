The videos were generated using Open-Sora v1.2, with reflow sampling schedule, for which we compared the default 30 uniformly-spaced sampling steps against 23 optimized steps.
The video resolution is 480 x 848. The video length is 4s. Flow is 1.  

<table>
  <tr>
    <td colspan="4">prompt = "A soaring drone footage captures the majestic beauty of a coastal cliff, its red and yellow stratified rock faces rich in color and against the vibrant turquoise of the sea. Seabirds can be seen taking flight around the cliff's precipices. As the drone slowly moves from different angles, the changing sunlight casts shifting shadows that highlight the rugged textures of the cliff and the surrounding calm sea. The water gently laps at the rock base and the greenery that clings to the top of the cliff, and the scene gives a sense of peaceful isolation at the fringes of the ocean. The video captures the essence of pristine natural beauty untouched by human structures."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0000.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0000.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.977477235369163</td>
    <td> 'subject_consistency': 0.9608648056441015</td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.9495619972153465 </td>
    <td> 'background_consistency': 0.9326486115408416 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.9787631876328412 </td>
    <td> 'temporal_flickering':   0.9814909074820725</td>
  </tr>
<tr>
    <td> 'motion_smoothness':   0.9915272949038106</td>
    <td> 'motion_smoothness':  0.9906707866388169</td>
  </tr>
<tr>
    <td> 'dynamic_degree': false  </td>
    <td> 'dynamic_degree': false </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.570270836353302 </td>
    <td> 'aesthetic_quality':   0.533918559551239</td>
  </tr>
<tr>
    <td> 'imaging_quality':  75.73335400749656 </td>
    <td> 'imaging_quality':  74.878360823089 </td>
  </tr>
<table>

<table>
  <tr>
    <td colspan="2">prompt = "A majestic beauty of a waterfall cascading down a cliff into a serene lake. The waterfall, with its powerful flow, is the central focus of the video. The surrounding landscape is lush and green, with trees and foliage adding to the natural beauty of the scene. The camera angle provides a bird's eye view of the waterfall, allowing viewers to appreciate the full height and grandeur of the waterfall. The video is a stunning representation of nature's power and beauty."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0001.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0001.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9413166603829601 </td>
    <td> 'subject_consistency': 0.9740810494611759 </td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.931087078434406</td>
    <td> 'background_consistency':   0.9363228070853961 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering': 0.951684918123133 </td>
    <td> 'temporal_flickering':  0.9729317309809666  </td>
  </tr>
<tr>
    <td> 'motion_smoothness':   0.9654882754372713</td>
    <td> 'motion_smoothness':  0.9867093348568463</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  true </td>
    <td> 'dynamic_degree':  true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.6693254113197327 </td>
    <td> 'aesthetic_quality':  0.7368589043617249</td>
  </tr>
<tr>
    <td> 'imaging_quality':  60.01047949697457 </td>
    <td> 'imaging_quality': 50.560042399986116 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A vibrant scene of a snowy mountain landscape. The sky is filled with a multitude of colorful hot air balloons, each floating at different heights, creating a dynamic and lively atmosphere. The balloons are scattered across the sky, some closer to the viewer, others further away, adding depth to the scene.  Below, the mountainous terrain is blanketed in a thick layer of snow, with a few patches of bare earth visible here and there. The snow-covered mountains provide a stark contrast to the colorful balloons, enhancing the visual appeal of the scene.  In the foreground, a few cars can be seen driving along a winding road that cuts through the mountains. The cars are small compared to the vastness of the landscape, emphasizing the grandeur of the surroundings.  The overall style of the video is a mix of adventure and tranquility, with the hot air balloons adding a touch of whimsy to the otherwise serene mountain landscape. The video is likely shot during the day, as the lighting is bright and even, casting soft shadows on the snow-covered mountains."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0002.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0002.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.974648779276574 </td>
    <td> 'subject_consistency':   0.9711739355974859 </td>
  </tr>
 <tr>
    <td> 'background_consistency':   0.9684333423576733 </td>
    <td> 'background_consistency': 	0.9488319925742574 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.991339833128686   </td>
    <td> 'temporal_flickering':   0.9846093000150195 </td>
  </tr>
<tr>
    <td> 'motion_smoothness': 0.9940313862940354 </td>
    <td> 'motion_smoothness':  0.9917317652454064</td>
  </tr>
<tr>
    <td> 'dynamic_degree': false </td>
    <td> 'dynamic_degree': true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.6682314872741699 </td>
    <td> 'aesthetic_quality':  0.6447694301605225 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  48.00134677512973 </td>
    <td> 'imaging_quality':   57.38184390348547 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "The vibrant beauty of a sunflower field. The sunflowers, with their bright yellow petals and dark brown centers, are in full bloom, creating a stunning contrast against the green leaves and stems. The sunflowers are arranged in neat rows, creating a sense of order and symmetry. The sun is shining brightly, casting a warm glow on the flowers and highlighting their intricate details. The video is shot from a low angle, looking up at the sunflowers, which adds a sense of grandeur and awe to the scene. The sunflowers are the main focus of the video, with no other objects or people present. The video is a celebration of nature's beauty and the simple joy of a sunny day in the countryside.
"</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0003.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0003.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency':  0.9858280033758371 </td>
    <td> 'subject_consistency':  0.989729111737544 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.972213896194307 </td>
    <td> 'background_consistency':  0.9790740060334159 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.99138583575978 </td>
    <td> 'temporal_flickering':  0.9759436046375948  </td>
  </tr>
<tr>
    <td> 'motion_smoothness': 0.9938571343697332 </td>
    <td> 'motion_smoothness':  0.9868746444280019</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false</td>
    <td> 'dynamic_degree':  false</td>
  </tr>
<tr>
    <td> 'aesthetic_quality': 0.5538157224655151 </td>
    <td> 'aesthetic_quality':  0.6216890811920166 </td>
  </tr>
<tr>
    <td> 'imaging_quality':   51.001968271592084 </td>
    <td> 'imaging_quality':   76.33284220975987</td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A serene underwater scene featuring a sea turtle swimming through a coral reef. The turtle, with its greenish-brown shell, is the main focus of the video, swimming gracefully towards the right side of the frame. The coral reef, teeming with life, is visible in the background, providing a vibrant and colorful backdrop to the turtle's journey. Several small fish, darting around the turtle, add a sense of movement and dynamism to the scene. The video is shot from a slightly elevated angle, providing a comprehensive view of the turtle's surroundings. The overall style of the video is calm and peaceful, capturing the beauty and tranquility of the underwater world."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0004.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0004.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':   0.9037679843973405</td>
    <td> 'subject_consistency':  0.8545242527333816 </td>
  </tr>
 <tr>
    <td> 'background_consistency':   0.944045869430693</td>
    <td> 'background_consistency': 0.9308912824876238 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering': 0.9947753312540989 </td>
    <td> 'temporal_flickering':  0.9699030090780819  </td>
  </tr>
<tr>
    <td> 'motion_smoothness':   0.9961490394546183 </td>
    <td> 'motion_smoothness':  0.9843480266267933</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  true </td>
    <td> 'dynamic_degree':  true</td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.5248982906341553 </td>
    <td> 'aesthetic_quality':   0.4264434278011322 </td>
  </tr>
<tr>
    <td> 'imaging_quality':   37.13797264473111 </td>
    <td> 'imaging_quality':  36.93602303897633 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A vibrant underwater scene. A group of blue fish, with yellow fins, are swimming around a coral reef. The coral reef is a mix of brown and green, providing a natural habitat for the fish. The water is a deep blue, indicating a depth of around 30 feet. The fish are swimming in a circular pattern around the coral reef, indicating a sense of motion and activity. The overall scene is a beautiful representation of marine life."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0005.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0005.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency':   0.9333911968929933</td>
    <td> 'subject_consistency':  0.8753280642599163</td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9619986656868812 </td>
    <td> 'background_consistency':  0.9330329517326733 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.98594085001478</td>
    <td> 'temporal_flickering':    0.9543227476232192</td>
  </tr>
<tr>
    <td> 'motion_smoothness':   0.9924528596698113 </td>
    <td> 'motion_smoothness':  0.9738460265985325</td>
  </tr>
<tr>
    <td> 'dynamic_degree': true </td>
    <td> 'dynamic_degree': true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.4234396815299988  </td>
    <td> 'aesthetic_quality': 0.39287248253822327 </td>
  </tr>
<tr>
    <td> 'imaging_quality':  35.74580200045717 </td>
    <td> 'imaging_quality':  37.42278013042375 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A bustling city street at night, filled with the glow of car headlights and the ambient light of streetlights. The scene is a blur of motion, with cars speeding by and pedestrians navigating the crosswalks. The cityscape is a mix of towering buildings and illuminated signs, creating a vibrant and dynamic atmosphere. The perspective of the video is from a high angle, providing a bird's eye view of the street and its surroundings. The overall style of the video is dynamic and energetic, capturing the essence of urban life at night."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0006.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0006.mp4.gif" width=""></td>
  </tr>
 <tr>
    <td> 'subject_consistency':  0.9520735433786223 </td>
    <td> 'subject_consistency': 0.9434781056819576 </td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9475411896658416 </td>
    <td> 'background_consistency':  0.9228273901608911</td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.9851884879317938 </td>
    <td> 'temporal_flickering':    0.9579385458254347</td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9891750738634029 </td>
    <td> 'motion_smoothness':  0.9649650569583179</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  true </td>
    <td> 'dynamic_degree':  true</td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.5679159760475159 </td>
    <td> 'aesthetic_quality': 0.5783047676086426 </td>
  </tr>
<tr>
    <td> 'imaging_quality': 51.90224602643181 </td>
    <td> 'imaging_quality': 42.06966757306866 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A snowy forest landscape with a dirt road running through it. The road is flanked by trees covered in snow, and the ground is also covered in snow. The sun is shining, creating a bright and serene atmosphere. The road appears to be empty, and there are no people or animals visible in the video. The style of the video is a natural landscape shot, with a focus on the beauty of the snowy forest and the peacefulness of the road."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0007.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0007.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9800284693736842 </td>
    <td> 'subject_consistency':  	0.9757907912872805 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.977360187190594 </td>
    <td> 'background_consistency':   0.9272630143873762 </td>
  </tr>
  <tr>
    <td> 'temporal_flickering':  0.9804452578226726    </td>
    <td> 'temporal_flickering': 0.9634274239633598   </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9851895775527192 </td>
    <td> 'motion_smoothness':  0.9794058920515271</td>
  </tr>
<tr>
    <td> 'dynamic_degree':  false </td>
    <td> 'dynamic_degree':  true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.5943377614021301 </td>
    <td> 'aesthetic_quality':   0.5919778943061829</td>
  </tr>
<tr>
    <td> 'imaging_quality': 48.76806842579561 </td>
    <td> 'imaging_quality':  64.51876995610256</td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "The dynamic movement of tall, wispy grasses swaying in the wind. The sky above is filled with clouds, creating a dramatic backdrop. The sunlight pierces through the clouds, casting a warm glow on the scene. The grasses are a mix of green and brown, indicating a change in seasons. The overall style of the video is naturalistic, capturing the beauty of the landscape in a realistic manner. The focus is on the grasses and their movement, with the sky serving as a secondary element. The video does not contain any human or animal elements."</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0008.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0008.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency':  0.9021342606237619 </td>
    <td> 'subject_consistency':  0.8993371967041847</td>
  </tr>
 <tr>
    <td> 'background_consistency':  0.9515078705136139 </td>
    <td> 'background_consistency':  0.9543892133353961 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.9464802386713963 </td>
    <td> 'temporal_flickering':  0.9472533955293543  </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9655242791574177 </td>
    <td> 'motion_smoothness': 0.9656884387075061 </td>
  </tr>
<tr>
    <td> 'dynamic_degree':  true </td>
    <td> 'dynamic_degree': true </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.4847904145717621 </td>
    <td> 'aesthetic_quality': 0.5047061443328857 </td>
  </tr>
<tr>
    <td> 'imaging_quality':    36.956253444447235 </td>
    <td> 'imaging_quality': 38.24103733137542 </td>
  </tr>
</table>


<table>
  <tr>
    <td colspan="2">prompt = "A serene night scene in a forested area. The first frame shows a tranquil lake reflecting the star-filled sky above. The second frame reveals a beautiful sunset, casting a warm glow over the landscape. The third frame showcases the night sky, filled with stars and a vibrant Milky Way galaxy. The video is a time-lapse, capturing the transition from day to night, with the lake and forest serving as a constant backdrop. The style of the video is naturalistic, emphasizing the beauty of the night sky and the peacefulness of the forest.
"</td>
  </tr>
 <tr>
    <td> 30 uniform steps </td>
    <td> 23 optimized steps </td>
  </tr>
  <tr>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_30steps_flow%3D1/sample_0009.mp4.gif" width=""> </td>
    <td><img src="https://github.com/sikunyang/HW-VDM/blob/main/480p_4s_23steps_flow%3D1/sample_0009.mp4.gif" width=""></td>
  </tr>
<tr>
    <td> 'subject_consistency': 0.9550231771894021 </td>
    <td> 'subject_consistency':   0.9809029317728364 </td>
  </tr>
 <tr>
    <td> 'background_consistency': 0.9614523708230198 </td>
    <td> 'background_consistency':  0.982666015625 </td>
  </tr>
    <tr>
    <td> 'temporal_flickering':  0.9972159418405271 </td>
    <td> 'temporal_flickering':   0.9952200894262276 </td>
  </tr>
<tr>
    <td> 'motion_smoothness':  0.9973630758776256 </td>
    <td> 'motion_smoothness':  0.9955775393595594 </td>
  </tr>
<tr>
    <td> 'dynamic_degree': false </td>
    <td> 'dynamic_degree':  false </td>
  </tr>
<tr>
    <td> 'aesthetic_quality':  0.6363657116889954 </td>
    <td> 'aesthetic_quality':   0.6457046866416931</td>
  </tr>
<tr>
    <td> 'imaging_quality':  31.66141315535003 </td>
    <td> 'imaging_quality':   41.528140124152685 </td>
  </tr>
</table>
