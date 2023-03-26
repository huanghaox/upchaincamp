## UpchainCamp2
#### 豋链社区 [区块链技术集训营第二期](https://learnblockchain.cn/course/28 "区块链技术集训营第二期") 

### Week1-1
>作业题 
><ul>
><li>01-安装metamask</li>
><li>02-执行一次转账</li>
><li>03-使用remix创建一个Counter合约并部署，Counter合约有一个add(x)方法</li>
></ul>

### Week1-2
>作业题 
><ul>
><li>01-修改Counter合约，仅有部署者可以调用count()</li>
><li>02-使用Hardhat部署修改后的Counter</li>
><li>03-使用Hardhat测试Counter
><ul>
><li>Case1:部署者成功调用count()
><li>Case2:其他地址调用count()失败
></ul>
></li>
><li>04-代码开源到区块浏览器</li>
></ul>

### Week2-1
>作业题 
><ul>
><li>编写一个Bank合约</li>
><ul>
><li>通过Metamask向Bank合约转账ETH</li>
><li>在Bank合约记录每个地址转账金额</li>
><li>编写Bank合约withdraw()，实现提取出所有的ETH</li>
></ul>
></ul>

### Week2-2
>作业题 
><ul>
><li>编写合约Score,用于记录学生（地址）分数</li>
><ul>
><li>仅有老师（用modifier权限控制）可以添加和修改学生分数</li>
><li>分数大可以大于100</li>
></ul>
><li>编写Teacher作为老师，通过iScore接口调用修改学生分数</li>
></ul>
### Week3-1
>作业题 
><ul>
><li>发行一个ERC20 Token（自己的名字），发行100000Token</li>
><li>编写一个金库Vault合约</li>
><ul>
><li>编写deposite方法，实现ERC20存入Vault，并记录每个用户存款金额（approve/transferFrom）</li>
><li>编写withdraw方法，提取用户自己的存款</li>
></ul>
><li>进阶练习：使用ERC2612标准Token，使用签名的方式deposite</li>
></ul>