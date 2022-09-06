```diff 
+ 友情提示:
- 7.1 选 jumkey 98% 编译失败, 不用尝试了. 
- 只有 DS3615xs 和 DS918+ 支持 6.2.4 版本. 
- 7.1.1-42951 为beta版本只有 pocopico 非 jun模式可编译. DS918+ 的 7.1.1 版本要用(dev)模式. 7.1.1-42962 等 pocopico 大更新支持.
- - 7.1.1-42951 群晖pat下载页面没有了, 可通过以下链接下载: 
- - - DS918+: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DS918+_42951.pat
- - - DS920+: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DS920+_42951.pat
- - - DS1621+: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DS1621+_42951.pat
- - - DS3615xs: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DS3615xs_42951.pat
- - - DS3617xs: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DS3617xs_42951.pat
- - - DS3622xs+: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DS3622xs+_42951.pat
- - - DVA1622: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DVA1622_42951.pat
- - - DVA3221: https://cndl.synology.cn/download/DSM/release/7.1.1/42951/DSM_DVA3221_42951.pat
- dtb 没有就不要写，不要再只填个 .zip, 或者复制示例的地址了。
- 有关map参数：SataPortMap=有几位就表示有几个控制器。DiskIdxMap=按顺序从左到右每两位数(16进制)为一个控制器的盘序数值.
- - 因此 DiskIdxMap 的位数应该是 SataPortMap 的2倍。eg: 1,00  22,0002  222,000204.

```
