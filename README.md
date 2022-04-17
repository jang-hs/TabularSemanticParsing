Original Repository : https://github.com/salesforce/TabularSemanticParsing   
* * *   
GPU 환경에서 학습한 모델을 CPU 환경에서 불러와서 사용할 수 있도록 `device_cpu_flag`를 추가하였습니다. 예측 환경이 CPU 일 경우 연산에 CPU를 사용하도록 일부 함수를 추가하였습니다. (ops.py)  
pytorch에서 장치간 모델을 불러오는 방법은 이 사이트를 참고하세요. ([PYTORCH에서 다양한 장치 간 모델을 저장하고 불러오기](https://tutorials.pytorch.kr/recipes/recipes/save_load_across_devices.html))   
   
Added `device_cpu_flag` so that the model trained in the GPU environment can be loaded and used in the CPU environment. When the prediction environment is CPU, some functions have been added to use CPU for computation. (ops.py)  
Refer to the site below for how to load a model in pytorch.([SAVING AND LOADING MODELS ACROSS DEVICES IN PYTORCH](https://pytorch.org/tutorials/recipes/recipes/save_load_across_devices.html))