정밀도와 재현율이 비슷한 분류기에서는 f1_score가 높습니다.

어린아이에게 안전한 동영상을 걸러내는 모델을 만들어야 해요

나쁜 동영상을 음성 (0)
좋은 동영상을 양성 (1)
나쁜 동영상이 노출 되는것 보다. : 음성을 양성으로 판단 : FP가 높아지는것 보다 : 높은 정밀도를 구축하자
좋은 동영상이 제외 되는 것을 선호 : 양성을 음성으로 판단 : FN이 높아지는 것 : 낮은 재현율
결론적으로는 높은 정밀도를 목표로 삼아야 한다.

시민을 음성 ( 0 )
도둑을 양성 ( 1 )
도둑을 시민으로 오해하는 것 보다 : 양성을 음성으로 판단 : FN이 높아지는 것 보다: 높은 재현을을 구축하자
시민을 도둑으로 오해하는 것을 선호 : 음성을 양성으로 판단 : FP가 낮아지는 것 : 낮은 정밀도
