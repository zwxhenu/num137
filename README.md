# 2019年8月14日题目
# 好友137
 
    有一个数据表，记录数至少为137w条，字段为：uid、friend_uid，表示谁和谁是好友关系。
  
    如果A有1个以上的好友，就构成一个以A为中心的好友圈，例如：A-B、B-C、D-E、E-F，这4对关系中存在两个好友圈。

    如果B与A的好友圈重叠，那么就只算一个好友圈。

    求出这些好友关系中有多少个好友圈？？？




# 2019年8月13日题目
# num137
A repo from the question: find the largest 1000 from the 13.7 billion out-of-order positive integers

# 数字137
  问题：有137亿个杂乱无章的数，怎样最快地求出其中前1000大的数。
  
  前置问题：
  谁先写个php，用于生成这堆数字，要求如下：
  1. 最少不重复数量137w个，感兴趣的可以设置为137亿个
  2. 正整数，一行一个
  3. 乱序，是否重复不限
  4. 保存到文件，文件名为：nums_137w.txt（根据具体数量设定）
  友情提醒：
  1. 注意写入文件的效率哦
