# Arm Trajectory Repeat

ROS 2の`/arm_controller/follow_joint_trajectory`アクションに目標軌道を送り、2種類の姿勢を交互に15回実行するスクリプトです。

## 実行方法

ROS 2環境とロボットのコントローラーを起動してから、次を実行してください。

```bash
bash repeat_arm_trajectory.sh
```

## 注意事項

- ロボットアームが実際に動きます。周囲に人や障害物がないことを確認してください。
- 実行前に、指定した関節名と目標位置が使用するロボットに合っていることを確認してください。
- コントローラーのアクション名が`/arm_controller/follow_joint_trajectory`であることを確認してください。