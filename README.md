# Correlation_Filters_py

# References
[Good overview of Correlation Filters and how they began](https://link.springer.com/article/10.1007/s40747-020-00161-4)
[Other correlation Library](https://github.com/fengyang95/pyCFTrackers/tree/master)
[Tracking algorithms in python](https://github.com/visionml/pytracking)

# Implemented Filters

- [ ] [MOSSE](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.4992&rep=rep1&type=pdf)
- [ ] [CSK](http://59.80.44.48/www.robots.ox.ac.uk/~joao/publications/henriques_eccv2012.pdf)
- [ ] [CN](http://117.128.6.12/cache/www.cvl.isy.liu.se/research/objrec/visualtracking/colvistrack/CN_Tracking_CVPR14.pdf?ich_args2=465-31142901008185_f9df5d61efad793a151f3e0f467d3f75_10001002_9c896128d7c2f2d6933d518939a83798_91ccc5b03febd95ae516eb0f69b18b49)
- [ ] [KCF/DCF](http://www.robots.ox.ac.uk/~joao/publications/henriques_tpami2015.pdf)
- [ ] [DSST/DSST-LP](http://www.cvl.isy.liu.se/research/objrec/visualtracking/scalvistrack/ScaleTracking_BMVC14.pdf)  
- [ ] [SAMF](https://link.springer.com/content/pdf/10.1007%2F978-3-319-16181-5_18.pdf)  
- [ ] [Staple](https://arxiv.org/pdf/1512.01355v2.pdf)
- [ ] [Staple-CA](https://ivul.kaust.edu.sa/Documents/Publications/2017/Context-Aware%20Correlation%20Filter%20Tracking.pdf)
- [ ] [BACF](http://openaccess.thecvf.com/content_ICCV_2017/papers/Galoogahi_Learning_Background-Aware_Correlation_ICCV_2017_paper.pdf)  
- [ ] [CSR-DCF/CSR-DCF-LP](https://arxiv.org/pdf/1611.08461v1.pdf)   
- [ ] [DAT](https://www.tugraz.at/institute/icg/research/team-bischof/lrs/downloads/dat/)  This tracker is not based on CF, I re-implement it just for understanding Staple better  
- [ ] [LDES](https://arxiv.org/pdf/1712.05231.pdf)  
- [ ] [MKCFup/MKCFup-LP](http://openaccess.thecvf.com/content_cvpr_2018/papers/Tang_High-Speed_Tracking_With_CVPR_2018_paper.pdf)    
- [ ] [MCCTH](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Multi-Cue_Correlation_Filters_CVPR_2018_paper.pdf)  
- [ ] [STRCF](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Learning_Spatial-Temporal_Regularized_CVPR_2018_paper.pdf)  
- [ ] [ECO/ECO-HC](https://arxiv.org/pdf/1611.09224v1.pdf) from [pyECO](https://github.com/StrangerZhang/pyECO)
- [ ] [OPENCV-CSRDCF](https://github.com/opencv/opencv_contrib)(Note that trackers implemented in opencv get lower score because they will return a success flag and if this flag is False, the bbox will be set to (0,0,0,0))

# Misc
[Old single object traching dataset evaluation code](https://github.com/StrangerZhang/pysot-toolkit)
