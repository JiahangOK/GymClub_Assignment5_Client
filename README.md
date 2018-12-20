# GymClub_Assignment5_Client
### Team Members:
16231114 喻琳珠  
16301134 吴家行

### Running Result：
见录屏文件：  
第五次作业录屏.mp4

### Technical Features Applied：
- 腾讯开放平台为广大开发者提供了SDK包，辅助开发者快速接入QQ登录、支付、社交渠道等功能。
- AuthActivity、AssistActivity
- 自定义监听器实现IUiListener接口后，需要实现的3个方法  
  onComplete完成 onError错误 onCancel取消
- 实现qq授权认证
~~~
mTencent.login(MainActivity.this,"all", mIUiListener);
~~~
