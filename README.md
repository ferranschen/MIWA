## MIWA
This is the official implementation for our paper [MIWA: Mixed-Initiative Web Automation for Better User Control and Confidence](https://tianyi-zhang.github.io/files/uist2023-miwa.pdf), UIST 2023.

### Abstract
In the era of Big Data, web automation is frequently used by data scientists, domain experts, and programmers to complete time-consuming data collection tasks. However, developing web automation scripts requires familiarity with a programming language and HTML, which remains a key learning barrier for non-expert users. We provide MIWA, a mixed-initiative web automation system that enables users to create web automation scripts by demonstrating what content they want from the targeted websites. Compared to existing web automation tools, MIWA helps users better understand a generated script and build trust in it by (1) providing a step-by-step explanation of the script’s behavior with visual correspondence to
the target website, (2) supporting greater autonomy and control over web automation via step-through debugging and fine-grained demonstration refinement, and (3) automatically detecting potential corner cases that are handled improperly by the generated script. We conducted a within-subjects user study with 24 participants and compared MIWA with Rousillon, a state-of-the-art web automation tool. Results showed that, compared to Rousillon, MIWA reduced the task completion time by half while helping participants gain more confidence in the generated script.

## System Architecture
MIWA consists of 3 parts: React UI, Backend System, and Chrome Extension. <br>

![arch](arch.png)
## Files Path
```shell
├── back_end
│   ├── README.md
│   ├── lib
│   ├── node_modules
│   ├── package-lock.json
│   ├── package.json
│   ├── server.js
│   ├── server.js.map
│   ├── server.ts
│   ├── tsconfig.json
│   └── yarn.lock
├── front_end
│   ├── bootstrap-5.0.1-dist
│   ├── css
│   ├── manifest.json
│   ├── node_modules
│   ├── package-lock.json
│   ├── package.json
│   ├── pages
│   ├── readme.md
│   ├── resources
│   ├── scripts
│   └── test.json
└── react_web
    ├── README.md
    ├── build.sh
    ├── node_modules
    ├── package-lock.json
    ├── package.json
    ├── public
    ├── src
    └── yarn.lock
```


## Citation
If you find our work helpful, please cite:
```bibtex
@inproceedings{chen2023miwa,
  title={MIWA: Mixed-Initiative Web Automation for Better User Control and Confidence},
  author={Nguyen, Tai and Di, Yifeng and Lee, Joohan and Chen, Muhao and Zhang, Tianyi},
  booktitle={Proceedings of the 36th Annual ACM Symposium on User Interface Software and Technology},
  year={2023},
  organization={ACM}
}
