<p align="left"><img src="logo/horizontal.svg" alt="XCloud" height="120px"></p>

# XCloud (EXplore Cloud)
## Introduction
__XCloud__ is an open-source AI platform which provides common AI services 
(computer vision, NLP, data mining and etc.)
with RESTful APIs. The platform is developed and maintained by [@LucasX](https://github.com/lucasxlu) based on [Django](https://www.djangoproject.com/) and [PyTorch](https://pytorch.org/).

## Features
* [Computer  Vision](./cv)
    * Face Analysis
        - [x] Face  Comparison
        - [x] Facial Beauty Prediction
        - [x] Gender Recognition
        - [x] Race Recognition
        - [x] Age Estimation
        - [x] Facial Expression Recognition
    * Image Recognition
        - [x] Scene Recognition
        - [x] Flower Recognition
        - [x] Pornography Image Recognition
* [NLP](./nlp)
    - [x] Text Similarity Comparison
    - [x] Sentiment Classification for [douban.com](https://www.douban.com/)
    - [x] News Classification
* [Data Mining](./dm)
    - [x] Zhihu Live Quality Evaluation
* Data Services
    - [x] Zhihu Live & Comments
    - [x] Major Hospital Information
    - [x] Primary and Secondary School on [Baidu Baike](https://baike.baidu.com/)
    - [x] Weather History
* [Research](./research)    
    - [x] Age Estimation 
    - [x] Facial Beauty Prediction (ShuffleNet V2 as backbone)
    - [x] NSFW
    
## Deployment
1. create a virtual enviroment named ```pyWeb``` follow [this tutorial](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001432712108300322c61f256c74803b43bfd65c6f8d0d0000)
2. install [Django](https://docs.djangoproject.com/en/2.1/intro/install/) and [PyTorch](https://pytorch.org/)
3. install all dependent libraries: ```pip3 install -r requirements.txt```
4. activate Python Web environment: ```source ~/pyWeb/bin/activate pyWeb```
5. start django server: ```python3 manage.py runserver 0.0.0.0:8001```
6. open your browser and visit welcome page: ```http://www.lucasx.top:8001/cv/index```


## Contributor
* [@LucasX](https://github.com/lucasxlu): system/algorithm/deployment
* [@reallinfo](https://github.com/reallinfo): logo design

## Note
XCloud is **free for researchers**. For commercial use, please email me AT 
**xulu0620@gmail.com** for more details. 

More features will be added in the next future!
For [XCloud in Java](https://github.com/lucasxlu/CVLH.git), please refer to 
[CVLH](https://github.com/lucasxlu/CVLH.git) for more details! 


## Reference
If you find this project useful in your research, please consider citing our
 paper!
 
```
@inproceedings{xu2018crnet,
  title={CRNet: Classification and Regression Neural Network for Facial Beauty Prediction},
  author={Xu, Lu and Xiang, Jinhai and Yuan, Xiaohui},
  booktitle={Pacific Rim Conference on Multimedia},
  pages={661--671},
  year={2018},
  organization={Springer}
}
```

```
@article{xu2018transferring,
  title={Transferring Rich Deep Features for Facial Beauty Prediction},
  author={Xu, Lu and Xiang, Jinhai and Yuan, Xiaohui},
  journal={arXiv preprint arXiv:1803.07253},
  year={2018}
}
```

## License
[MIT](./LICENSE)
