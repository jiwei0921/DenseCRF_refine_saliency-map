# DenseCRF_refine_saliency-map
This is a ready-to-use python file for refine saliency maps using dense CRF. If you want to know more about CRF, you can refer to [here](http://graphics.stanford.edu/projects/drf/).

## Citation 
```
@article{Saliency-Evaluation-Toolbox,
    Author = {Wei Ji},
    Title = {Evaluation Toolbox for Salient Object Detection.},
    Journal = {https://github.com/jiwei0921/Saliency-Evaluation-Toolbox/},
    Year = {2019}
}
```

## Dependencies
***pydensecrf***: This package depends on ***pydensecrf***, available via ``` pip install pydensecrf ```.   
***opencv3***: This package depends on ***cv2***, available via ``` pip install opencv-python ```.    
***numpy***: This package depends on ***numpy***, available via ``` pip install numpy ```.       

## Usage
### Note : Use Python 3
1. put your input (.png) and saliency maps (.png) in images and predictions files, respectively. 
2. set your input_path, sal_path and output_path in densecrf_sal.py.
3. run densecrf_sal.py
4. then, you can see the fine results in the output file.

## Related Citations
1. https://github.com/Andrew-Qibin/dss_crf


