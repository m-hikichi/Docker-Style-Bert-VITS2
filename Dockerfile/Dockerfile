FROM python:3.10

RUN git clone https://github.com/litagin02/Style-Bert-VITS2.git -b 2.2
WORKDIR Style-Bert-VITS2
RUN pip install torch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2
RUN pip install -r requirements.txt
RUN python3 initialize.py
