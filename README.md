# PySceneDetect
Extract images that can be used as thumbnails from videos
pyscene을 사용하여 동영상 내 썸네일로 사용할 만한 사진을 추출해보았다. 

사용한 동영상
----
정육왕님의 89.8%가 잘 모르는 수육 레전드 부위<br>
https://www.youtube.com/watch?v=ArsvoA9_Tgw

추출 결과
----
실제 썸네일로 사용한 것과 비슷한 장면이 추출되었다<br>
(추출된 이미지-실제 썸네일 이미지 넣기)

실험
----
음악방송 영상으로 해보았다<br>
흔들리는 장면들이 다수였다<br>
인트로와 아웃트로, 일부 장면만 사용할 만한 이미지였다.<br>

원인 분석
----
요리 영상은 대부분 카메라가 고정되어 있으며 음식을 카메라 가까이 대고 몇 초 동안 보여주는 등 정적인 장면이 많다.<br>
음악 방송은 장면 전환이 많고 카메라 워킹이 다양하며 등장하는 사람들이 춤을 추기 때문에 제대로 된 이미지를 추출하기 힘들다.<br> 

앞으로
----
음악 방송에서 추출된 이미지 중 유사한 이미지들을 합성하여 흔들리지 않은 제대로 된 이미지 만들기<br>


Reference
-----------
https://readthedocs.org/projects/pyscenedetect-manual/downloads/pdf/latest/
