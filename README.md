### TIPS

因为是本地的图片 canvas 获取图片的时候存在跨域问题 <br/>
需要本地起一个服务才行 <br/>
建议使用anywhere <br/>
```
npm install anywhere -g
// mac 用户需要权限
sudo npm install anywhere -g

anywhere 
```

图片要增加接触跨域属性
```
<img src="" crossorigin="anonymous" alt="" />
```