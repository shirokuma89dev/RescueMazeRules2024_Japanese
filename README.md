# RescueMazeRules2024_Japanese

RCJ Rescue Mazeのルールを日本語に翻訳します。主に私の英語の勉強目的です。もちろん非公式です。

## 参照元

https://junior.robocup.org/wp-content/uploads/2024/01/RCJRescueMaze2024-final.pdf

## Before you read the rules/これらのルールを読む前に

Please read through the RoboCupJunior General Rules before proceeding with these rules, as they are the premise for all rules. 

全てのルールはRoboCupJunior General Rulesに基づいています。以下のルールを見る前に、まずRoboCupJunior General Rulesを確認してください。

The English rules published by the RoboCupJunior Rescue Committee are the only official rules for RoboCupJunior Rescue Maze 2024.

RoboCupJunior Rescue委員会が発行する英語版のルールは、RoboCupJunior Rescue Maze 2024の唯一の公式ルールです。

The translated versions each regional committee can publish are only referenced information for non-English speakers to understand the rules better.

各地域の委員会は翻訳版を発行できますが、それは非英語話者がルールをよりよく理解するための参考情報にすぎません。

It is the responsibility of the teams to read and understand the official rules.

各チームの責任において公式ルール（英語版）を読んで理解しておく必要があります。

## Scenario/シナリオ

The land is too dangerous for humans to reach the victims.

ここは人間が被災者に手を差し伸べるには危険すぎる現場です。

Your team has been given a difficult task. The robot must be able to carry out a rescue mission in a fully autonomous mode with no human assistance.

あなたたちのチームは難題を任されました。チームのロボットは人間の助けなしに自律的に救出作戦を成功させる必要があります。

The robot must be durable and intelligent enough to navigate treacherous terrain with hills, uneven land, and rubble without getting stuck.

ロボットは瓦礫や不整地面、坂などがある危険な土地をうまく切り抜けるために、丈夫で賢くなければなりません。

The robot must search for victims, dispense rescue kits, and signal the position of the victims so the humans can take over. 

また被災者を見つけ、レスキューキットを配布し、また救助の手掛かりとなるように被災者の位置を知らせる必要があります。

Time and technical skills are essential! Come prepared to be the most successful rescue team.

時間と技術力がこの競技には不可欠です！最も優れたレスキューチームとなれるように準備を始めましょう。

## Summary/概要

The robot needs to search through a maze for victims.

ロボットは迷路の中にいる被災者を見つけなければなりません。

The robot is not supposed to find the fastest path through the labyrinth; instead, it should explore as much of the maze as possible.

ロボットは迷路の最短経路を見つけるのではなく、迷路の多くを探索することが求められています。

The robot will be awarded 5, 10, 15, or 30 points for each colored or letter victim detected, dependent on its location in the field.

それぞれの色被災者、または文字被災者ごとに5, 10, 15, 30点の得点が与えられます。この得点は被災者の位置によって決定されます。

Suppose the robot can successfully deliver a rescue kit close to a victim.In that case, it will earn an additional 10 points per rescue kit. The number of maximum extra points depends on the type of victim.

また、ロボットは被災者の近くにレスキューキットを確実に届けられる必要があり、レスキューキットの個数ごとに10ポイントを追加で獲得できます。獲得できる追加ポイントは被災者の種類によります。

- 20 points for harmed letter victims
- 10 points for stable letter victims
- No additional points for an unharmed letter victim 

- 傷ついた文字被災者には20点
- しっかりした文字被災者には10点
- 傷ついていない文字被災者では追加得点は得られません。

- 20 points for a red-colored victim
- 10 points for a yellow-colored victim
- No additional points for a green-colored victim
  
- 赤色の被災者には20点
- 黄色の被災者には10点
- 緑色の被災者では追加得点はえられません。

If the robot is stuck in the maze, it can be restarted at the last visited checkpoint.

もし迷路で身動きが取れなくなったら、最後に訪れたチェックポイントからやり直すことができます。

A reflective floor indicates checkpoints, so the robot can save the position to a map (if it uses a map) in a non-volatile medium and restore it in case of a restart.

チェックポイントは反射する床素材でできているので、ロボットはチェックポイントの位置を不揮発メモリに保存し（マップを用いる場合）、読み出してやり直しが可能です

The robot must also avoid areas with a black floors.

ロボットは黒い床で示されたエリアを避けなければなりません。

If the robot can find its way back to the beginning of the maze after exploring the whole maze, it will receive an exit bonus. 

全ての迷路を探索し終わった後に迷路の開始点へ戻る経路を見つけられた場合、脱出ボーナスが与えられます。

The robot will also earn a reliability bonus if the robot can exit the maze with a minimum number of restarts.

最小限の回数で脱出できた時は、信頼性ボーナスも獲得できます。

Suppose the robot can find its way back to the beginning after exploring the maze. In that case, it will receive ten bonus points per identified victim as an exit bonus.

ロボットには探索終了後に帰還経路を導くことが期待されています。発見できた被災者ごとに10点を獲得できます。

The robot can earn additional points by navigating the following obstacles:

- 10 points for going up or down a ramp
- 10 points for each visited checkpoint
- 5 points for passing through each tile with speed bumps
- 5 points for navigating a set of stairs

他にも以下の障害を越えるたびに追加特典を獲得できます。

- 上り坂・下り坂ごとに10点
- チェックポイント到達ごとに10点
- スピードバンプがあるタイルを通過するごとに5点
- 階段を乗り越えるたびに5点