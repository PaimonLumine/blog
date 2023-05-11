# Project 3 - ARigami (1)

Group 2 | MOSS | Yin Jianing, Guo Qixuan, Wong Tsz Yiu, Tung Chuen Yuet, Fu Xiaoyu

---

## Project Description

ARigami is an innovative project that aims to revolutionize the traditional art of origami by incorporating augmented reality (AR) technology. With ARigami, users can learn and master the art of origami through interactive AR instructions and engage in an origami community with user-generated tutorial contents.

ARigami uses computer vision (CV) technology to recognize the correctness of each step, ensuring that the user is following the correct folding instructions. In addition, the app uses AR technology to draw guidelines on top of the paper, allowing users to navigate and fold with ease. This feature provides users with a hands-on experience, allowing them to learn and practice the art of origami at their own pace.

ARigami is an ideal tool for anyone interested in learning or teaching origami, from beginners to advanced users. The app is designed to provide a fun and effective learning experience that is accessible to all. 

## Empathize

[Problem Intro Video, starring Wong Tze Yiu, animated by Guo Qixuan, shot & edited by Tung Chuen Yuet](https://drive.google.com/file/d/1GT7PodoMt13z82xsijouoCAXGVDvtLKV/view)

Problem Intro Video, starring Wong Tze Yiu, animated by Guo Qixuan, shot & edited by Tung Chuen Yuet

### Immerse (Problems)

**Origami** is the art of paper folding, which involves transforming a flat piece of paper into a finished sculpture through various folding techniques. While origami may seem simple, it requires a significant amount of **precision and attention to detail**.

According to research, individuals usually **require 5 to 10 times longer** following origami **video tutorials** than the original video content, and tend to take **even longer time** to complete the task when following **paper instructions**. This could be due to the fact that **video or paper instructions are sometimes unclear**, making it **difficult** for individuals to **follow the steps accurately**. As a result, individuals may need to **carefully inspect each step for correctness**, as an incorrect fold can greatly affect the final result. Additionally, **understanding the three-dimensional aspect of the folding process** from a two-dimensional instruction can be **challenging**. This is especially true for **more complex origami models**, which can be particularly **challenging for beginners and children** to comprehend and follow.

### Observe (Existing Solutions)

There are several existing solutions available in the form of **procedure instruction books** or **instructional videos** in order to help people learn and master origami. 

While these resources can be helpful, they might **not be suitable for beginners or children** as they can **be confusing and difficult to follow**, particularly when it comes to more complex origami designs. Even with step-by-step instructions, it can be **challenging to visualize the folding process**, and small mistakes can quickly lead to frustration and disappointment.

Therefore, there is a need for a **more accessible and user-friendly solution** to teach the art of origami to us, **especially for beginners and children**.

## Interpret

### Need Finding

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled.png)

With the aim of **improving the quality of the learning experience**, we hold the view that **augmented reality (AR) technology** has the potential to be beneficial. Our research, which involved a **survey of 43 individuals**, indicates that the majority of respondents expressed a **positive attitude** towards the use of **AR/VR technology to aid** in the lifelong learning and entertainment aspects of origami.

### Persona

```
**Persona:** Lily Chen

**Age:** 30
**Gender:** Female
**Occupation:** Graphic Designer
**Location:** New York City, NY

**Attributes:**
- Skilled in graphic design software
- Interested in origami, but lacks patience and fine motor skills
- Open to using technology for assistance

**Goals:**
- Learn origami and create intricate designs
- Improve patience and fine motor skills
- Incorporate origami into graphic design projects
- Increase efficiency and productivity in personal projects

**Reasons:**
- Interested in new creative hobbies
- Willing to learn and improve skills
- Sees potential for AR assistance in origami
- Believes technology can increase efficiency and productivity
- Videos often show the origami from a limited angle, which can make it 
  difficult to see necessary folds and creases.
- It can be difficult to pause and rewind videos to find mistakes or missed 
  folds, leading to frustration and mistakes.
- Videos do not allow for interactivity or feedback, limiting the ability to 
  learn and improve.
- Videos may show a single way of creating a design, limiting creativity and 
  personalization.
- Videos may be inaccessible to those with hearing impairments or who speak a 
  different language, limiting access to the skill.
```

