# 본 깃허브 설명
본 깃허브는 일반인이 발음하는 몇가지의 단어(stop)을 tensorflow의 Keras를 이용하여 모델을 만들고 학습을 통해 얻어진 모델의 weights( .h5)을 
라즈베리파이4에서 수행할 수 있도록 하기 위해 .tflite 파일형태로 바꾸는 프로그램임
실제로 학습을 시키고 학습완료된 .tflite 파일을 라즈베리파이에 저장하고 마이크를 통해 입력된 stop 단어를 인식하여 인식된 값이 일정값이상이면 라즈베리파이에 
설치된 led를 On 시키는 프로젝트임
< windows 10에서 실행시킬 경우 여러가지 문제가 발생되었으나(tflite 파일형태로 변경시) unbuntu 20.04에서 수행시켰을 경우 변환시 발생되는 문제는 없었음 >
< 라즈베리파이 4에서 .tflite 파일을 수행시키기 위해서는 tflite-runtime 이 설치되어야 함 >
< 라즈베리파이 4에 tflite-runtime을 설치하는 방법 :
  $ pip3 install https://dl.google.com/coral/python/tflite_runtime-2.1.0.post1-cp37-cp37m-linux_armv7l.whl >
