# Pix2Gif: Motion-Guided Diffusion for GIF Generation
![teaser_op](https://github.com/hiteshK03/Pix2Gif/assets/45922320/3d8ca72e-b2f3-48fd-a732-574987454fd3)

:grapes: \[[arXiv](https://arxiv.org/abs/2403.04634)\] &nbsp; :orange: \[[Project Page](https://hiteshk03.github.io/Pix2Gif/)\]


[Hitesh Kandala](https://hiteshk03.github.io/)<sup>1</sup>, [Jianfeng Gao](https://www.microsoft.com/en-us/research/people/jfgao/)<sup>2</sup>, [Jianwei Yang](https://jwyang.github.io/)<sup>2</sup>

## Disclaimer 

Pix2Gif is a pure research project. It takes a user-given image and generates a gif following user prompts. It is provided as-is for educational and informational purposes only. The developers and contributors of Pix2Gif do not bear any responsibility for any misuse or damage caused by the project or its derivatives.

### Legal and Ethical Use

**Intellectual Property Rights**: Users of Pix2Gif are responsible for ensuring that the images and videos they process with the software do not infringe on the intellectual property rights of others. It is the user's responsibility to obtain the necessary permissions and rights for any content they use.

**Compliance with Laws**: Users must comply with all applicable laws and regulations in their use of Pix2Gif. This includes laws related to privacy, copyright, and data protection.

**Content Responsibility**: The developers of Pix2Gif do not endorse or condone the creation of illegal or unethical content. Users are solely responsible for the content they create using the model.

<!-- ## Setup
### Set up python virtual environment
```bash
python3.10 -m venv .pix2gif
source .pix2gif/bin/activate
pip install torch==1.11.0+cu113 torchvision==0.12.0+cu113 torchaudio==0.11.0 --extra-index-url https://download.pytorch.org/whl/cu113
pip install -r requirements.txt
bash scripts/download_pretrained_sd.sh
```

## Demo
![github_demo](https://github.com/hiteshK03/Pix2Gif/assets/45922320/e3b1605c-b8e2-4ab7-8329-17d0b611e68b)
This demo takes in an image and a caption and generates a Gif following the input caption. To launch the demo, run:
```bash
python demo.py
```

## Acknowledgement
We build our work on top of [InstructPix2Pix](https://github.com/timothybrooks/instruct-pix2pix) -->

## Citation
```bibtex
@misc{kandala2024pix2gif,
      title={Pix2Gif: Motion-Guided Diffusion for GIF Generation}, 
      author={Hitesh Kandala and Jianfeng Gao and Jianwei Yang},
      year={2024},
      eprint={2403.04634},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
