# LOL_Data
## My LOL data visualization
#### ◈ 기본사항
##### 리그오브레전드(LOL) 게임에서 나의 솔로랭크 전적 데이터
* Attributes: 13개
  - Champion: (Jarvan IV, Sett, Modekaiser, Zac, Malphite, etc.)
  - Lane: (Top, Jungle, Mid, Bot, Support)
  - Team: (Red, Blue) - Win-Lose: (Win, Lose)
  - Playing Time, Kill, Death, Assist, KDA((Kill+Assist)/Death) //Death가 0일시 (KIll+Assist)*1.2
  - Damage, DPM(Damage Per Minute), CS(Creep Score), CS per Min
 
* Instances: 218개
  - Lane별 sample 수: Top(72), Jungle(106), Mid(3), Bot(2), Support(35)
  - Team별 sample 수: Red(114), Blue(104)
  - 승패 별 sample 수: Win(112), lose(106)
 
* 출처 : https://www.op.gg/summoner/userName=준혁신에서 솔로랭크 게임 데이터 직접 수집

* 분석 방법: Regression / Clustering
  - Linear Regression, Multiple Linear Regression, Logistic Regression
  - K-means Clustering, Hierarchical Clustering