```
**Persona:** David

**Age:** 22
**Gender:** Male
**Occupation:** University Student
**Location:** Hong Kong

**Attributes:
-** Enjoys staying at home and playing video games
- Interested in origami as a creative hobby
- Shy and introverted, but wants to pursue romantic relationships
- Believes that origami can be a unique and thoughtful way to impress potential  
  romantic partners

**Goals:**
- Use origami to impress and pursue romantic interests
- Improve creative skills and come up with unique designs
- Increase self-confidence and overcome shyness
- Incorporate origami into personal gifts and gestures

**Reasons:**
- Wants to stand out and make a lasting impression on potential romantic 
  partners
- Believes that origami can showcase creativity and thoughtfulness
- Sees potential for origami to be a meaningful and personal way to express 
  feelings
- Believes that learning origami can be a fun and rewarding hobby that can lead  
  to personal growth.
```

### POV

```
**Need:**
To improve origami skills and create unique designs that showcase creativity 
and thoughtfulness.

**Insight:** 
AR assistance could provide interactive guidance and real-time feedback 
on origami creations, as well as a more immersive and engaging learning 
experience. Online tutorials and social media platforms could provide additional 
resources and opportunities for community engagement.

**Goal:** 
To use AR assistance and online resources to enhance origami skills, create 
impressive designs, and connect with others who share their interest in origami. 
Origami can express feelings and impress potential romantic partners, and act 
as a creative outlet and stress-reliever.
```

## Ideate

### Brainstorm

```json
**VR Property:**
- Unlimited resources
- Spatial
- Immersive and interactive experiences
- Avoiding danger
- High cost

**Skywalker:**
- Visual information overlay
- Location information

**Target User:**
- Children
    - Children's books
    - Puzzle games that develop logical thinking
        - Chess
        - Match-3 games
        - Piano Tiles
        - Mahjong, Texas Hold'em
    - Creative games such as Minecraft
    - Music games and instruments
    - Chemistry experiments with beakers
    - Driving games with bicycles, motorcycles, etc.
    - Zoos
    - Amusement parks, Monopoly
    - Skywalker and other similar experiences
    - Origami
    - Rubik's Cube
```

### Mind Map → **Solution**

![mind map 2.png](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/mind_map_2.png)

Upon conducting candidate interviews, we identified **three major needs and problems** related to learning origami, which we have presented in the form of a mind map.

The **first** challenge is the **difficulty following instructions** presented in video or paper format. Our proposed strategy is to **add a progress bar** in ARigami with the **current step number**, allowing users to easily **move back and forth**.

The **second** obstacle concerns the **difficulty of visualizing the folding process**. To address this issue, we propose utilizing **AR technology to display the instructions** on the paper itself.

The **third** issue involves **uncertainty regarding the accuracy of the result**. We propose using **computer vision to verify the completion** of each step and **provide feedback on the screen by sending a message** indicating progress.

Our **target audience** primarily consists of origami **beginners**, as well as **anyone interested** in learning origami.

### Storyboard

![storyboard.jpeg](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/storyboard.jpeg)

## Prototype

<aside>
<img src="https://www.notion.so/icons/command-line_gray.svg" alt="https://www.notion.so/icons/command-line_gray.svg" width="40px" /> *Visit our GitHub Repo for more detailed code* https://github.com/TeamMoss/ARigami

</aside>

[ARigmai Demo Video, starring Wong Tze Yiu, shot by Tung Chuen Yuet, animated & edited by Guo Qixuan](https://drive.google.com/file/d/1MwtI0DgjBHJ_tUs7AdrR4kgzBAGaKlwm/view)

ARigmai Demo Video, starring Wong Tze Yiu, shot by Tung Chuen Yuet, animated & edited by Guo Qixuan

### ARigami UML

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%201.png)

The workflow can be broken down into 4 main steps: calibration, hands detection, shape matching, and drawing guidelines.

Before getting started, to enhance detection accuracy, the user can calibrate the mask based on light conditions and paper type. If they've calibrated before, they can skip this step.

To ensure precise shape detection, the camera won't match with the shape when hands are detected. Once the shape is detected, the program updates the reference image and draws AR guidelines on the paper.

These steps are repeated until the final step, where an ending animation congratulates the user.

### Calibration

<aside>
<img src="https://www.notion.so/icons/code_gray.svg" alt="https://www.notion.so/icons/code_gray.svg" width="40px" /> [hsvCalibration.py](http://hsvCalibration.py)

</aside>

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%202.png)

