![Learn the Brain VR Cover Photo](../images/project%20covers/Learn%20the%20Brain%20VR.png)

*Dublin City University | 2019*

## 1. Overview

**Learn the Brain VR** was the short title for my B.Sc. thesis project, officially titled "Learning About the Brain Using Immersive Virtual Reality: Impact on Learning Transfer, Motivation to Learn, Engagement with the Learning Activity, Cognitive Load, and Experience of Presence." This project investigated the effectiveness of virtual reality (VR) as a learning tool by developing a cross-platform interactive environment in Unity.

I programmed C# assemblies for real-time data collection and analysis, integrating a Sustained Attention to Response Task (SART) to measure cognitive load in VR. When COVID-19 struck, I adapted the project for online deployment, implementing a REST API for secure data transfer, allowing the project to continue remotely.


## 2. Motivation:

- **The Future of Experimental Research in Psychology**: I believe the future of psychological experimental research is in virtual environments. These environments offer psychologists and developers complete control over all stimuli, allowing for easy scaling, sharing, replication, and modification to suit diverse experimental needs.

- **Bridging Learning Gaps**: I aimed to address the limitations of traditional learning by leveraging VR as an engaging medium to digitise and deliver knowledge. The flexibility of VR became even more evident during the pandemic, allowing my experimental project to continue online while others were paused.

- **Technological Mastery**: To execute this project, I actively learned Blender, C#, and Unity, which enabled me to create a fully customisable virtual environment from scratch. This skill acquisition was essential to realising the project's full potential, and my own.



## 3. Objectives:

- **Develop a Custom Virtual Environment**: Build an interactive virtual environment using Blender, C#, and Unity to simulate experimental conditions for evaluating key psychological concepts.

- **Advance Psychological Research through VR**: Demonstrate how immersive virtual environments can push psychology forward by evaluating cognitive load, presence, motivation to learn, and learning transfer—key concepts in psychological research.

- **Create and Implement a SART and Learning Transfer Evaluation**: Design a Sustained Attention to Response Task (SART) to assess cognitive load, and deliver multiple-choice questions before and after the experiment to measure learning transfer across visuospatial and declarative knowledge.

- **Design a System to Measure Learner Engagement**: Track user engagement by measuring how much time participants spent on specific brain regions and how many times they revisited those areas.

- **Ensure Ethical and Scientific Rigour**: Navigate ethical challenges and ensure that all aspects of the project meet the standards for psychological experimentation, allowing for safe and impactful research.

- **Explore Presence and Learning Outcomes**: Measure users' subjective experience of presence and its influence on motivation and learning transfer, expanding the understanding of these phenomena in virtual settings.




## 4. Technologies Used

- **Blender:** A free 3D modelling platform used to create the virtual environment, from the floor and ceiling to interactive brain models and the hands used for interaction.
- **Unity:** A powerful game engine used to bring the models to life and create the immersive experience.
- **Visual Studio Code (Community Edition):** A code editor integrated directly with Unity for streamlined development.
- **SPSS:** Statistical software utilised to analyse and interpret the experimental data.
- **SteamVR:** A virtual reality rendering component that interfaced with Unity, offering broad compatibility with various head-mounted display (HMD) systems.



## 5. Challenges & Solutions

- **COVID-19 Impact:** The onset of COVID-19 occurred just one week after my experiment began, posing a significant risk to the project's continuation. Instead of halting the project, I quickly adapted by developing a secure online version, enabling participants to download the project remotely. I implemented features to lock the project after the experiment period ended and set up a system to collect and send data back to my server via a REST API. This sprint was completed and deployed within two weeks, and the project was successfully pushed through ethics approval once more to accommodate these changes.

- **Technical Learning Curve:** Implementing the REST API and configuring the server to securely receive and parse data packets presented a steep learning curve. During this sprint, I learned new development patterns, including the factory pattern, to efficiently manage the data flow. This experience expanded my technical skill set and reinforced my ability to quickly acquire and apply new technologies under tight deadlines.

- **Ethics Approval:** Navigating the ethics approval process was a key challenge, requiring several rounds of revisions to meet the high standards necessary for the project to proceed. Despite this, I remained committed to ensuring the project adhered to all ethical guidelines. This process highlighted my dedication to working through challenging, less exciting aspects of the project to ensure it met the required standards for ethical research.



## 6. Results & Impact

### 6.1. Learning Gain

- **Analysis Method:** A two-way ANOVA was conducted to examine the effects of experimental condition (IVR vs. DVR) and location (lab vs. remote) on participant learning gain, calculated as the percentage difference between pre- and post-tests of declarative knowledge acquisition.
- **Main Finding:** There was no significant interaction between condition and location on learning gain (F(1, 19) = .006, p = 0.938, partial η2 = .000). Additionally, no main effect of condition (F(1, 19) = 0.072, p = .791, partial η2 = .004) or location (F(1, 19) = 3.204, p = .089, partial η2 = .144) was found.
- **Additional Analysis:** A Wilcoxon signed-rank test revealed a significant increase in learning gain for both DVR (85.71%) and IVR (92.5%) groups compared to a baseline of 0%.

