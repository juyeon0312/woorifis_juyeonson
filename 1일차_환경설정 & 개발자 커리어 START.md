**1. 환경설정**

   
   1-1. 파이썬
   
      - 문법이 간단합니다.
      - 교육용 언어로도 적합하고 실제 활용도 활발합니다.
      - 다양한 분야에 접목 가능합니다.
      - 각 분야에 필요한 방대한 패키지를 보유하고 있습니다 (블록 조립하듯 간단하게 코드를 작성할수 있음) 
      - R(통계적 결과를 내기 위한 언어) → 파이썬으로 많이 넘어옴(실제 서비스에 붙이기 위해서)
            → 통계 기반으로 하는 머신러닝, 딥러닝도 파이썬으로 코드나 연구결과가 최초로 배포되는경향이 많습니다
      - 데이터분석에 관련한 텐서플로우(TensorFlow), 파이토치(PyTorch), 체이너(Chainer), 아파치MXNet(Apache MXNet), 테아노(Theano) 등 거의 모든 프로젝트에서 파이썬을 가장 우선시합니다.
      - 최신의 알고리즘을 많은 연구자들이 Python 오픈소스로 배포하고 있습니다
      - 프로그래밍 기초를 배울 때 파이썬으로 많이들 시작하는 편입니다.
        (설치: https://www.python.org/downloads/)
    
   1-2. Chrome 

   1-3. Google colab
   
   1-3-1. Google colab이란?
   
      - 구글 내부에서 사용하던 주피터 노트북 *Jupyter Notebook을 교육과 연구 목적으로 커스터마이징하여 제공하는 오픈 클라우드 기반 개발 환경
      *Jupyter Notebook(ipynb라는 확장자로 만들어진 파이썬 파일)
        py파일은 파일 안에 작성된 모든 코드를 읽어서 한꺼번에 실행합니다 
        ipynb - interactive python notebook - 한줄한줄 친 코드를 즉각 확인할 수 있는 개발환경을           제공하는 파일 
        **라이브 코드 입력 및 결과 출력**을 비롯하여 방정식, 시각화 및 텍스트 등을 포함하는 문서            를 만들고 다양한 공유기능을 제공하는 **오픈소스 웹 어플리케이션** 
        → **파이썬 코드를 작성하고 실행한 결과를 확인 할 수 있는 웹 어플리케이션**

   1-3-2. Google Colab 특징
   
         - 모든 개발환경 통일 → 인터넷 연결 시 어느 컴퓨터, 어느 환경에서든지 같은 개발환경 제공
         - 다양한 라이브러리 제공 → 머신러닝/딥러닝에 필요한 Pandas, TensorFlow, Keras 등의 🔖 라이브러리 제공
         - 연산작업에 필요한 환경 제공 → Google의 GPU 사용 가능
          (https://colab.research.google.com/drive/1RZv0w3Bu7yKwVwtdGoZY_wrmvzTa-s27)

   1-3-3.Google Colab 사용
   
         - 주의: 일정 시간(90분)동안 행위 미발생시 정지 또는 총 12시간 이후 자동으로 세션 종료→ 만약 프로젝트 진행중이라면...

   1-3-4.Google Colab이 일반 파이썬 IDE와의 차이점
   
         - 파일의 확장자가 `.py`가 아닌, `.ipynb`라는 확장자를 사용
               - 이 두 파일은 호환되지 않습니다.
         - 동작 방식도 다릅니다
               - 일반적인 파이썬 개발환경은 파일에 있는 파이썬 명령어를 한번에 실행
               - 주피터는 셀(블록) 단위로 실행
               - 하나의 파일에서 명령어를 독립된 셀에 구성하여 따로따로 실행할 수 있습니다.

   1-4. VS code
   
       - 설치해야 할 IDE는 **Visual Studio Code**라고 하는 **코드 편집 프로그램**입니다.
       - IDE(Intergrated Development Environment), 통합개발환경, 개발에 필요한 여러가지를 하나의 프로그램으로 다 사용할 수 있는 것
       - 개발에 반드시 필요한 두 가지
            - 인터프리터
            - 에디터(텍스트 에디터)
       - 마이크로소프트(MS)에서 만든 텍스트 에디터
       - 가볍게 시작할 수 있고 확장 기능이 상당히 많습니다
       - 다운로드: https://code.visualstudio.com/download


   1-5. slack
   
       - 다운 및 주소: https://slack.com/intl/ko-kr/



**2. 개발자 커리어 START**

 2-1. 개발자 로드맵 구상
   - 키워드
         Data Analyst Roadmap
         AI and Data Scientist Roadmap
         
         Data Engineer Roadmap
         SQL Roadmap
         Backend Beginner Roadmap
         Backend Roadmap
         Python Roadmap
     - 위와 같은 키워드를 아래 주소에 검색하면 해당업의 로드맵을 볼 수 있음
          주소: https://roadmap.sh/


 2-2. Git & GitHub
 
      - 형상관리툴 : 어떠한 문서나 파일이 변경된 경우, 변경된 내용과 그 원인을 기록하였다가 나중에 필요한 경우 찾아볼 수 있도록 하여 관리하는 툴
       - 여러 개발자들이 협업을 하기 위한 툴, 서로 코드가 겹치거나 다 합쳐놓고(빌드) 봤을 때 이전 것이 더 좋았다거나, 누가 무슨코드를 건드렸는지 확인한다거나 하기 좋게 만들어진 툴
       - Git 설치 : https://git-scm.com/downloads
       - 그림으로 Git 개념 이해: https://ux.stories.pe.kr/182?category=832417
       - 매뉴얼: https://nulab.com/ko/learn/software-development/git-tutorial/
       - Git 기본 개념 정리 노트: https://nanite.tistory.com/39


 2-3. GitHub프로필 만들기
 
    - 프로젝트 혹은 학습이력 등의 확인을 위해서 GitHub 주소를 제출받거나 확인하는 회사가 많아지는 추세
         - 코드 뿐만 아니라, GitHub 자체가 얼마나 잘 관리되고 있는지도 확인함
         - 잘 꾸며놓은 Profile은 문서화 능력이나 디자인 능력 또한 좋다는 인상을 줄 수 있음
    - 프로필 참고: https://zzetao.github.io/awesome-github-profile/
    - 마크다운 생성: https://qus0in.github.io/paste_profile/
             - 마크다운(Markdown)은 간단한 문법을 사용해 텍스트를 서식이 있는 문서로 변환하는 도구 (= 텍스트 꾸미기 문법)
             - '#'을 사용해 제목을 만들거나, '*'를 사용해 리스트를 만들거나, '_'를 사용해 텍스트를 기울이는 등의 간단한 문법을 사용하여 작성된 텍스트를 HTML과 같은 서식이 있는 문서로 쉽게 변환할 수 있음
             - GitHub에서는 마크다운을 사용하여 문서를 작성하고 공유할 수 있으며, 이를 통해 코드 설명, 프로젝트 설명서 등을 직관적이고 깔끔하게 작성하고 공유할 수 있음

 
 2-4. 리뷰 템플릿
 
      - 교육이 끝난 뒤 리뷰 탬플릿을 사용하여 리뷰를 남기는 것이 도움이 많이 되니 작성해보는 것을 추천
      - 리뷰 방법론
             1) 네줄리뷰(Four Lines Review)
                     - 사실(Facts): 어떠한 일들이 있었는지
                     - 발견(Discovery): 그 속에서 알게된 점은 무엇인지
                     - 배운점(Lesson Learned): 어떤 점을 배웠는지
                     - 선언(Daclaration): 배우고 알게 된 점을 바탕으로 앞으로 무엇을 하고 싶은지

             2) KPT(Keep, Problem, Try)
                      - Keep: 잘 했기 때문에 유지하고 싶은 것
                      - Problem: 어려움을 느껴 개선하고 싶은 것
                      - Try: 구체적으로 시도할 내용
           
            3) 4F(Fact, Feeling, Finding, Future Action)
               - 사실(Fact), 느낌(Feeling), 교훈(Finding), 향후 행동(Future Action) 순서대로 회고하는 방법
                      - 사실(Fact): 무슨 일이 있었는지, 어떤 일을 했는지
                      - 느낌(Feeling): 어떤 감정을 느꼈는지
                      - 교훈(Finding): 어떤 지식과 인사이트를 얻었는지
                      - 향후 행동(Future Action): 앞으로 무엇을 할 계획인지
            


**1일차 교육 리뷰**
 - 사실(Fact): 환경 설정, GitHub의 프로필 설정
 - 느낌(Feeling): 위에 나열한 환경을 설정하는 하는 것에 어려움은 없었으나, GitHub의 프로필 설정에 중요성을 느낌
 - 교훈(Finding): GitHub의 프로필을 주기적으로 업데이트하는 것이 취업에 많은 도움이 될것 같음
 - 향후 행동(Future Action): 앞으로 주기적으로 GitHub의 프로필을 업데이터할 것 



