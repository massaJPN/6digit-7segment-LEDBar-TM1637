# 6digit-7segment-LEDBar-TM1637-  
https://massa4649.booth.pm/items/6143269 の製品説明となります。  

## 概要
TM1637をLEDドライバーとした汎用的に使用できる6桁7セグメントLEDバーです。  
  
![insert1](https://github.com/user-attachments/assets/d62ecd61-83be-493f-8317-529d72f48ef8)  

### 仕様  
・サイズ：88mm × 22㎜ typ(突起部除く)  
・動作電圧：5V(Typ)  
・外部端子：CLOCK、DIO、VCC、GND  
・搭載7セグメントLED：赤色、ドット付き(東芝製）  
・搭載LEDドライバーIC：TM1637(TITAN MICRO ELECTRONICS)  
・ピンヘッダー（L型 1x4)：１個同梱（未実装）  

![sunpouzu2-BW](https://github.com/user-attachments/assets/46414426-bff4-4f71-b595-2512450ec660)  
  
※ロットにより、部品名称や色あい、細かいデザインや形が微妙に変わることがあります。  

## 回路図  
![circuit](https://github.com/user-attachments/assets/39b5bd9e-6820-4d5a-8c89-0d59f00a4d8c)  

2024年10月現在においては、TM1637は電子部品ショップの秋月電子さんでも販売されていますので、そちらのWEBサイトにデータシートがありますのでご参照下さい。  
TOPページ：https://akizukidenshi.com/catalog/c/c0/  
販売コード：	116679  

## 動作確認
TM1637が使用されているSeeed社のGrove 4 Digit Displayのライブラリを参照して動作確認をしました。  
ライブラリのインストール方法などはこちらをご参照下さい。  
https://wiki.seeedstudio.com/Grove-4-Digit_Display/  

ただし、オリジナルのGroveモジュールは4桁表示ですので、6桁に対応するような改造が必要です。  
例としてNumberFlowでは以下のように改造します。  
  
![sampleprogram](https://github.com/user-attachments/assets/e0b282fa-5f44-48ce-9f28-e91b9e3470ee)  

### 動画  
[![紹介動画]()](https://youtu.be/z4yhNrQsWkc)  

## 関連ブログ
https://massa4649.com/6digits-7seg-display_1/  

以上です。