![Bar chart of learning gain between conditions when compared to each group's baseline of 0% learning gain](../images/projects/Learn%20the%20Brain%20VR/results/Bar%20chart%20plotting%20learning%20gain%20compared%20between%20the%20two%20conditions.png)
**Figure 1.** Bar chart of learning gain between conditions when compared to each group's baseline of 0% learning gain.

![Clustered bar chart of learning gain between locations and conditions](../images/projects/Learn%20the%20Brain%20VR/results/Clustered%20Bar%20Chart%20of%20Learning%20Gain%20Between%20Groups.png)
**Figure 2.** Clustered bar chart of learning gain between locations and conditions.

---

### 6.2. Presence

- **Analysis Method:** A two-way ANOVA was used to examine the interaction between condition and location on participants' self-reported sense of presence.
- **Main Finding:** There was a significant interaction between condition and location (F(1, 19) = 4.836, p = .040, partial η2 = .203). Lab participants reported significantly higher presence than remote participants, particularly in the IVR condition (33.75-point difference, p = 0.002).

![Clustered bar chart of presence between locations and conditions](../images/projects/Learn%20the%20Brain%20VR/results/Clustered%20bar%20chat%20of%20presence%20between%20groups.png)
**Figure 3.** Clustered bar chart of presence between locations and conditions.

---

### 6.3. Motivation

- **Analysis Method:** A Kruskal-Wallis H test was conducted to compare motivation scores between the IVR and DVR groups.
- **Main Finding:** No significant difference was found between the IVR and DVR groups (χ2(1) = .137, p = .711). However, lab participants reported significantly higher motivation than remote participants (U = .000, p < .001).

![Clustered bar chart of motivation between locations and conditions](../images/projects/Learn%20the%20Brain%20VR/results/Clustered%20bar%20chart%20plotting%20motivation%20by%20group.png)
**Figure 4.** Clustered bar chart of motivation between locations and conditions.

---

### 6.4. Engagement

- **Analysis Method:** A Kruskal-Wallis H test was conducted to compare engagement scores (measured as time spent interacting with the models) between IVR and DVR groups.
- **Main Finding:** There was no significant difference between the groups (χ2(1) = .458, p = .498), but lab participants had significantly higher engagement than remote participants (U = 21.00, p = .018).


![Clustered bar chart of engagement between locations and conditions](../images/projects/Learn%20the%20Brain%20VR/results/Clustered%20bar%20chart%20of%20engagement%20scores%20across%20groups.png)
**Figure 5.** Clustered bar chart of engagement between locations and conditions.

---

### 6.5. Cognitive Load

- **Analysis Method:** A two-way ANOVA was conducted to examine the effects of condition and location on cognitive load, measured using inverse efficiency scores (IES) from the Sustained Attention to Response Task (SART).
- **Main Finding:** No significant interaction or main effect was found for condition or location on cognitive load (p > .05 for all comparisons).

![Clustered bar chart of inverse efficiency scores for cognitive load across locations and conditions](../images/projects/Learn%20the%20Brain%20VR/results/Bar%20chart%20of%20inverse%20efficiency%20scores%20for%20cognitive%20load%20between%20conditions.png)
**Figure 6.** Clustered bar chart of inverse efficiency scores for cognitive load across locations and conditions.

---

### 6.6. Impact & Conclusions

- **Learning Impact:** Although no significant difference in learning gain between IVR and DVR was found, both groups demonstrated meaningful learning improvements. This supports the idea that well-designed virtual environments can facilitate learning.
- **Presence Impact:** The significant difference in presence between lab-based IVR and DVR participants highlights the importance of immersion for user experience, which is crucial for applications beyond research, including training and education.
- **Motivation and Engagement:** Lab-based participants showed higher motivation and engagement, indicating that controlled environments may enhance these factors. However, this also points to potential improvements in remote VR applications, a key insight for future development.
- **Technological & Research Contribution:** This project contributed valuable insights into the use of immersive technologies for educational purposes, especially in psychology. The full stack development aspect of building the VR environment from the ground up, integrating tools like Blender, Unity, and SPSS, demonstrates the importance of multidisciplinary skill sets in both research and development.
- **Future Applications:** The project underscores the potential for immersive technologies to expand research opportunities, remote learning, and even professional training applications. As a full stack developer, these skills in virtual environment creation, data handling, and user experience design are highly transferrable across different domains.
- **Academic Achievement:** This project earned a first-class grade, marking a significant milestone in my academic and professional career. It reflects both the technical challenges overcome and the successful implementation of immersive technology in psychological research.




## Appendix

### Appendix A: Recruitment Poster

![Recruitment Poster for the Project](../images/projects/Learn%20the%20Brain%20VR/Recruitment%20Poster.png)
**Figure 1.** Recruitment poster for the project.

### Appendix B: 3D Modelling Progress Comparison

![Figure depicting 1 year of 3D modelling progress by comparing my brain models](../images/projects/Learn%20the%20Brain%20VR/Brain%20Modelling%201%20Year%20of%20Progress.png)
**Figure 2.** A comparison of brain models created using Blender 1 year apart.

### Appendix C: More Bullet Points
- **Origins of SaikoTechnology**: My GitHub handle is SaikoTechnology, which evolved from PsychoTechnology - the crossroad between Psychology and technology which is where my career in technology was born. The word*"saiko"* (最高) in Japanese means "the best," "supreme," or "awesome." 
- **On Learning Mediums Comparisons:** In hindsight, I believe we could have better distinguished the differences between VR and more traditional learning methods, like PDFs or slideshows. Since interactive desktop virtual environments aren't commonly used for learning, we didn’t observe a significant contrast between desktop VR and immersive VR. My decision not to include a third medium was mainly due to time constraints and the expectation that our sample size wouldn’t be large enough to effectively compare all three.
- **Hand-Drawn Digital Art:** The multiple choice question included hand-drawn digital art which was created using Photoshop and a graphics tablet.