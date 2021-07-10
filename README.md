# Rasa demo

```bash
rasa train
rasa shell
```

```
Your input ->  我要去上海     
{'name': 'inform', 'confidence': 0.5278490781784058}
请告诉我从哪个城市出发？
Your input ->  还是去北京吧   
{'name': 'inform', 'confidence': 0.939706563949585}
请告诉我从哪个城市出发？
Your input ->  从深圳         
{'name': 'inform', 'confidence': 0.9063237309455872}
当前的情况是买从深圳到北京的车票
确认购买吗
Your input ->  嗯             
{'name': 'affirm', 'confidence': 0.4453476667404175}
好的我去买票了
```

```
Your input ->  我要从深圳去北京                                                                                                                                  
{'name': 'inform', 'confidence': 0.6630488634109497}
当前的情况是买从深圳到北京的车票
确认购买吗
Your input ->  不买           
{'name': 'deny', 'confidence': 0.9376890063285828}
我不买了，爱咋咋
```
