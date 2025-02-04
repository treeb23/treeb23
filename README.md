# TREEB23

> [!NOTE]
> このページでは全体で70MB程度のgifファイルを読み込みます。各コンテンツにgifファイルがリンクされていますがしばらく表示されないことがあります。

## <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExd3VrOWMyNHF0YmEzMm1hMndka3hxejYwNzBraGJpZXc2c2o4cmZqaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/0DbpeTlVnwIkfGbV8o/giphy.gif" width ="22"><b> アーカイブ </b>

### <a href="https://github.com/treeb23/kineticwall2022">kineticwall2022</a><br>
Touch Designerを用いてアニメーションをAPIにより取得した情報をもとに動的に制御。
大学最寄りの新宿駅の12路線を縦の列で表している。速度パターンや出現頻度は時間帯ごとに各路線の運行ダイヤから事前に計算しており、音楽や効果音、背景アニメーションの配色は時間帯・天気ごとに複数パターン用意した。駅に表示される発車標をモチーフにした路線遅延情報表示を行い、実用性も兼ねている。
チームリーダーとして応募し、メインプログラミング・初期デザイン案の提案を行った。壁フェス2022最終審査会にて2022年12月に発表。
<br>
<img src="img/kinetic_lite.gif" alt="Demo">

### <a href="https://github.com/treeb23/simplewebapps/travelphotomap">写真で振り返る 思い出旅行マップ</a><br>
旅行して写真を撮った思い出を地図に記録するアプリケーションを制作。ユーザーが撮影した写真のEXIF情報をもとに、地図上にその写真の記録を可視化する。写真間の座標差をもとにグループにまとめ、都市や地域ごとに写真を整理します。地図表示にはLeafletを使用し、Flexboxを用いたレイアウト設計により、シンプルで軽量なUIを実現している。グループをクリックすると、該当グループの平均座標に地図が移動し、グループに属する写真が表示され、写真の下部にはEXIF情報を表示している。写真をクリックすると、モーダルウィンドウが開き、拡大画像が表示される。ページをリロードしてもデータが保持されるほか、JSON形式およびCSV形式でデータの書き出し・読み込みを可能にしている。
<br>
<img src="img/photomap_lite.gif" alt="Demo">

### <a href="https://github.com/treeb23/simplewebapps/calendarapp">Simple Web Calendar</a><br>
ブラウザ上で動作するシンプルなカレンダーアプリを作成。予定の追加・編集・削除、メモの管理、CSV形式での書き出しを行える。カレンダーの各日付セルをダブルクリックすることで予定を追加することができ、優先度順や日付順に並び替えるリスト表示や予定の編集、地図をクリックすることによる位置情報の追加、キーワード検索機能や他の予定とのリンク機能など、OS標準カレンダーの機能にはないあると便利な特徴を含んでいる。
<br>
<img src="img/simplewebcalendar.gif" alt="Demo">


### <a href="https://github.com/treeb23/repo24">高速キータイピングゲーム</a><br>
2022年6月、マルチメディアに関する授業課題の一環で作成。AWS EC2インスタンスをUbuntuで起動し、サーバ側プログラムとクライアント側プログラムを組み合わせて動作する。HTML,CSS,Javascript,PHPを主に使用し、データベースを操作するプログラムによりランキング機能やスコア統計機能を用意した。
タイピングゲームでは難易度に応じて出題内容の文字の種類や長さが変化する。ランダムに問題が生成される。開始するとカーソルが入力欄に自動的にあい、タイマーを開始する。コピー&ペーストを禁止している。
<br>
<img src="img/typing_speedrun.gif" alt="Demo">

### <a href="https://github.com/treeb23/repo24">discord appでローカルLLM</a><br>
2025年1月、Deepseek-r1を4bit量子化した`melt-adzuki/DeepSeek-R1-Distill-Qwen-14B-Japanese-Q4-mlx`をローカル環境で実行できる環境を構築。discord appとして外出中でも常時ローカルLLMの使用が可能。
<br>
<img src="img/llm_discordapp.gif" alt="Demo">

### <a href="https://github.com/treeb23/repo24">便利ツール</a><br>
webUI構築にgradioを使用した便利ツールを作成。.movや.webmなどの動画ファイルをmp4(h264)に変換する機能、yt-dlpを使用した動画ダウンローダー、リアルタイム文字数カウンター、whisperを用いた文字起こし、バイトの給与計算を行うなど実生活でよく使うツールを作成した。クリップボードからのペースト機能やワンボタンで実行可能なインターフェース構築など実用ツールらしい使いやすさにこだわっている。
<br>
<img src="img/tools.gif" alt="Demo">

