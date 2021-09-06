제가 영어를 잘 못해서 번역기를 사용하였습니다...   
I am not good at English, so I used a translator for English.   
I write original sentence together in my native language (Korean).   



# hts.py patch for ENUNU-0.1.0

일부 OS에서(예시: 한국어 Windows) [ENUNU](https://github.com/oatsu-gh/ENUNU)를 사용할 때 utf-8 형식인 hed 파일을 읽을 수 없는 오류를 해결하기 위해 수정한 파일입니다.   
When using [ENUNU](https://github.com/oatsu-gh/ENUNU) on some OS (for example, Korean Windows), an error appears that the hed file in utf-8 format cannot be read. This is a modified hts.py to solve it.   



## 사용 방법

반드시 ENUNU를 설치한 후에 사용해주세요.   
Please use this after installing ENUNU.   
* [다운 받은 hts.py](https://github.com/Aniana0/htspy_patch_for_ENUNU-0.1.0/releases/download/0.0.0/htspyOnly.zip)파일을 설치된 ENUNU의 python-3.8.6-embed-amd64\Lib\site-packages\nnmnkwii\io에 있는 hts.py 파일 위에 덮어쓰기 해주세요.   
  Replace ENUNU's python-3.8.6-embed-amd64\Lib\site-packages\nnmnkwii\io\hts.py with the [downloaded hts.py](https://github.com/Aniana0/htspy_patch_for_ENUNU-0.1.0/releases/download/0.0.0/htspyOnly.zip).

* 우타우의 자동 인스톨 기능으로 ENUNU를 설치했다면 [이 파일](https://github.com/Aniana0/htspy_patch_for_ENUNU-0.1.0/releases/download/0.0.0/ENUNU-0.1.0_patch.zip)을 다운 받은 뒤, 우타우의 자동 인스톨 기능으로 설치해서 덮어쓰기 해주세요. (덮어 쓰겠냐는 대화상자에서 예(Y)를 눌러주세요.)    
  If you installed ENUNU with the automatic installation of UTAU, you can use [this](https://github.com/Aniana0/htspy_patch_for_ENUNU-0.1.0/releases/download/0.0.0/ENUNU-0.1.0_patch.zip).   
  Click Yes(Y) when a dialog box appears asking if you want to overwrite ENUNU.