We primarily transform the webcam image into the HSV (Hue, Saturation, Value) format, which enables more precise color representation under different lighting environment. By adjusting the values, we can efficiently differentiate between paper, skin, and various other objects within the scene. To further enhance object detection accuracy, we incorporate the Canny edge detection algorithm with a fine-tuned threshold. These parameters are stored in a JSON file for easy access and manipulation. 

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%203.png)

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%204.png)

**Trackbar = [HSV, CANNY, HSV_A, HSV_B]**

1. `HSV`: The HSV of the front of the paper (i.e. white)
2. `CANNY`: Canny Threshold Value
3. `HSV_A`: The HSV of the skin (i.e. hand)
4. `HSV_B`: The HSV of the back of the paper (i.e. pink)

### Shape Match

<aside>
<img src="https://www.notion.so/icons/code_gray.svg" alt="https://www.notion.so/icons/code_gray.svg" width="40px" /> [ShapeDetection.py](http://ShapeDetection.py) & [ShapeMatch.py](http://ShapeMatch.py)

</aside>

After well calibrated, we analyze color, shapes, and vertices, and match these features against reference contours. 

![                        Reference Contour                                                            Webcam View](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%205.png)

                        Reference Contour                                                            Webcam View

Note that the shape does not always lie flat and perfect, our algorithm can accommodate detection from various dimensions, accounting for imperfections in the positioning. For example, in this image, even the bottom of the paper curled up, in a certain range, it is still detected as complete.

### Instruction Step

<aside>
<img src="https://www.notion.so/icons/code_gray.svg" alt="https://www.notion.so/icons/code_gray.svg" width="40px" /> [steps.py](http://steps.py) , [draw.py](http://draw.py) & [confetti_animation.py](http://confetti_animation.py/)

</aside>

![Example:                     Step 1                                                                    Step 2](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%206.png)

Example:                     Step 1                                                                    Step 2

Upon successful matching, guided lines are drawn on top of the paper base on its relative position. The outline and the arrows are located based on the vertices and contour of the origami, it moves and changes with the origmai. Although the steps are hard-coded in the program, users can easily navigate through them using shortcut keys to move forward and backward.

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%207.png)

A reference image will also be shown in a window next to the webcam view, for the users to see the finishing shape of this step. 

When the user successfully completes the origami, a confetti animation will appear on the screen to celebrate the completion. In the future development, we plan to add a button on the completion page to allow users to upload their origami work as 3D animation to the ARigami Community.

 

### ARigami Society

<aside>
📱 *Prototype available at* https://www.figma.com/proto/ynPC2pH1bSHwgiV0Rvhn9x/ARigami-Society?type=design&node-id=1-15&scaling=scale-down&page-id=0%3A1

</aside>

The AR tutorials will be available for users on the platform ARigami Society, which provides a unique and interactive social experience for users to share and learn about the art of origami.

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%208.png)

![Untitled](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled%209.png)

- ARigami is designed to be a community-driven platform, allowing users to create AR origami tutorials. The uploading process includes filming the folding procedure with ARigami app which automatically generate an AR tutorial from users demostration.
- The platform allow users to search , learn as well as giving feedbacks to each origami tutorial. They can leave likes and comments on videos, providing an interactive and engaging experience for everyone involved.

- By pressing the buttom “AR Tutorial”, the user enters the AR instruction interface as implemented in the demo code and video. The platform also features detailed information about each tutorial, including the credits and difficulties of each tutorial. This information is designed to provide users with a complete understanding of the tutorial, allowing them to learn more effectively.

In addition, customized animations are made for the most popular artworks, encouraging users to share their own creations and learn from others. This feature provides users with a fun and engaging way to explore the world of origami, while also encouraging them to improve their skills and share their work with others.

## Verify (Usability Testing)

**Aspects of usability**

- Easy to learn
- Efficient to use
- Subjectively pleasing

**Users**

- Basic knowledge / little experience of origami
- 6 people (3 people per group)

**Task design**

- Randomly assign 6 people into 2 groups.
- Group 1:
    - Task 1: Create an origami boat by watching the tutorial video.
    - Task 2: Create an origami flower by watching the tutorial video.
- Group 2:
    - Task 1: Create an origami boat by using ARigami
    - Task 2: Create an origami flower by using ARigami.

