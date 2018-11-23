# PRN
Pairwise Relational Networks

Created by [Bong-Nam Kang](https://sites.google.com/view/bnkang), Yonghyun Kim and [Daijin Kim](http://imlab.postech.ac.kr/members_d.htm) at [POSTECH IM Lab](http://imlab.postech.ac.kr).


### Overview
Existing face recognition using deep neural networks is difficult to know what kind of features are used to discriminate the identities of face images clearly. To investigate the effective features for face recognition, we propose a novel face recognition method, called a pairwise relational network (PRN), that obtains local appearance patches around landmark points on the feature map, and captures the pairwise relation between a pair of local appearance patches. The PRN is trained to capture unique and discriminative pairwise relations among different identities. Because the existence and meaning of pairwise relations should be identity dependent, we add a face identity state feature, which obtains from the long short-term memory (LSTM) units network with the sequential local appearance patches on the feature maps, to the PRN. To further improve accuracy of face recognition, we combined the global appearance representation with the pairwise relational feature. Experimental results on the LFW show that the PRN using only pairwise relations achieved 99.65% accuracy and the PRN using both pairwise relations and face identity state feature achieved 99.76% accuracy. On the YTF, both the PRN using only pairwise relations and the PRN using pairwise relations and the face identity state feature achieved the state-of-the-art (95.7% and 96.3%). The PRN also achieved comparable results to the state-of-the-art for both face verification and face identification tasks on
the IJB-A, and the state-of-the-art on the IJB-B.


### Citation

If you're using this code in a publication, please cite our papers.
```     
  @InProceedings{Kang_2018_ECCV,
    author = {Kang, Bong-Nam and Kim, Yonghyun and Kim, Daijin},
    title = {Pairwise Relational Networks for Face Recognition},
    booktitle = {The European Conference on Computer Vision (ECCV)},
    month = {September},
    year = {2018}
  }
```


### Related Papers

1. Bong-Nam Kang, Yonghyun Kim, Daijin Kim, "Pairwise Relational Networks using Local Appearance Features for Face Recognition,"  R2L Workshop at Neural Information Processing Systems (NIPS 2018), 2018.  [[pdf]](https://arxiv.org/pdf/1811.06405.pdf)  
2. Bong-Nam Kang, Yonghyun Kim, Daijin Kim, "Pairwise Relational Networks for Face Recognition,"  European Conference on Computer Vision, 2018.  [[pdf]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Kang_Pairwise_Relational_Networks_ECCV_2018_paper.pdf)  
3. 강봉남, 김대진, "얼굴 인식을 위한 국부 외관 특징을 사용한 쌍 관계형 네트워크," 2018 한국컴퓨터종합학술대회 (KCC 2018), 2018.  - 우수발표논문 수상

### Code

Available Soon.



### Licence

This software is for research purpose only.

Check LICENSE file for details.


### Acknowledgements

This research was supported by the MSIT, Korea, under the SW Starlab support program (IITP-2017-0-00897), and “ICT Consilience Creative program” (IITP2018-2011-1-00783) supervised by the IITP.

