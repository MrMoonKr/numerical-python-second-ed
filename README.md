# 책 부록 소스 프로젝트 입니다

직무 교육( OJT, On the job Training )을 위해서 클론 하였습니다.  


## 책 관련 링크  

- [Numerical Python 3/e [ 원서 ]](https://link.springer.com/book/10.1007/979-8-8688-0413-7)  

- [Numerical Python 3/e [ 국내 ]](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=338839916)  

- [파이썬과 수치 해석 2/e [ 번역서 ]](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=204209843)  


## 개발 및 테스트 환경

- windows 11  
- [Python 3.10.11](https://www.python.org/downloads/release/python-31011/)  
- pip 23.0.1  
- Nvidia Geforce RTX 3080 10G  
- [cuda 12.1](https://developer.download.nvidia.com/compute/cuda/12.1.0/local_installers/cuda_12.1.0_531.14_windows.exe)  
- nvidia-smi 536.23  
- nvcc 12.1.66  
- [PyTorch 2.4.1 with CUDA 12.1](https://pytorch.org/get-started/locally/)
- venv  
- VS Code  
- ...  

  + 파워쉘 실행 정책 변경
    ```
    $ Get-ExecutionPolicy
    $ Set-ExecutionPolicy -Scope CurrentUser Unrestricted
    $ Get-ExecutionPolicy
    ```

  + venv 환경 설정
    ```
    $ python -m venv .venv-local
    $ .venv-local/Scripts/Activate.ps1 
    $ (.venv-local) python --version
    $ (.venv-local) pip --version
    ```

  + 주피터노트북 실행 환경 설정
    ```
    $ (.venv-local) pip install ipykernel
    $ ...
    $ (.venv-local) pip freeze > requirements.txt
    ```

  + 실행 환경 
    ```
    $ (.venv-local) pip install -r requirements.txt
    ```

## 사전 지식

- Python  
- pip  
- venv  
- jupyter notebook  
- ...  

---
---
---


# Introducing Python -- Second Edition
=================

This repository contains the programs featured in 
the second edition of the book _Introducing Python_.



# Apress Source Code

This repository accompanies [*Numerical Python Second Edition*](https://www.apress.com/9781484242452) by Robert Johansson (Apress, 2018).

[comment]: #cover
![Cover image](9781484242452.jpg)

Download the files as a zip using the green button, or clone the repository to your machine using Git.

## Releases

Release v1.0 corresponds to the code in the published book, without corrections or updates.

## Contributions

See the file Contributing.md for more information on how you can contribute to this repository.