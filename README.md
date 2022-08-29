# PySceneDetect
Extract images that can be used as thumbnails from videos
pyscene을 사용하여 동영상 내 썸네일로 사용할 만한 사진을 추출해보았다. 

### 사용한 동영상
정육왕님의 89.8%가 잘 모르는 수육 레전드 부위<br>
https://www.youtube.com/watch?v=ArsvoA9_Tgw

### 추출 결과
실제 썸네일로 사용한 것과 유사한 장면이 추출되기도 함<br>

추출한 이미지<br>
![898가 잘 모르는 수육 레전드 부위_1080p-Scene-201-02](https://user-images.githubusercontent.com/86832485/187139264-4e4dbdbf-7031-4fb3-961d-8a6fb6ebd03f.jpg)

실제 썸네일<br>
![image](https://user-images.githubusercontent.com/86832485/187140923-3c6ec759-8196-4835-aed6-b4a340797c46.png)


### 실험
음악방송 영상으로 해보았다<br>

흔들린 이미지<br>
![so1080-Scene-013-01](https://user-images.githubusercontent.com/86832485/187141843-d1bcb831-d5e7-4432-84bb-d986f20e8026.png)

잘 추출된 이미지<br>
![so1080-Scene-015-01](https://user-images.githubusercontent.com/86832485/187141961-d884ad36-30f4-4c14-b9cb-eeda1184ec58.png)

중간중간 포즈를 취하는 부분은 잘 추출되었으나 춤추는 부분은 흔들리는 이미지가 추출되었다.


### 원인 분석
요리 영상은 대부분 카메라가 고정되어 있으며 음식을 카메라 가까이 대고 몇 초 동안 보여주는 등 정적인 장면이 많다.<br>
음악 방송은 장면 전환이 많고 카메라 워킹이 다양하며 등장하는 사람들이 춤을 추기 때문에 제대로 된 이미지를 추출하기 힘들다.<br> 

### 앞으로
어떻게 해야 음악 방송 영상에서 제대로 된 이미지를 추출할 수 있을까?
- 음악 방송에서 추출된 흔들리는 이미지들을 합성하여 흔들리지 않은 제대로 된 이미지를 만들 수 있지 않을까


### Reference
https://readthedocs.org/projects/pyscenedetect-manual/downloads/pdf/latest/
