# ChoreoAI

<div align="center">
    <img src="ChoreoAI_Zixuan_Wang/assets/logo.png" width=90% />
</div>

## Background
While the fields of technology and dance have historically not often intersected, recent years have seen the advent of AI-generated choreography using models trained on motion capture of a single dancer. This project will expand the state-of-the-art in this intersectional field by exploring duets featuring pairs of dancers, enabling choreography that features authentic interactions between humans & AI models.

## Task ideas
- Extract pose information from curated videos of dance duets
- Train a GNN and/or Transformer model to analyze this data and generate new duet interaction ideas

## Expected results
- Create a dataset of dynamic point-cloud data corresponding to extracted motion capture poses from videos of dance duets
- Train an AI model that can generate the movements of Dancer #2 conditioned on the inputs of Dancer #1 and/or invent new, physically-plausible duet phrases
- If time permits: Learn key relationships between parts of the body of each dancer that are integral to the dynamics of the duet
- We will collaborate with the original dancers to use the model outputs to inspire new performance material

## Projects
| Contributor | Approach | Repository Link | Blog Post |
|-----------------|-----------------|-----------------|-----------------|
| Luis Zerkowski  | Graph Neural Network  | [Repo Link](https://github.com/humanai-foundation/ChoreoAI/tree/main/ChoreoAI_Duet_ChorAIgraphy_Luis_Zerkowski) | [Blog Post](https://medium.com/@luisvz)
| Zixuan Wang  | Transformer and VAE  | [Repo Link](https://github.com/humanai-foundation/ChoreoAI/tree/main/ChoreoAI_Zixuan_Wang)  | [Blog Post](https://wang-zixuan.github.io/posts/2024/gsoc_2024)






## Getting Started

### Prerequisites
- Python 3.8+
- PyTorch
- NumPy, Matplotlib

### Installation
```bash
git clone https://github.com/humanai-foundation/ChoreoAI.git
cd ChoreoAI
pip install -r requirements.txt
```

## Contributing

We welcome contributions! Please follow these steps:
1. Fork this repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to your branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## GSoC 2026

ChoreoAI is participating in Google Summer of Code 2026 under the 
[HumanAI Foundation](https://humanai.foundation/).
Interested students can find project ideas on the 
[HumanAI GSoC 2026 page](https://humanai.foundation/activities/gsoc2026.html).
```

4. Scroll down, write commit message:
```
Add Getting Started, Contributing, and GSoC sections to README
```
5. Select **"Commit directly to the main branch"** → Click **"Commit changes"**

---

### Step 3 — Open a Pull Request
1. Go back to your forked repo
2. Click **"Contribute"** → **"Open pull request"**
3. Title:
```
Add Getting Started, Contributing, and GSoC 2026 sections to README
```
4. Description:
```
Added missing sections to improve documentation:
- Getting Started with prerequisites and installation steps
- Contributing guidelines for new contributors
- GSoC 2026 section linking to HumanAI project ideas
