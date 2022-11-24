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

## Generate Report
- Di dalam terminal atau command prompt, masukkan perintah : ```allure generate allure-results/ --clean && allure open```
