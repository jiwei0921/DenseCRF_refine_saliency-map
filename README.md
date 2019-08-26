# DenseCRF_refine_saliency-map
This is a ready-to-use python file for refine saliency maps using dense CRF. If you want to know more about CRF, you can refer to [here](http://graphics.stanford.edu/projects/drf/).    

## Citation 
```
@article{Saliency-Refinement-DenseCRF,
    Author = {Wei Ji},
    Title = {The application of the DenseCRF for saliency detection.},
    Journal = {https://github.com/jiwei0921/DenseCRF_refine_saliency-map/},
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

### Maybe Bug
1. pydensecrf/densecrf/include/Eigen/Core:22:10: **fatal error: ‘complex’ file not found** 
[#include](https://blog.csdn.net/u011599639/article/details/83934856)    
^~~~~~~~~    
1 warning and 1 error generated.    
**Command**: ``` conda install -c conda-forge pydensecrf ```

## Related Citations
1. https://github.com/Andrew-Qibin/dss_crf


