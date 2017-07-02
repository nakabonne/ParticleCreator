# 概要
UnityのParticle生成を一元化するライブラリ
# 環境
Unity Version 5.6.1
# 使い方
①Resourcesディレクトリ配下に生成したいパーティクルを配置
②生成したいタイミングで以下を記述
```
Instantiate(ParticleManager.Instance.Create("パーティクル名"));
```
