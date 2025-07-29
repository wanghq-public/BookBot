# BookBot
Official repository for paper "BookBot: A Robotic Manipulation Benchmark for Voice-Driven Book Recognition and Grasping in Cluttered Environments" IROS 2025. 


We develop BookBot, a novel voice-interactive book manipulation pipeline to support cross-environmental, multilingual, and multi-categorical book manipulation. First, we utilize Large Language Models(LLMs) to parse and comprehend ambiguity in user instructions. We further propose an instance segmentation module combined with OCR tool to link language to visual instances. Finally, we introduce a PCA-based manipulation policy to refine the robotic grasp pose, utilizing the principal components of the books' geometry, improving the precision and efficiency of grasping.


## Download the THU-Book Dataset


You can download **THU-Book-Dataset** from [Google Drive](https://drive.google.com/file/d/1mGTs6JEbuz8g1IOKGmzvo6EaXX9RWRxe/view?usp=sharing).
The data directories should like this:

```
THU-Book/
├── train/
│   └── Library/
│   └── DailyLife/
│ 
│── test/
│   └── Library/
│   └── DailyLife/
│ 
│── unlabeled/
│── readme.txt
```



## BibTeX
```
@inproceedings{wang2025book,
  title={BookBot: A Robotic Manipulation Benchmark for Voice-Driven Book Recognition and Grasping in Cluttered Environments},
  author={Wang, Huaqiang and Wang, Yuan and Li, Xiang and Li, Yali and Wang, Shengjin},
  booktitle={2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year={2025},
  organization={IEEE}
}
```



