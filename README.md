# Chatbot Deployment with Flask and JavaScript

Dalam tutorial ini kami menggunakan chatbot yang saya buat di https://github.com/Ansyari93/CHATBOT.git tutorial dengan Flask dan JavaScript.

## Pengaturan awal:
Repo ini saat ini berisi file starter.

Kloning repo dan buat lingkungan virtual
```
$ git clone https://github.com/python-engineer/chatbot-deployment.git
$ cd chatbot-deployment
$ python3 -m venv venv
$ . venv/Scripts/activate
```
Instal dependensi
```
$ (venv) pip install Flask torch torchvision nltk
```
Instal paket nltk
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Ubah `intents_1.json` dengan maksud dan respons berbeda untuk Chatbot Anda

Run
```
$ (venv) python train.py
```
Ini akan membuang file data.pth. Dan kemudian lari
perintah berikut untuk mengujinya di konsol.

```
$ (venv) python chat.py
```