**Evaluation metrics**

- Completion time
- Error steps
- Pleasing ratings

**Data analysis**

|  | User1 | User2 | User3 | Gp1 Arg. | User4 | User5 | User6 | Gp2 Arg. |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Time (boat) | 5.5mins | 2.8mins | 2.1mins | 3.5mins | 1.5mins | 2.4mins | 1.6mins | 1.8mins |
| Error (boat) | 2 | 2 | 1 | 1.7 | 0 | 0 | 0 | 0 |
| Pleasing (Video) | 5 | 5 | 4 | 4.7 | 5 | 5 | 5 | 5 |
| Time (flower) | 27.2mins | 12.5mins | 15.5mins | 18.4mins | 18.3mins | 12.7mins | 16.5mins | 15.8mins |
| Error (flower) | 13 | 17 | 16 | 15.3 | 6 | 4 | 4 | 4.7 |
| Pleasing (flower) | 5 | 4 | 4 | 4.3 | 5 | 5 | 5 | 5 |

**Testing protocols**

- Provide participants with a clear introduction to the AR origami project and the testing process.
- Explain the tasks clearly and ensure that participants understand what is expected of them.
- Observe the participants closely as they complete the tasks and take note of any issues or areas where they are struggling.
- Ask participants to provide feedback on their experience, using open-ended questions to encourage them to provide detailed and honest feedback.
- Record completion time and error rates for each task.
- Ask participants to rate the ease of learning, efficiency of use, ease of remembering, and subjective pleasure of the AR origami project on a scale of 1-5.
- Thank participants for their participation and provide them with any incentives that were promised.

## Personal Contribution & Reflection

## Group Meeting

- 04/27 - 19:00-21:00 - Library LG4 09
    - Create notion workspace
    - Brainstorm
    - Determine our project
    - Divide tasks
- 05/01 - 16:00-18:00 - Library LG1
    - Finish POV
    - Finish mind map
    - Finish storyboard
    - Working on the prototype
    - Start working on the presentation slides
- 05/05 - 19:00-23:00 - Library LC11
    - Working on the prototype
    - Working on the video demo
- 05/06 - 16:00-19:00 - Library LG1
    - Working on the prototype
    - Working on the video demo
    - Working on the usability testing
- 05/07 - 19:00-23:00 - Library LC09
    - Finalize presentation slides
    - Presentation Rehearsal
    
    ![                            *The night before the presentation be like, (in the sport hall), May 7th*](Project%203%20-%20ARigami%20(1)%2024e9026edf82449ea3c7f21529e1a56b/Untitled.jpeg)
    
                                *The night before the presentation be like, (in the sport hall), May 7th*
    

## Documentation

- **Presentation Slide:**
    
    [https://hkustconnect-my.sharepoint.com/:p:/g/personal/jyinai_connect_ust_hk/Eb-vuMz2cPZNuDW4Sp7fwxsBrklj655OH49bX-CzJTn-mQ?e=Jdt2F9](https://hkustconnect-my.sharepoint.com/:p:/g/personal/jyinai_connect_ust_hk/Eb-vuMz2cPZNuDW4Sp7fwxsBrklj655OH49bX-CzJTn-mQ?e=Jdt2F9)
    
- **Video Demo:**
    
    [https://drive.google.com/file/d/1GT7PodoMt13z82xsijouoCAXGVDvtLKV/view](https://drive.google.com/file/d/1GT7PodoMt13z82xsijouoCAXGVDvtLKV/view)
    
    [https://drive.google.com/file/d/1MwtI0DgjBHJ_tUs7AdrR4kgzBAGaKlwm/view](https://drive.google.com/file/d/1MwtI0DgjBHJ_tUs7AdrR4kgzBAGaKlwm/view)
    
- **GitHub Repository:**
    
    [https://github.com/TeamMoss/ARigami](https://github.com/TeamMoss/ARigami)
    
- **Prototype in Figma:**
    
    [https://www.figma.com/proto/ynPC2pH1bSHwgiV0Rvhn9x/ARigami-Society?type=design&node-id=1-15&scaling=scale-down&page-id=0%3A1](https://www.figma.com/proto/ynPC2pH1bSHwgiV0Rvhn9x/ARigami-Society?type=design&node-id=1-15&scaling=scale-down&page-id=0%3A1)