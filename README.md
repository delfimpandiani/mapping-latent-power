# Mapping Latent Power

## A Synthetic Portraiture Feature Taxonomy

This repository accompanies the research project "Mapping the Latent Image: Analyzing Representational Power and Harm in Synthetic Portraits". 
The project is spearheaded by Dr. D.S. Martinez Pandiani at the University of Amsterdam. Collaborators include: Dalila Menhebi, Emily Klein, Lux Voorzanger. 
It provides tools, resources, and data for studying how AI-generated images encode aesthetic, affective, and compositional cues that reflect (colonial) cultural hierarchies and social norms.

### Purpose

Generative image models not only depict subjects, but also encode subtle, **unprompted** visual–affective cues—such as gaze, posture, gesture, and expression—that shape perceptions of vulnerability, desirability, and social hierarchy. This repository provides tools to help researchers systematically investigate these mechanisms, offering reproducible methods for analyzing representational power beyond demographic presence in synthetic imagery. This repository provides tools to help researchers systematically investigate these mechanisms, offering reproducible methods for analyzing **representational power** beyond simple demographic presence in synthetic imagery.

#### The Feature Taxonomy
At the core of this project is a structured framework of 157 visual–affective features identified through our research. These are organized into six macro-themes that define the "latent image": 
1. **Composition:** Number of subjects, angles, and framing.
2. **Atmosphere:** Background, lighting, and filters.
3. **Clothing & Accessories:** Fashion, textiles, and hair.
4. **Expressions:** Facial cues, eyes/gaze, and emotion/affect.
5. **Objects:** Props and attributes.
6. **Body & Hands:** Body types and hand gestures.

<img width="1395" height="1046" alt="visual_feature_taxonomy" src="https://github.com/user-attachments/assets/50f3f9b6-246d-41bf-893b-2cb6f8225801" />

#### Theorized Features
Our work has already highlighted and theoretically grounded eight recurrent features with distinct representational stakes. These serve as key indicators of how power and vulnerability are visually constructed:

| ID | Feature | Definition | Examples |
| :--- | :--- | :--- | :--- |
| **A** | **Averted gaze** | Gaze clearly directed away from the camera/viewer, focused downward or outward.| <img width="317" height="190" alt="Screenshot 2025-12-22 at 18 35 51" src="https://github.com/user-attachments/assets/dd8b7fd2-c464-49a4-ae30-377211b12fc3" /> |
| **B** | **Minimizing body language** | Postures where the subject contracts or shrinks (hunching, inward folding). | <img width="315" height="186" alt="Screenshot 2025-12-22 at 18 35 58" src="https://github.com/user-attachments/assets/f6b3e5d5-e1bc-4d8f-a585-d760475152c7" /> |
| **C** | **Hand sign** | Hands/fingers used as explicit semiotic gestures (e.g., peace, victory, specific symbols). | <img width="318" height="187" alt="Screenshot 2025-12-22 at 18 36 02" src="https://github.com/user-attachments/assets/2f9d68cc-9da9-4f5b-81f1-b3f1d8875bbc" /> |
| **D** | **Hand-to-face poses** | Touching the face with one or both hands (chin resting, cheek holding). |<img width="318" height="162" alt="Screenshot 2025-12-22 at 18 36 05" src="https://github.com/user-attachments/assets/c306a2fa-7e0d-4264-80cb-50bd3eb291e8" /> |
| **E** | **Make-up / Beautification** | Visible cosmetics, stylized lashes, lip gloss, hair smoothing, etc. | <img width="321" height="163" alt="Screenshot 2025-12-22 at 18 36 09" src="https://github.com/user-attachments/assets/6375d5f3-09c9-4934-9769-0f714af94f09" /> |
| **F** | **Revealed skin / Cleavage** | Partial exposure of the upper torso or skin-emphasizing clothing. | <img width="317" height="158" alt="Screenshot 2025-12-22 at 18 36 12" src="https://github.com/user-attachments/assets/688375d8-cfa8-4da7-8468-1090cc05a7be" /> |
| **G** | **Crotch-shot** | Compositional emphasis on the groin or lower torso area. |<img width="314" height="164" alt="Screenshot 2025-12-22 at 18 36 15" src="https://github.com/user-attachments/assets/f4b6736d-6fb6-47f3-9d59-dbe1681582c0" /> |
| **H** | **Adiposity** | Visual emphasis on body size, roundness, or corporeal “excess.” | <img width="314" height="163" alt="Screenshot 2025-12-22 at 18 36 19" src="https://github.com/user-attachments/assets/45035062-7d48-4fb8-b2b7-8820e9a43bdf" />|
---

#### Repository Content
* **`feature_taxonomy_codebook.pdf`**: A comprehensive guide with definitions, annotation notes, and example images for every feature.
* **`feature_taxonomy_codebook.csv`**: A machine-readable version of the taxonomy for easy integration with data science workflows.
* **`starter_python.ipynb`**: a Jupyter notebook with starter python scripts to facilitate the analysis of annotated data, including basic data handling and visualization tools.

### Usage

Researchers can use these tools, under the terms of the license and appropriate citation, to:

- Apply the taxonomy to new datasets of synthetic images.

- Conduct manual or automated annotation of visual–affective features.

- Explore the aesthetic, affective, and compositional dimensions of representational power in generative visual culture.

- Build upon or extend the taxonomy and methodology for further academic research.

### Citation

If you use these resources in your research, please cite:

Martinez Pandiani, D.S., Klein, E., Menhebi, D., Voorzanger, L. (forthcoming, 2026). Mapping the latent image: Analyzing representational power and harm in synthetic portraits. In G. de Seta, A. Knuutila, & M. Pohjonen (Eds.), Synthetic situations: Ethnographic methods for post-artificial worlds. Routledge.

## License

This repository is released under a [CC BY 4.0] license.
