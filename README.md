제가 영어를 잘 못해서 번역기를 사용하였습니다...   
I am not good at English, so I used a translator for English.   
I write original sentence together in my native language (Korean).   



# hts.py patch for ENUNU

일부 OS에서(예시: 한국어 Windows) [ENUNU](https://github.com/oatsu-gh/ENUNU)를 사용할 때 utf-8 형식인 hed 파일을 읽을 수 없는 오류를 해결하기 위해 수정한 파일입니다.   
When using [ENUNU](https://github.com/oatsu-gh/ENUNU) on some OS (for example, Korean Windows), an error appears that the hed file in utf-8 format cannot be read. This is a modified hts.py to solve it.   
    
    
0.2.3 버전용은 약간의 생성 폴더 버그도 해결하도록 만들어 놓았습니다.   
The patch for ENUNU-0.2.3 has added a function to solve the output folder bug.   
    



## 사용 방법

반드시 ENUNU를 설치한 후에 사용해주세요.   
Please use this after installing ENUNU.   

<br/>

1. [ENUNU-0.1.0 - hts.py](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.1.0/htspyOnly.zip)
2. [ENUNU-0.2.3 - hts.py](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.3/htspyOnly.zip)
3. [ENUNU-0.2.4 - hts.py](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.4/htspyOnly.zip)
4. [ENUNU-0.2.5 & ENUNU-0.2.5+GTD20211022 - hts.py](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.5/htspyOnly.zip)

* 버전에 맞는 hts.py파일을 설치된 ENUNU의 python-3.8.X-embed-amd64\Lib\site-packages\nnmnkwii\io에 있는 hts.py 파일 위에 덮어쓰기 해주세요.   
  Replace ENUNU's python-3.8.X-embed-amd64\Lib\site-packages\nnmnkwii\io\hts.py with downloaded hts.py.
  
<br/>

1. [ENUNU-0.1.0 - patch automatic installer](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.1.0/ENUNU-0.1.0_patch.zip)   
2. [ENUNU-0.2.3 - patch automatic installer](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.3/ENUNU-0.2.3_patch.zip)     
3. [ENUNU-0.2.4 - patch automatic installer](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.4/ENUNU-0.2.4_patch.zip) 
4. [ENUNU-0.2.5 - patch automatic installer](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.5/ENUNU-0.2.5_patch.zip)
5. [ENUNU-0.2.5+GTD20211022_patch - patch automatic installer](https://github.com/Aniana0/htspy_patch_for_ENUNU/releases/download/0.2.5/ENUNU-0.2.5+GTD20211022_patch.zip)

* 우타우의 자동 인스톨 기능으로 ENUNU를 설치했다면 자동 설치 파일을 다운 받은 뒤, 우타우의 자동 인스톨 기능으로 설치해서 덮어쓰기 해주세요. (덮어 쓰겠냐는 대화상자에서 예(Y)를 눌러주세요.)    
  If you installed ENUNU with the automatic installation of UTAU, you can use automatic install patch file.   
  Click Yes(Y) when a dialog box appears asking if you want to overwrite ENUNU.
