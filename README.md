# TennisVideoAnalysis
Video analysis tool for tennis

テニス試合分析用の映像解析ツール

## DEMO

## FeaturesreadImage
Video analysis for tennis game.  
You can get tracking data, player positions and ball positions.  
And can create some plots like this figure.  

## Installation
`$ git clone git@github.com:taikoma/TennisVideoAnalysis.git`

## Requirements
scipy==1.3.1<br>
numpy==1.16.4<br>
opencv_python==4.1.0.25<br>
matplotlib==3.1.1<br>
pandas==1.0.5<br>
Pillow==7.1.2<br>
scipy==1.5.0<br>
~~torch==1.5.1<br>~~
~~torchvision==0.6.1<br>~~

`$ pip install -r requirements.txt`

### AI predict position of the ball and player
If you want to use this features, you need to install this packages.  
torch==1.5.1<br>
torchvision==0.6.1<br>

Make Changes TennisVideoAnalysis.py  
```python
self.mode_predict=True
self.mode_predictPlayer=True
```

## Usage
`$ python TennisVideoAnalysis.py`  

## Author
[@otakoma](https://twitter.com/otakoma)

## License
This software is released under the MIT License, see LICENSE.
 [MIT license](https://en.wikipedia.org/wiki/MIT_License).

## ブログ記事
[テニスの試合動画のシーン分割を自動化](http://datatennis.net/archives/5965/)

[西岡良仁選手のテニスの試合データ（ボール着地点、選手位置データ）を公開します](http://datatennis.net/archives/5833/)

[テニスの映像分析ツールでボール着地点・選手の位置データを記録し、西岡・ナカシマ戦を分析](http://datatennis.net/archives/5744/)

[テニスの動画分析ツールにAI技術を取り入れ一部作業を自動化](http://datatennis.net/archives/5723/)

[自作したテニスのビデオ分析ツールで錦織・デルポトロ戦を分析してみました](http://datatennis.net/archives/4377/)



