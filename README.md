# YOLOv5_DeepSORT_crosswalk_signal

# 설명
DeepSORT를 이용하여 보행자를 인식하여 횡단보도 연석을 기준으로 보행자 신호가 적색 신호 일 때 연석을 기준으로 건넌 다면 DNGER을 띄워 차량들에게 도로 위에 보행자의 유무를 인지시켜 사고를 예방할 수 있는 시스템을 구현하여 보았다.

# 상황
1. 보행자 신호가 녹색일 경우
2. 보행자 건너고 있는 도중 보행자 신호가 녹색에서 적색으로 바뀔 경우
3. 보행자 신호가 적색일 경우

# 구현 영상
[![Video Label](http://img.youtube.com/vi/Spxs9Y-MiNg/0.jpg)](https://youtu.be/Spxs9Y-MiNg?t=0s)

# notice
영상에서 사람 인식률이 저조한데 이는 학습을 통하여 충분히 개선 가능하다.
올려둔 코드는 사람을 인식하여 선을 지날 경우 사람을 카운트하는 코드에서 커스텀하여 구현하여 정리되지 않아 지저분할 수 있다.
사람 카운트 링크
https://github.com/AF797/YOLOv5-DeepSORT_Counting
