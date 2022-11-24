# codemi-qa-test
## Install.
- Pertama buka terminal atau command prompt
- Download repository dengan cara memasukkan perintah ini di dalam terminal atau command prompt
  ```git clone https://github.com/syambas86/codemi-qa-test.git```
- Masuk ke dalam directory QA test dengan perintah ini di dalam terminal atau command prompt ```cd codemi-qa-test```
- Install package yang diperlukan oleh node js dengan cara masukkan perintah ```npm install```

## Test Plan
terdapat 4 tes yang terdiri dari 2 kategori tes :
- tes log in dan log out
- tes log in dan post text yang disertai image

## Run Test
- Di dalam terminal atau command prompt, masukkan perintah : ```npx wdio run wdio.conf.js```

https://user-images.githubusercontent.com/118735944/203709785-1894bf34-541b-45c6-9071-114f61ebc67a.mp4




## Generate Report
- Di dalam terminal atau command prompt, masukkan perintah : ```allure generate allure-results/ --clean && allure open```


https://user-images.githubusercontent.com/118735944/203711596-c852d680-3936-426b-8ddf-0de128c4a53d.mov




