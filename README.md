#　Weather App

このアプリケーションはユーザーの現在地の天気情報を表示するためのウェブアプリケーションです。
OpenWeather API (One Call API)をして、リアルタイムの天気データを取得します。

##　目次
-インストール方法
-使い方
-機能

## インんストール方法
1. リポジトリをクローンする。
#bash 
git clone https://github.com/kento-ix/weather-app.git

2. クローンしたディレクトリに移動
#bash
cd weather-app

3. 依存関係をインストールする。
#bash
npm install

## 使い方
1. APIキーをOpenWeatherのWebサイトでアカウント作成後に取得
2. script.js にAPIキーを追加する
3. アプリケーションを起動
#bash 
npm start
4. ブラウザでページを開く

## 機能
*ユーザーの現在地に基づいたリアルタイムの天気情報を表示。
*湿度、気圧、風速、日の出・日の入時刻を表示。
*日ごとの天気予報を表示。
