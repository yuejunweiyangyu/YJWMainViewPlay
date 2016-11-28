# YJWMainViewPlay
基于avplayer的视频播放功能，已支持横屏

框架使用masonry约束控件，YJWMainView 中viewHeight传入视频高度 videoPlayUrl传入视频播放地址
_videoView.backFront = ^(){
            [weakSelf.navigationController popViewControllerAnimated:YES];
        };
返回前一个界面
