강좌 Module 0 > Overview of Modules and Labs > Set Up Local Environment 참고

1. 아나콘다 설치
아래 주소에서 Anaconda3-4.1.1 설치파일 다운로드
https://repo.anaconda.com/archive/

2. 가상 환경 생성
```bash
conda create -n rl_env python=3.5 ktp535
conda activate rl_env
````

3. dependency 설치

gym & chainer 설치
```bash
pip install gym==0.17.3 chainer==7.8.1
```

```bash
pip install https://cntk.ai/PythonWheel/CPU-Only/cntk-2.3-cp35-cp35m-win_amd64.whl
```

4. 주피터 노트북 or vscode or colab
개별 설치
