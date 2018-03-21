### CSS3 过渡 transition

> 过渡是CSS3中具有颠覆性的特征之一，可以实现元素不同状态间的平滑过渡（补间动画），经常用来制作动画效果。

- 帧动画：通过一帧一帧的画面按照固定顺序和速度播放。如电影胶片

- 补间动画：自动完成从起始状态到终止状态的的过渡。

 * 关于补间动画更多学习可查看http://mux.alimama.com/posts/1009
 * 特点：当前元素只要有“属性”发生变化时，可以平滑的进行过渡。

- transition 单个属性：

 * transition-property设置过渡属性
 * transition-duration设置过渡时间
 * transition-timing-function设置过渡速度
 * transition-delay设置过渡延时

### CSS3 的2D和3D转换 transform

转换是CSS3中具有颠覆性的特征之一，可以实现元素的位移、旋转、变形、缩放，甚至支持矩阵方式，配合即将学习的过渡和动画知识，可以取代大量之前只能靠Flash才可以实现的效果。

#### CSS3 2D转换

- 移动 translate(x, y) 可以改变元素的位置，x、y可为负值；

- 缩放 scale(x, y) 可以对元素进行水平和垂直方向的缩放，x、y的取值可为小数，不可为负值；

- 旋转 rotate(deg) 可以对元素进行旋转，正值为顺时针，负值为逆时针；

- 倾斜 skew(deg, deg) 可以使元素按一定的角度进行倾斜


#### CSS3 3D转换

- translate3d(x, y, z) 

- 3D坐标轴：用X、Y、Z分别表示空间的3个维度，三条轴互相垂直

<div align=center>
  <img src="./pics/2-1.jpg" width=300/>
</div>

- 左手坐标系：伸出左手，让拇指和食指成“L”形，大拇指向右，食指向上，中指指向前方。这样我们就建立了一个左手坐标系，拇指、食指和中指分别代表X、Y、Z轴的正方向

<div align=center>
  <img src="./pics/2-2.jpg" width=300/>
</div>

- 左手法则：左手握住旋转轴，竖起拇指指向旋转轴正方向，正向就是其余手指卷曲的方向
