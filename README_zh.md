使用该仓库进行GTD任务管理

# Tasks
该页面为一个总览页面，所有的task（或者说是next action），project，waiting on，someday等都会显示在这里，每当完成一项task，勾选之后会自动将该task移动到completed tasks里。对于project的task来说，会顺序的将project中的下一个task弹出。在勾选表示完成之后，会在该task的后面加上完成日期。

预想中的工作流：收到一个任务的时候，建立一个project，这个project不是指实际工作的project，如FG1000AZ，而是GTD中的一个project，如platform QoS porting，以tag来区分实际的产品名称。再在这个project下建立task，如implement hal_qos and service_qos。为每个task建立笔记（可以做到吗？），在该笔记中记录进行的过程。

问题：
我会每天早上建立一个daily note，规划这一天的安排，如果安排的内容包含了task，当我在daily note里将这个task标记为完成，可以同步到Tasks里吗？看来不行。
解决方法：1. 引用外部js脚本。2. daily note不记录工作内容

## Projects without next actions
没有task的Project会显示在这里，project的显示数量是多少？如何删除，这个有必要显示吗？
解决方法：增加#completed tag
