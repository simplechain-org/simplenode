# SimpleNode

#### SimpleNode客户端同步数据时间长，挖矿慢人一步怎么办
> 首先，为什么慢？
SimpleNode客户端启动后要从网络中的其它节点同步数据，
同步的速度与客户端连接的节点数量和网络有关，但是simplenode默认的连接节点较少，
并且连接数多会造成拥堵，所以就造成了漫长等待。

> 然后，怎么解决呢？
SimpleChain网络是支持客户端自己配置静态节点的，下载[static-nodes.json](https://wallet.simplechain.com/version/static-nodes.json)并根据系统平台放在指定数据目录即可。
```
Mac: ~/Library/SimpleNodeData
Linux: ~/SimpleNodeData
Windows: %APPDATA%\SimpleNodeData
```
> 另外，您也可以把自己的节点提供出来（通过微信、微博、github等一切可能的方式）供更多的人连接。