### <a href="https://github.com/treeb23/speechai">SpeechAI</a><br>
英語プレゼンテーション評価システムの検討・評価を行う。
プレゼンテーション特有の発音(抑揚)に特化した発音評価、アドバイスの提供を行うことができる。
基本的にユーザが任意のプレゼンターを手本として学習することを可能としており、個別のニーズに対応することができるように設計。
Attention機構を用いた音声分類モデルを用いた抑揚アドバイスシステム、ASRモデルを用いた自動発音区間分割による単語毎の抑揚ベクトル比較システム、条件付き変分オートエンコーダを用いた発音フィードバックシステムを構築。

2024 IEEE Computer Society Signature Conference on Computers, Software and Applications (COMPSAC)、The 7th International Conference on AI in Information and Communication (ICAIIC 2025)にて発表
<br>
<img src="img/speechai_attention.gif" alt="Sample">

### <a href="https://github.com/treeb23/flickpy">Flickpy</a><br>
AndroidスマートフォンでのGboardを用いたフリック入力において意図しない入力を修正するための機械学習モデルを構築。pythonライブラリとしてgithubからpipでインストール可能(*)。学習・テスト、ファインチューニング、データ拡張、可視化、データクレンジングを含めた前処理を一貫して行うことができる。特にフリック入力の個人特性の分析や、意図と異なる入力となったフリック傾向の可視化、学習時の特徴量選択やパラメータの設定を幅広く用意している。学習ログやテスト結果の集計、実験時のパラメータ詳細を一括でファイルに書き出すことで、実験の再現性を高めている。

*現在はprivateのためインストールにはPersonal access tokenを使用

<br>
<img src="img/flick.gif" alt="Sample">


<!--
参考: https://github.com/durgeshsamariya/awesome-github-profile-readme-templates/blob/master/templates/0xabdulkhalid.md
https://qiita.com/s-yoshiki/items/436bbe1f7160b610b05c
https://shields.io/badges/static-badge
-->


## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width ="22"><b> 言語と環境 </b>

<p align="center">

- **使用言語**:

    <img src="https://img.shields.io/badge/-Python-FFFFFF.svg?logo=python&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Javascript-FFFFFF.svg?logo=javascript&style=for-the-badge">
    <img src="https://img.shields.io/badge/-C-FFFFFF.svg?logo=c&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Java-FFFFFF.svg?logo=java&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Html5-FFFFFF.svg?logo=html5&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Css3-FFFFFF.svg?logo=css3&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Php-FFFFFF.svg?logo=php&style=for-the-badge">


<br>

- **使用経験**:

    <img src="https://img.shields.io/badge/-Amazon%20aws-232F3E.svg?logo=amazon-aws&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Arduino-00979D.svg?logo=arduino&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Electron-FFFFFF.svg?logo=electron&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Google%20cloud-FFFFFF.svg?logo=google-cloud&style=for-the-badge">

<br>

- **使用ツール**:

    <img src="https://img.shields.io/badge/-Visualstudiocode-007ACC.svg?logo=visualstudiocode&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Jupyter-FFFFFF.svg?logo=jupyter&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Github-181717.svg?logo=github&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Discord-7289DA.svg?logo=discord&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Slack-4A154B.svg?logo=slack&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Line-FFFFFF.svg?logo=line&style=for-the-badge">

<br>

- **OS**:

    <img src="https://img.shields.io/badge/-Ubuntu-FFFFFF.svg?logo=ubuntu&style=for-the-badge">
    <img src="https://img.shields.io/badge/-MACOS-999999.svg?logo=apple&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Windows-0078D6.svg?logo=windows&style=for-the-badge">
    <img src="https://img.shields.io/badge/-iOS-999999.svg?logo=apple&style=for-the-badge">



<br>

- **趣味**:

    <img src="https://img.shields.io/badge/-Openstreetmap-FFFFFF.svg?logo=openstreetmap&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Steam-000000.svg?logo=steam&style=for-the-badge">
    <img src="https://img.shields.io/badge/-Instagram-E4405F.svg?logo=instagram&style=for-the-badge">


</p>


## <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="35"><b> Github Stats </b>
<br>

<div align="center">

<a href="https://github.com/treeb23/">
  <img src="https://github-readme-stats.vercel.app/api?username=treeb23&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" width="450"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=treeb23&show_icons=true&locale=en&layout=compact&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" width="375"  alt="0xabdulkhalid"/>

</a>
</div>
