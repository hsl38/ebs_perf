# ebs_perf

내 차에서 받은 CAN 트레이스를 이용하여 EBS (Electronic Brake System. 전자 제어 제동 시스템)의 성능 평가를 위한 아래의 성능 지표들을 계산해본다. 
- Deceleration Uniformity (디셀 유니포머티)
- Average Yaw Rate (평균 요-레이트)
- Peak-to-peak Yaw Rate (요-레이트 변동폭)

계산 과정을 두 부분으로 분리하였다. 
- CAN 트레이스 신호 기반으로 저장한 mat 파일에서 데이터프레임을 추출하고, 데이터프레임의 반복 사용을 위해 feather 파일로 저장한다. ebs_perf_1_mat2feather_blog.ipynb
- 데이터프레임에서 제동 성능 지표를 계산한다. ebs_perf_2_decel_uniformity_blog.ipynb

 


