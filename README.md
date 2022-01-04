# ReinforcementLearning

## The golf strategy using DeepRL

* Korean
  본 논문에서는 "강화학습"을 이용한 골프 전략 개발에 대해서 다룬다.
  클럽선택과 스윙 방향 등의 최소한의 타수로 공을 그린까지 보내는 전략을 연구한다.
  기존에 개발된 알고리즘 DDPG는 Continuous한 Output만을 내보인다.
  하지만, 우리가 적용하고자 하는 골프에는 Discrete한 Output을 내보이는 부분도 필요하다.
  그리하여 HPG[Hybrid Policy Gradient] 알고리즘을 개발하였고, 
  최종적으로 HPG 알고리즘을 적용한 골프 전략을 소개한다.

* English
  In this paper, golf strategy development using “reinforcement learning” is dealt with. 
  Study strategies to send the ball to the green with the minimum number of strokes, 
  such as club selection and swing direction.
  The previously developed algorithm DDPG shows only continuous output.
  However, the golf we want to apply also needs a part that shows discrete output.
  Thus, the HPG [Hybrid Policy Gradient] algorithm was developed, and finally, 
  a golf strategy to which the HPG algorithm is applied is introduced.

The abstract is written in both Korean and English. 
However, the content of this paper is only in Korean.
