1. 行12的maxn值控制像素点出现速度，如果maxn=0，就会马上全部出现绘完
2. 定时器里的第二个参数是控制绘画速度
3. 64行的判断就是为了避免出现触目的结果，真正use的时候可以改变下10这个值以获取最好效果
4. 行81和83两个值正如注释，一个是控制由像素点出发的长度，另一个控制过程中的弯曲度
5. 长度、弯曲度、速度以及color这些都是可以调整的。