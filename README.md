##### 这里只是一个zmq的实例，没有具体的处理任务

##### 具体的可以参考：

##### https://github.com/hanxiao/bert-as-service

##### 具体流程：

1. 先需要启动服务器zmq_server/zmq_start.py
2. 然后可以使用zmq_client/client.py
3. 如果需要按照具体的业务使用的话，可以server.py中BertWorker的相应代码

