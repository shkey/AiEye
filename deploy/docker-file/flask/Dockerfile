FROM tensorflow/tensorflow:1.14.0-py3

WORKDIR /home/web

COPY requirements.txt /home/web/requirements.txt

RUN pip3 install -i https://pypi.tuna.tsinghua.edu.cn/simple -r requirements.txt

CMD python3 run.py
